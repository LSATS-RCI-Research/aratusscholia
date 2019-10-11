# Aratus Project Custom Theme and Admin console modifications

Modified theme for Omeka S. Allows for items listed in browse view to list all their metadata inline. Also updated admin console so item list view has an additional column and item view matches the site item view in the theme.The files that were modified were layout.phtml, browse.phtml, and show.phtml. There are comments where new code was added or removed (commented out)

To install, uncompress the view.zip file and replace the files in that path on the Omeka server. 


Data dictionary:
* dcterms:title = Scholium Number
* dcterms:identifier = Paragraph
* bibo:edition = Manuscript
* dcterms:description = Greek/Latin Text Col. 1
* dcterms:extent = Greek/Latin Text Col. 2
* dcterms:format = Greek/Latin Text Col 3
* bibo:translationOf = English Translation Col. 1
* bibo:transcriptOf = English Translation Col. 2
* bibo:translator = English Translation Col. 3
* bibo:locator = Greek Key Terms
* bibo:number = English Key Terms
* dcterms:subject = Constellations/Themes
* dcterms:bibliographicCitation = Bibliographic Citation
* foaf:topic = Notes
* foaf:knows = Voice
