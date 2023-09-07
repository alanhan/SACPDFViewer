# SACPDFViewer

This is an SAP Analytics Cloud custom widget that can be used to embed PDF files in Stories (with Optimized Design Experience enabled) or Analytic Applications.

This repo is forked from https://github.com/ferrygun/SACPDFViewer, with some slight modifications:
* The JS resource file URL is changed to use relative path, this allows us to use the new feature in SAC to host the resource files within SAC itself.
* After you upload the JSON file to SAC Custom Widget, please zip up the two JS resource files (pdfviewer.js & aps_pdfviewer.js) in a ZIP archive and upload to SAC. 

Please refer to this blog post https://blogs.sap.com/2020/11/03/displaying-a-pdf-file-in-sap-analytics-cloud-analytic-app-with-custom-widget/ from the author of this custom widget for more information. 
