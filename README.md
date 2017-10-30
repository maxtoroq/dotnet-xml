.NET &lt;XML>
=============
A list of XML libraries, frameworks and tools for .NET. Products are listed in alphabetical order.

### Table of Contents

- [XPath, XQuery and XSLT](#xpath-xquery-and-xslt)
- [Validators](#validators)
- [Document Representations](#document-representations)
- [Parsers](#parsers)
- [Data Binding](#data-binding)
- [Template Engines](#template-engines)

## XPath, XQuery and XSLT

Product | XPath | XQuery | XSLT | FOSS
------- | ----- | ------ | ---- | ----
[Exselt]<br><sub>XSLT 3.0 processor | 3.0 | :x: | 3.0 | :x:
[Lightweight XPath2 for .NET][Lightweight-XPath2]<br><sub>based on standard XPathNavigator API | 2.0 | :x: | :x: | :heavy_check_mark:
[QueryMachine]<br><sub>Standalone XQuery and SQL Implementation in .NET | 2.0 | 1.0 | :x: | :heavy_check_mark:
[Saxon]<br><sub>XSLT and XQuery Processor | 3.1 | 3.1 | 3.0 | :heavy_check_mark:
[System.Xml] | 1.0 | :x: | 1.0 | :heavy_check_mark:
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
[XMLUnit]<br><sub>Tools to verify the XML you emit is the one you want to create | | :heavy_check_mark:

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
[SGMLReader (MindTouch)][SGMLReader-MindTouch]<br><sub>Fork of *SgmlReader* with many improvements | | | :heavy_check_mark:
[System.Xml] | :x: | :x: | :heavy_check_mark:

## Data Binding

> XML data binding refers to a means of representing information in an XML document as a business object in computer memory. This allows applications to access the data in the XML from the object rather than using the DOM or SAX to retrieve the data from a direct representation of the XML itself.
> -- [Wikipedia](https://en.wikipedia.org/wiki/XML_data_binding)

Product | Design-time | Run-time | FOSS
------- | ----------- | -------- | ----
[ExtendedXmlSerializer]<br><sub>Extended Xml Serializer for .NET | | :heavy_check_mark: | :heavy_check_mark:
[LINQ to XSD]<br><sub>The LINQ to XSD technology provides .NET developers with support for typed XML programming | :heavy_check_mark: | | :heavy_check_mark:
[SharpSerializer]<br><sub>XML and binary serializer for .NET | | :heavy_check_mark: | :heavy_check_mark:
[System.Runtime.Serialization]<br><sub>Data contract based XML serialization | | :heavy_check_mark: | :heavy_check_mark:
[System.Xml.Serialization]<br><sub>XML Serializer | | :heavy_check_mark: | :heavy_check_mark:
[XSerializer]<br><sub>Provides advanced, high-performance XML and JSON serializers | | :heavy_check_mark: | :heavy_check_mark:
[YAXLib]<br><sub>Flexible XML serialization library that lets developers design freely the XML file structure | | :heavy_check_mark: | :heavy_check_mark:

## Template Engines

Product | FOSS
------- | ----
[SharpTAL]<br><sub>Xml-based template engine for .NET platform | :heavy_check_mark:
[XCST (eXtensible C-Sharp Templates)][XCST]<br><sub>Language for transforming objects into XML documents. It is based on a subset of XSLT | :heavy_check_mark:


[Commons.Xml.Relaxng]: https://github.com/mono/mono/tree/master/mcs/class/Commons.Xml.Relaxng
[Exselt]: http://exselt.net/
[ExtendedXmlSerializer]: https://extendedxmlserializer.github.io/
[Lightweight-XPath2]: https://xpath2.codeplex.com/
[LINQ to XSD]: https://linqtoxsd.codeplex.com/
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
[SharpTAL]: https://github.com/lck/SharpTAL
[System.Runtime.Serialization]: https://docs.microsoft.com/en-us/dotnet/api/system.runtime.serialization
[System.Xml]: https://docs.microsoft.com/en-us/dotnet/api/system.xml
[System.Xml.Linq]: https://docs.microsoft.com/en-us/dotnet/api/system.xml.linq
[System.Xml.Serialization]: https://docs.microsoft.com/en-us/dotnet/api/system.xml.serialization
[System.Xml.XPath]: https://docs.microsoft.com/en-us/dotnet/api/system.xml.xpath
[Tenuto]: https://github.com/java-schema-utilities/relaxng-tenuto
[XCST]: http://maxtoroq.github.io/XCST/
[XmlPrime]: http://www.xmlprime.com/
[XMLUnit]: http://www.xmlunit.org/
[XPath2.Net]: https://github.com/StefH/XPath2.Net
[XSerializer]: https://github.com/QuickenLoans/XSerializer
[YAXLib]: http://sinairv.github.io/yaxlib/
