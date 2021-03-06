.. _PDFSaveOptions:

================================================
PDFSaveOptions
================================================


Description
-----------

Options for saving a document in PDF format.






Static Properties
^^^^^^^^^^^^^^^^^

+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`PDFCompatibility<PDFSaveOptions.PDFCompatibility>`             | The PDF version to make the document compatible with.                                                                  |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`PDFStandard<PDFSaveOptions.PDFStandard>`                       | The PDF standard to make the document compatible with.                                                                 |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`alphaChannels<PDFSaveOptions.alphaChannels>`                   | If true, the alpha channels are saved.                                                                                 |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`annotations<PDFSaveOptions.annotations>`                       | If true, the annotations are saved.                                                                                    |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`colorConversion<PDFSaveOptions.colorConversion>`               | If true, converts the color profile to the destination profile.                                                        |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`convertToEightBit<PDFSaveOptions.convertToEightBit>`           | If true, converts a 16-bit image to 8-bit for better compatibility with other applications.                            |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`description<PDFSaveOptions.description>`                       | Description of the save options in use.                                                                                |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`destinationProfile<PDFSaveOptions.destinationProfile>`         | Describes the final RGB or CMYK output device, such as a monitor or press standard.                                    |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`downSample<PDFSaveOptions.downSample>`                         | The downsample method to use.                                                                                          |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`downSampleSize<PDFSaveOptions.downSampleSize>`                 | The size (in pixels per inch) to downsample images to if they exceed the value specified for 'down sample size limit'. |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`downSampleSizeLimit<PDFSaveOptions.downSampleSizeLimit>`       | Limits downsampling or subsampling to images that exceed this value (in pixels per inch).                              |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`downgradeColorProfile<PDFSaveOptions.downgradeColorProfile>`   | DEPRECATED, ( should the embedded color profile be downgraded to version 2 )                                           |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`embedColorProfile<PDFSaveOptions.embedColorProfile>`           | If true, the color profile is embedded in the document.                                                                |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`embedFonts<PDFSaveOptions.embedFonts>`                         | DEPRECATED. ( embed fonts? Only valid if a text layer is included )                                                    |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`embedThumbnail<PDFSaveOptions.embedThumbnail>`                 | If true, includes a small preview image in Acrobat.                                                                    |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`encoding<PDFSaveOptions.encoding>`                             | The encoding method to use.                                                                                            |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`interpolation<PDFSaveOptions.interpolation>`                   | DEPRECATED. ( use image interpolation? )                                                                               |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`jpegQuality<PDFSaveOptions.jpegQuality>`                       | The quality of the produced image. Valid only for JPEG-encoded PDF documents. Range: 0 to 12.                          |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`layers<PDFSaveOptions.layers>`                                 | If true, the layers are saved.                                                                                         |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`optimizeForWeb<PDFSaveOptions.optimizeForWeb>`                 | If true, improves performance of PDFs on Web servers.                                                                  |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`outputCondition<PDFSaveOptions.outputCondition>`               | An optional comment field for inserting descriptions of the output condition. The text is stored in the PDF/X file.    |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`outputConditionID<PDFSaveOptions.outputConditionID>`           | The identifier for the output condition.                                                                               |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`preserveEditing<PDFSaveOptions.preserveEditing>`               | If true, allows users to reopen the PDF in Photoshop with native Photoshop data intact.                                |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`presetFile<PDFSaveOptions.presetFile>`                         | The preset file to use for settings; overrides other settings.                                                         |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`profileInclusionPolicy<PDFSaveOptions.profileInclusionPolicy>` | If true, shows which profiles to include.                                                                              |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`registryName<PDFSaveOptions.registryName>`                     | The URL where the output condition is registered.                                                                      |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`spotColors<PDFSaveOptions.spotColors>`                         | If true, the spot colors are saved.                                                                                    |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`tileSize<PDFSaveOptions.tileSize>`                             | The compression option. Valid only when encoding is JPEG2000.                                                          |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`transparency<PDFSaveOptions.transparency>`                     | DEPRECATED.                                                                                                            |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`useOutlines<PDFSaveOptions.useOutlines>`                       | DEPRECATED. ( use outlines for text? Only valid if vector data is included )                                           |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`vectorData<PDFSaveOptions.vectorData>`                         | DEPRECATED. ( include vector data )                                                                                    |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`view<PDFSaveOptions.view>`                                     | If true, opens the saved PDF in Acrobat.                                                                               |
+----------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------+












.. container:: hide

   .. toctree::
      :hidden:
      :maxdepth: 1

      
      PDFSaveOptions/alphaChannels.rst
      PDFSaveOptions/layers.rst
      PDFSaveOptions/annotations.rst
      PDFSaveOptions/spotColors.rst
      PDFSaveOptions/embedColorProfile.rst
      PDFSaveOptions/downgradeColorProfile.rst
      PDFSaveOptions/transparency.rst
      PDFSaveOptions/interpolation.rst
      PDFSaveOptions/vectorData.rst
      PDFSaveOptions/embedFonts.rst
      PDFSaveOptions/useOutlines.rst
      PDFSaveOptions/encoding.rst
      PDFSaveOptions/jpegQuality.rst
      PDFSaveOptions/presetFile.rst
      PDFSaveOptions/PDFStandard.rst
      PDFSaveOptions/PDFCompatibility.rst
      PDFSaveOptions/description.rst
      PDFSaveOptions/preserveEditing.rst
      PDFSaveOptions/embedThumbnail.rst
      PDFSaveOptions/optimizeForWeb.rst
      PDFSaveOptions/view.rst
      PDFSaveOptions/downSample.rst
      PDFSaveOptions/downSampleSize.rst
      PDFSaveOptions/downSampleSizeLimit.rst
      PDFSaveOptions/tileSize.rst
      PDFSaveOptions/convertToEightBit.rst
      PDFSaveOptions/colorConversion.rst
      PDFSaveOptions/destinationProfile.rst
      PDFSaveOptions/profileInclusionPolicy.rst
      PDFSaveOptions/outputCondition.rst
      PDFSaveOptions/outputConditionID.rst
      PDFSaveOptions/registryName.rst
      

      
      
      
      