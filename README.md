cssparser
=========

基于字符串来解析CSS, 更主要的目的是保留CSS的所有内容, 包括注释和Hack, 在toString的时候还能原样还原

解析的内核是基于 [XMLParser ](https://github.com/iazrael/xmlparser) 的 interpreter.
