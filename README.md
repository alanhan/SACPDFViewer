# SACPDFViewer

This is an SAP Analytics Cloud custom widget that can be used to embed PDF files in Stories (with Optimized Design Experience enabled) or Analytic Applications.

This repo is forked from https://github.com/ferrygun/SACPDFViewer, with some slight modifications:
* The JS resource file URL is changed to use relative path, this allows us to use the new feature in SAC to host the resource files within SAC itself.
* After you upload the JSON file to SAC Custom Widget, please zip up the two JS resource files (pdfviewer.js & aps_pdfviewer.js) in a ZIP archive and upload to SAC. 

Please refer to this blog post https://blogs.sap.com/2020/11/03/displaying-a-pdf-file-in-sap-analytics-cloud-analytic-app-with-custom-widget/ from the author of this custom widget for more information. 

Quick Start Guide:
1. Download the "pdfviewer.json", "pdfviewer.js" and "aps_pdfviewer.js" from this repo
2. In SAC, go to "Analytic Application", and click on the "Custom Widget" tab
3. On the "Custom Widget" page, click the + button, then upload the "pdfviewer.json" file
4. You will then be prompted to upload the resource files, please compress the two JS files into a ZIP archive, and upload it to SAC
5. Now the custom widget is installed successfully. To use it, create a new Story (with optimized design experience enabled) or Analytic Application
6. Add the PDFViewer custom widget to your page
7. With the widget highlighted, go to its Styling panel and scroll to the bottom, you will see "Custom Widet Additional Properties" where you can define the URL to the PDF file, as well as the Title and Height
