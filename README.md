# .NET &lt;XML><br><sub>A list of XML libraries, frameworks and tools for .NET

Products are listed in alphabetical order. Data-binding tools are not considered, only products that embrace the XML language.

Have a suggestion? Create an issue or pull request.

### Table of Contents

- [XPath, XQuery and XSLT](#xpath-xquery-and-xslt)
- [Validators](#validators)
- [Document Representations](#document-representations)
- [Parsers](#parsers)
- [Template Engines](#template-engines)

## XPath, XQuery and XSLT

Product | XPath | XQuery | XSLT | FOSS
------- | ----- | ------ | ---- | ----
**[Exselt]**<br><sub>XSLT 3.0 processor | 3.0 | :x: | 3.0 | :x:
**[Lightweight XPath2 for .NET][Lightweight-XPath2]**<br><sub>based on standard XPathNavigator API. See also [StefH's fork][XPath2.Net]. | 2.0 | :x: | :x: | :heavy_check_mark:
**[QueryMachine]**<br><sub>Standalone XQuery and SQL Implementation in .NET | 2.0 | 1.0 | :x: | :heavy_check_mark:
**[Saxon]**<br><sub>XSLT and XQuery Processor. [NuGet][Saxon-NuGet] | 3.1 | 3.1 | 3.0 | :heavy_check_mark:
**[System.Xml]** | 1.0 | :x: | 1.0 | :heavy_check_mark:
**[XmlPrime]**<br><sub>XML Processing for the .NET Framework | 3.1 | 3.1 | 2.0 | :x:

## Validators

Product | Implements | FOSS
------- | ---------- | ----
**[Commons.Xml.Relaxng]**<br><sub>Validates XML with RELAX NG grammar | Relax NG 1.0 | :heavy_check_mark:
**[Saxon][Saxonica]**<br><sub>Saxon can be used as a free-standing schema processor | XSD 1.1 | :x:
**[SchemaTron]**<br><sub>Native C#/.NET implementation of ISO schematron | ISO Schematron | :heavy_check_mark:
**[Schematron.NET]**<br><sub>A Schematron ISO/IEC standard processor for .NET, written in C# | ISO Schematron | :heavy_check_mark:
**[System.Xml]** | XSD 1.0 | :heavy_check_mark:
**[Tenuto]**<br><sub>Relax NG validator for .NET. Implemented in C# | Relax NG 1.0 | :heavy_check_mark:
**[XMLUnit]**<br><sub>Tools to verify the XML you emit is the one you want to create | | :heavy_check_mark:

## Document Representations

Product | Editable | Schema-aware | FOSS
------- | -------- | ------------ | ----
[Saxon.Api.**XdmNode**][Saxon]<br><sub>XdmNode represents a Node in the XDM Data Model | :x: | :x: | :heavy_check_mark:
[System.Xml.Linq.**XDocument**][System.Xml.Linq]<br><sub>Represents an XML document. Optimized for LINQ | :heavy_check_mark: | :x: | :heavy_check_mark:
[System.Xml.**XmlDocument**][System.Xml]<br><sub>Implements the W3C XML Document Object Model (DOM) Level 1 Core and the Core DOM Level 2 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
[System.Xml.XPath.**XPathNavigator**][System.Xml.XPath]<br><sub>Provides a cursor model for navigating and editing XML data. | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:

## Parsers

Product | XML Base | XInclude | FOSS
------- | -------- | -------- | ----
**[Apache Xerces][Saxon]**<br><sub>Included in *Saxon*, cross-compiled from Java | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
**[Microsoft.Language.Xml]**<br><sub>A Roslyn-inspired full-fidelity XML parser with no dependencies and a simple Visual Studio XML language service | :x: | :x: | :heavy_check_mark:
**[Mvp.Xml]**<br><sub>Supplements .NET framework XML processing functionality | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark:
**[SgmlReader]**<br><sub>Parses SGML files using the XmlReader API. See also [MindTouch's fork][SGMLReader-MindTouch]. | | | :heavy_check_mark:
**[System.Xml]** | :x: | :x: | :heavy_check_mark:

## Template Engines

Product | FOSS
------- | ----
**[SharpTAL]**<br><sub>Xml-based template engine for .NET platform | :heavy_check_mark:
**[XCST (eXtensible C-Sharp Templates)][XCST]**<br><sub>Language for transforming objects into XML documents. It is based on a subset of XSLT | :heavy_check_mark:
**[XDT]**<br><sub>Microsoft's Xml Document Transformation library | :heavy_check_mark:


[Commons.Xml.Relaxng]: https://github.com/mono/mono/tree/master/mcs/class/Commons.Xml.Relaxng
[Exselt]: http://exselt.net/
[Lightweight-XPath2]: https://xpath2.codeplex.com/
[Microsoft.Language.Xml]: https://github.com/KirillOsenkov/XmlParser
[Mvp.Xml]: https://mvpxml.codeplex.com/
[QueryMachine]: https://qm.codeplex.com/
[Saxon]: http://saxon.sourceforge.net/
[Saxon-NuGet]: https://www.nuget.org/packages/Saxon-HE
[Saxonica]: http://www.saxonica.com/
[SchemaTron]: https://github.com/gap777/SchemaTron
[Schematron.NET]: https://github.com/kzu/Schematron
[SgmlReader]: https://github.com/lovettchris/SgmlReader
[SGMLReader-MindTouch]: https://github.com/MindTouch/SGMLReader
[SharpTAL]: https://github.com/lck/SharpTAL
[System.Xml]: https://docs.microsoft.com/en-us/dotnet/api/system.xml
[System.Xml.Linq]: https://docs.microsoft.com/en-us/dotnet/api/system.xml.linq
[System.Xml.XPath]: https://docs.microsoft.com/en-us/dotnet/api/system.xml.xpath
[Tenuto]: https://github.com/java-schema-utilities/relaxng-tenuto
[XDT]: https://xdt.codeplex.com/
[XCST]: https://maxtoroq.github.io/XCST/
[XmlPrime]: http://www.xmlprime.com/
[XMLUnit]: http://www.xmlunit.org/
[XPath2.Net]: https://github.com/StefH/XPath2.Net
