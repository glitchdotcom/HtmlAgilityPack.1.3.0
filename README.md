HtmlAgilityPack.1.3.0
=====================

Fork of HtmlAgilityPack focused on performance and stability. Based on 1.3.0, because that's what we use.

Changes include:

* Rewriting HtmlNode.InnerText(), HtmlNode.WriteTo(), and HtmlNode.CloseNode()  to be iterative rather than recursive.
* Patching HtmlNode.InnerText to use a StringBuilder.
* Better handling of incorrect encoding declarations.


License
=======
MS-PL see [LICENSE.txt](https://github.com/FogCreek/HtmlAgilityPack.1.3.0/blob/master/LICENSE.txt)
