.NET &lt;XML>
=============
A list of XML libraries, frameworks and tools for .NET. Products are listed in alphabetical order.

### Table of Contents

- [XPath, XQuery and XSLT](#xpath-xquery-and-xslt)
- [Validators](#validators)
- [Document Representations](#document-representations)
- [Parsers](#parsers)
- [Object Serialization](#object-serialization)

## XPath, XQuery and XSLT

Product | XPath | XQuery | XSLT | FOSS
------- | ----- | ------ | ---- | ----
[Exselt]<br><sub>XSLT 3.0 processor | 3.0 | :x: | 3.0 | :x:
[Lightweight XPath2 for .NET][Lightweight-XPath2]<br><sub>based on standard XPathNavigator API | 2.0 | :x: | :x: | :heavy_check_mark:
[QueryMachine]<br><sub>Standalone XQuery and SQL Implementation in .NET | 2.0 | 1.0 | :x: | :heavy_check_mark:
[Saxon]<br><sub>XSLT and XQuery Processor | 3.1 | 3.1 | 3.0 | :heavy_check_mark:
[System.Xml]<br><sub>Standards-based support for processing XML | 1.0 | :x: | 1.0 | :heavy_check_mark:
[XmlPrime]<br><sub>XML Processing for the .NET Framework | 3.1 | 3.1 | 2.0 | :x:
[XPath2.Net]<br><sub>Fork of *Lightweight XPath2 for .NET* | 2.0 | :x: | :x: | :heavy_check_mark:

## Validators

Product | Implements | FOSS
------- | ---------- | ----
[Commons.Xml.Relaxng]<br><sub>Validates XML with RELAX NG grammar | Relax NG 1.0 | :heavy_check_mark:
[Saxon][Saxonica]<br><sub>Saxon can be used as a free-standing schema processor | XSD 1.1 | :x:
[SchemaTron]<br><sub>Native C#/.NET implementation of ISO schematron | ISO Schematron | :heavy_check_mark:
[Schematron.NET]<br><sub>A Schematron ISO/IEC standard processor for .NET, written in C# | ISO Schematron | :heavy_check_mark:
[System.Xml] | XSD 1.0 | :heavy_check_mark:
[Tenuto]<br><sub>Relax NG validator for .NET. Implemented in C# | Relax NG 1.0 | :heavy_check_mark:

## Document Representations

Product | Editable | Schema-aware | FOSS
------- | -------- | ------------ | ----
[Saxon.Api.XdmNode][Saxon]<br><sub>XdmNode represents a Node in the XDM Data Model | :x: | :x: | :heavy_check_mark:
[System.Xml.XmlDocument][System.Xml]<br><sub>Implements the W3C XML Document Object Model (DOM) Level 1 Core and the Core DOM Level 2 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
[System.Xml.XPath.XPathDocument][System.Xml.XPath]<br><sub>Provides a fast, read-only, in-memory representation of an XML document by using the XPath data model | :x: | :x: | :heavy_check_mark:
[System.Xml.Linq.XDocument][System.Xml.Linq]<br><sub>Represents an XML document. Optimized for LINQ | :heavy_check_mark: | :x: | :heavy_check_mark:
[XmlPrime.XdmDocument][XmlPrime]<br><sub>Provides a fast, read-only, in-memory representation of an XML document using the XQuery 1.0 and XPath 2.0 Data Model (XDM) | :x: | :heavy_check_mark: | :heavy_check_mark:

## Parsers

Product | XML Base | XInclude | FOSS
------- | -------- | -------- | ----
[Apache Xerces][Saxon]<br><sub>Included in *Saxon*, cross-compiled from Java | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
[Microsoft.Language.Xml]<br><sub>A Roslyn-inspired full-fidelity XML parser with no dependencies and a simple Visual Studio XML language service | :x: | :x: | :heavy_check_mark:
[Mvp.Xml]<br><sub>Supplements .NET framework XML processing functionality | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
[SgmlReader]<br><sub>Parses SGML files using the XmlReader API | | | :heavy_check_mark:
[SGMLReader][SGMLReader-MindTouch]<br><sub>MindTouch fork of *SgmlReader* with many improvements | | | :heavy_check_mark:
[System.Xml] | :x: | :x: | :heavy_check_mark:

## Object Serialization

Product | FOSS
------- | ----
[ExtendedXmlSerializer] | :heavy_check_mark:
[SharpSerializer] | :heavy_check_mark:
[System.Runtime.Serialization] | :heavy_check_mark:
[System.Xml.Serialization] | :heavy_check_mark:
[XSerializer] | :heavy_check_mark:
[YAXLib] | :heavy_check_mark:


[Commons.Xml.Relaxng]: https://github.com/mono/mono/tree/master/mcs/class/Commons.Xml.Relaxng
[Exselt]: http://exselt.net/
[ExtendedXmlSerializer]: https://extendedxmlserializer.github.io/
[Lightweight-XPath2]: https://xpath2.codeplex.com/
[Microsoft.Language.Xml]: https://github.com/KirillOsenkov/XmlParser
[Mvp.Xml]: https://mvpxml.codeplex.com/
[QueryMachine]: https://qm.codeplex.com/
[Saxon]: http://saxon.sourceforge.net/
[Saxonica]: http://www.saxonica.com/
[SchemaTron]: https://github.com/gap777/SchemaTron
[Schematron.NET]: https://github.com/kzu/Schematron
[SgmlReader]: https://github.com/lovettchris/SgmlReader
[SGMLReader-MindTouch]: https://github.com/MindTouch/SGMLReader
[SharpSerializer]: https://github.com/polenter/SharpSerializer
[System.Runtime.Serialization]: https://docs.microsoft.com/en-us/dotnet/api/system.runtime.serialization
[System.Xml]: https://docs.microsoft.com/en-us/dotnet/api/system.xml
[System.Xml.Linq]: https://docs.microsoft.com/en-us/dotnet/api/system.xml.linq
[System.Xml.Serialization]: https://docs.microsoft.com/en-us/dotnet/api/system.xml.serialization
[System.Xml.XPath]: https://docs.microsoft.com/en-us/dotnet/api/system.xml.xpath
[Tenuto]: https://github.com/java-schema-utilities/relaxng-tenuto
[XmlPrime]: http://www.xmlprime.com/
[XPath2.Net]: https://github.com/StefH/XPath2.Net
[XSerializer]: https://github.com/QuickenLoans/XSerializer
[YAXLib]: http://sinairv.github.io/yaxlib/
