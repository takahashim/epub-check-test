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
- epubsample015.epub : ???
- epubsample016.epub : Any Publication Resource that is an XML-Based Media Type must be a conformant XML 1.0 Document. XML Version retrieved: 1.1
- epubsample017.epub : 'OPS/css/stylesheet000.css': referenced resource missing in the package.
- epubsample018.epub : 'foo': fragment identifier is not defined in 'OPS/chapter_001.xhtml'
- epubsample019.epub : File name contains characters disallowed in OCF file names: ">"
- epubsample020.epub : Filename contains spaces. Consider changing filename such that URI escaping is not necessary
- epubsample021.epub : Filename is not allowed to end with '.'.
- epubsample022.epub : File name contains non-ascii characters: 章. Consider changing filename
- epubsample023.epub : (I/O error: error in opening zip file)
- epubsample024.epub : ???
- epubsample025.epub : Length of the first filename in archive must be 8, but was 9
- epubsample026.epub : Mimetype contains wrong type (application/epub+zip expected).
- epubsample027.epub : Mimetype file should contain only the string "application/epub+zip".
- epubsample028.epub : Required META-INF/container.xml resource is missing
- epubsample029.epub : No rootfile with media type 'application/oebps-package+xml'
- epubsample030.epub : (Version not found??)
- epubsample031.epub : unique-identifier attribute in package element must reference an existing identifier element id
- epubsample032.epub : character content of element "dc:identifier" invalid; must be a string with length at least 1 (actual length was 0)
