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
- epubsample033.epub : assertion failed: package dcterms:modified meta element must occur exactly once
- epubsample034.epub : assertion failed: dcterms:modified illegal syntax (expecting: 'CCYY-MM-DDThh:mm:ssZ')
- epubsample035.epub : assertion failed: @refines missing target id: 'creator02'
- epubsample036.epub : OPS/XHTML file OPS/chapter_002.xhtml is missing
- epubsample037.epub : item (OPS/chapter_002.xhtml) exists in the zip file, but is not declared in the OPF file
- epubsample038.epub : Only audio and video remote resources are permitted
- epubsample039.epub : Item property: cover-image is not defined for media type: text/css
- epubsample040.epub : This file should declare in opf the property: scripted
- epubsample041.epub : assertion failed: Exactly one manifest item must declare the 'nav' property (number of 'nav' items: 2).
- epubsample042.epub : assertion failed: Multiple occurrences of the 'cover-image' property (number of 'cover-image' items: 2).
- epubsample043.epub : Object type and the item media-type declared in manifest, do not match
- epubsample044.epub : assertion failed: manifest item element fallback attribute must resolve to another manifest item (given reference was 'foo') (+ "fallback item could not be found"???)
- epubsample045.epub : Spine item with non-standard media-type 'text/css' with no fallback
- epubsample046.epub : Spine item with non-standard media-type 'image/png' with fallback to non-spine-allowed media-type
- epubsample047.epub : circular reference in fallback chain
- epubsample048.epub : assertion failed: media overlay items must be of the 'application/smil+xml' type (given type was 'image/png')



LICENSES
--------
The base EPUB file epubsample000.epub is derived from moby-dick (https://code.google.com/p/epub-samples/wiki/SamplesListing#moby-dick), so the license of EPUB files in this repository are CC BY-SA 3.0.

poignant-guide_chapter-1-introducing.mp3 (in epubsample049) is from "THE SOUNDTRACK TO why's (poignant) guide to ruby" (http://mislav.uniqpath.com/poignant-guide/soundtrack/). The license of this file is CC BY-SA 2.5. (http://creativecommons.org/licenses/by-sa/2.5/)
