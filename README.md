epub-check-test
===============

*invalid* epub documents to test epub validator conformance.


files and error messages
------------------------

- epubsample000.epub : (valid)
- epubsample001.epub : Content is not allowed in prolog
- epubsample002.epub : Content is not allowed in trailing section
- epubsample003.epub : element "h2" not allowed here; expected the element ...
- epubsample004.epub : element "metadata" incomplete; missing required element "dc:language"
- epubsample005.epub : The prefix "foo" for element "foo:elem" is not bound
- epubsample006.epub : element "link" missing required attribute "href"
- epubsample007.epub : Element type "p" must be followed by either attribute specifications, ">" or "/>"
- epubsample008.epub : attribute "foo" not allowed here; expected attribute ...
- epubsample009.epub : The prefix "epub" for attribute "epub:type" associated with an element type "section" is not bound
- epubsample010.epub : duplicate id: id1
- epubsample011.epub : value of attribute "id" is invalid; must be an XML name without colons
- epubsample012.epub : The value of attribute "id" associated with an element type "p" must notcontain the '<' character
- epubsample013.epub : Only UTF-8 and UTF-16 encodings are allowed, detected SHIFT_JIS
- epubsample014.epub : ???
