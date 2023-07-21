# manor_bibtex

Contains BibTex file(s) that can be accessed by BibBase.org, to create an iFrame link to be embedded on lab webpage.


## Instructions
1. Update the .bib file in this repo;
2. Lab publication webpage should update automatically

## BibBase.org code that is being used now:
<iframe src="https://bibbase.org/show?bib=https%3A%2F%2Fgithub.com%2Fsalkmanorlab%2Fmanor_publications%2Fraw%2Fmain%2Fmanorlab_pubs.bib&commas=true&noBootstrap=1"></iframe>
note: shouldn't need to update unless the embedding is not working

## If need to update the iframe code:
1. open [BibBase.org](bibbase.org) and click "Get Started";
2. copy the link of the github path to the .bib file (must be in a public repo) and change the words "blob" to "raw" (eg. github.com/salkmanorlab/manor_publications/raw/main/manorlab_pubs.bib);
3. paste the link to the right box in BibBase get started page (the first one) and enter;
4. copy the code associated with iFrame;
5. enter the code in a text module in the Wordpress page.

