---
title: Included Assemblies
page_title: Included Assemblies | UI for ASP.NET AJAX Documentation
description: Included Assemblies
slug: introduction/installation/included-assemblies
tags: included,assemblies
published: True
position: 1
---

# Included Assemblies



This article explains what assemblies are included in the Telerik UI for ASP.NET AJAX installation: the main Telerik.Web.UI assemblies, the	[Telerik ZIP library](http://www.telerik.com/products/silverlight/zip-library.aspx) and	the Telerik Document processing libraries ([text processing](http://www.telerik.com/products/wpf/words-processing.aspx) and	[spreadsheet processing](http://www.telerik.com/products/wpf/spreadsheet-processing.aspx)). You can find more information about them in the sections below.

The assemblies come sorted in several folders so that you can use the appropriate ones.	Depending on the .NET framework version your project targets, you will find the needed assemblies in the corresponding directory. For example, if you target *.NET 4.0*, you will need the assemblies from the *Bin40* folder. If you target *.NET 4.5* or *.NET 4.6*, you should use the assemblies from the *Bin45* folder.

## Main Assemblies

The Telerik UI for ASP.NET AJAX product consists of the assemblies in the list below. You can find them in the root of the installation (both [automated]({%slug introduction/installation/installing-the-telerik-controls-from-msi-file%}) and in the [zip archive]({%slug introduction/installation/installing-the-telerik-controls-from-zip-file%})) and in the	[internal builds archives]({%slug introduction/installation/using-the-hotfix-(dlls-and-scripts/skins-only)%}).

* **Telerik.Web.UI.dll** — the core assembly from the suite where the actual controls are located. It also contains the *Default* skin.

* **Telerik.Web.UI.Skins.dll** — this assembly has all the skins the suite offers (except the *Default* one).If you use only the Default skin, or you only use custom skins, you do not need this assembly.

* **Telerik.Web.Design.dll** — this assembly contains the Visual Studio Design surface code for the suite. The configuration wizards you can access from the controls' Smart Tags are also there. It is only needed if you use the controls in the Design mode in VS and is not needed in the deployed application. The automated installation adds this assembly to the GAC.

* **Telerik.Web.Device.Detection.dll** — the [Telerik Device Detection framework]({%slug controls/raddevicedetectionframework%}) that can help you determine the screen resolution of the device that requested the page while processing the request on the server. It is used by the Telerik controls to determine the [RenderMode]({%slug controls/render-modes%}) when it is set to Auto.

## Telerik ZIP Library

This is a cross-platform library that lets you load, create and update Zip archives on the fly with easy to use API.

You can find its assembly in the **AdditionalLibraries** folder in the Telerik UI for ASP.NET AJAX installation (automated and manual) and in the internal builds archive.It supports .NET 4 and .NET 4.5, so depending on the target framework of your project, you need to take the assembly from the *Bin40* or *Bin45* folder respectively.

* **Telerik.Windows.Zip.dll** — the assembly of the Telerik Zip Library.

* **Telerik.Windows.Zip.Extensions.dll** — extends **Telerik.Windows.Zip** assembly with aditional helper methods ([Zip Extensions](http://docs.telerik.com/devtools/document-processing/libraries/radziplibrary/features/zip-extensions)).

You can read more about it in its documentation: [Getting started with RadZipLibrary](http://docs.telerik.com/devtools/document-processing/libraries/radziplibrary/overview).

## Telerik Document Processing Libraries

The Telerik document processing libraries are a set of assemblies that let you import and export content between different formats.

You can find the needed assemblies in the **AdditionalLibraries** folder in the Telerik UI for ASP.NET AJAX installation (automated and manual) and in the internal builds archive.It supports .NET 4 and .NET 4.5, so depending on the target framework of your project, you need to take the assembly from the *Bin40* or *Bin45* folder respectively.

* **Telerik.Windows.Documents.Core.dll** — the main assembly from the Telerik document processing libraries. You always need it when you intend to use the library.

* **Telerik.Windows.Documents.Flow.dll** — part of the words (text) processing library. It is needed for processing HTML, DOCX, RTF and TXT documents.

* **Telerik.Windows.Zip.dll** — needed for working with zipped formats (DOCX, XLSX) and PDF.

* **Telerik.Windows.Documents.Flow.FormatProviders.Pdf** — allows exporting of flow documents (DOCX, RTF) to PDF.

* **Telerik.Documents.SpreadsheetStreaming.dll**: The main assembly for generating huge spreadsheet files using minimum resources.

* **Telerik.Windows.Documents.Spreadsheet.dll** — the main assembly for the spreadsheet processing. It is needed for processing XLSX, CSV, TXT documents.

* **Telerik.Windows.Documents.Spreadsheet.FormatProviders.OpenXml.dll** — this assembly is needed for processing XLSX documents.

* **Telerik.Windows.Documents.Fixed.dll** — this assembly is needed for processing PDF documents.

* **Telerik.Windows.Documents.Spreadsheet.FormatProviders.Pdf.dll** — this assembly is needed for processing PDF documents.

You can find more information on working with the Telerik document processing libraries in the following articles:

* Words (text) processing

	* [DOCX format provider](http://docs.telerik.com/devtools/document-processing/libraries/radwordsprocessing/formats-and-conversion/docx/docxformatprovider)

	* [HTML format provider](http://docs.telerik.com/devtools/document-processing/libraries/radwordsprocessing/formats-and-conversion/html/htmlformatprovider)

	* [RTF format provider](http://docs.telerik.com/devtools/document-processing/libraries/radwordsprocessing/formats-and-conversion/rtf/rtfformatprovider)

	* [TXT format provider](http://docs.telerik.com/devtools/document-processing/libraries/radwordsprocessing/formats-and-conversion/plain-text/txt-txtformatprovider)

* Spreadsheet processing

	* [Getting Started](http://docs.telerik.com/devtools/document-processing/libraries/radspreadprocessing/getting-started)

	* [XLSX format provider](http://docs.telerik.com/devtools/document-processing/libraries/radspreadprocessing/formats-and-conversion/xlsx/xlsxformatprovider)

	* [CSV format provider](http://docs.telerik.com/devtools/document-processing/libraries/radspreadprocessing/formats-and-conversion/csv/csvformatprovider)

	* [PDF format provider](http://docs.telerik.com/devtools/document-processing/libraries/radspreadprocessing/formats-and-conversion/pdf/pdfformatprovider)

	* [TXT format provider](http://docs.telerik.com/devtools/document-processing/libraries/radspreadprocessing/formats-and-conversion/txt/txtformatprovider)

* PDF processing

	* [PDF format provider](http://docs.telerik.com/devtools/document-processing/libraries/radpdfprocessing/formats-and-conversion/pdf/pdfformatprovider)
	
	* [Text format provider](http://docs.telerik.com/devtools/document-processing/libraries/radpdfprocessing/formats-and-conversion/plain-text/textformatprovider)

* Fast spreadsheet generation
	
	* [Getting Started](http://docs.telerik.com/devtools/document-processing/libraries/radspreadstreamprocessing/getting-started)

## See Also

 * [Telerik ZIP library](http://www.telerik.com/products/silverlight/zip-library.aspx)

 * [Getting started with RadZipLibrary](http://www.telerik.com/help/silverlight/radziplibrary-gettingstarted.html)

 * [Telerik Words Processing Library](http://www.telerik.com/products/wpf/words-processing.aspx)

 * [Telerik Spreadsheet Processing Library](http://www.telerik.com/products/wpf/spreadsheet-processing.aspx)

 * [Telerik Device Detection Framework Overview](http://www.telerik.com/products/aspnet-ajax/device-detection-framework.aspx)
 
 * [Telerik Device Detection Framework API]({%slug controls/raddevicedetectionframework%})
 
 * [UI for ASP.NET AJAX Controls RenderModes Basics]({%slug controls/render-modes%})

