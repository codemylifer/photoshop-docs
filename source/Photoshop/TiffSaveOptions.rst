.. _TiffSaveOptions:

================================================
TiffSaveOptions
================================================


Description
-----------

Options for saving a document in TIFF format.






Static Properties
^^^^^^^^^^^^^^^^^

+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`alphaChannels<TiffSaveOptions.alphaChannels>`           | If true, the alpha channels are saved.                                                                                                                                |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`annotations<TiffSaveOptions.annotations>`               | If true, the annotations are saved.                                                                                                                                   |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`byteOrder<TiffSaveOptions.byteOrder>`                   | The order in which the bytes will be read. Default: Mac OS when running in Mac OS, and IBM PC when running in Windows.                                                |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`embedColorProfile<TiffSaveOptions.embedColorProfile>`   | If true, the color profile is embedded in the document.                                                                                                               |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`imageCompression<TiffSaveOptions.imageCompression>`     | The compression type.                                                                                                                                                 |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`interleaveChannels<TiffSaveOptions.interleaveChannels>` | If true, the channels in the image are interleaved.                                                                                                                   |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`jpegQuality<TiffSaveOptions.jpegQuality>`               | The quality of the produced image, which is inversely proportionate to the amount of JPEG compression. Valid only for JPEG compressed TIFF documents. Range: 0 to 12. |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`layerCompression<TiffSaveOptions.layerCompression>`     | The method of compression to use when saving layers (as opposed to saving composite data). Valid only when 'layers' = true.                                           |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`layers<TiffSaveOptions.layers>`                         | If true, the layers are saved.                                                                                                                                        |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`saveImagePyramid<TiffSaveOptions.saveImagePyramid>`     | If true, preserves multi-resolution information.                                                                                                                      |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`spotColors<TiffSaveOptions.spotColors>`                 | If true, spot colors are saved.                                                                                                                                       |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`transparency<TiffSaveOptions.transparency>`             | If true, saves the transparency as an additional alpha channel when the file is opened in another application.                                                        |
+---------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------+












.. container:: hide

   .. toctree::
      :hidden:
      :maxdepth: 1

      
      TiffSaveOptions/alphaChannels.rst
      TiffSaveOptions/layers.rst
      TiffSaveOptions/annotations.rst
      TiffSaveOptions/spotColors.rst
      TiffSaveOptions/embedColorProfile.rst
      TiffSaveOptions/imageCompression.rst
      TiffSaveOptions/jpegQuality.rst
      TiffSaveOptions/byteOrder.rst
      TiffSaveOptions/saveImagePyramid.rst
      TiffSaveOptions/transparency.rst
      TiffSaveOptions/layerCompression.rst
      TiffSaveOptions/interleaveChannels.rst
      

      
      
      
      