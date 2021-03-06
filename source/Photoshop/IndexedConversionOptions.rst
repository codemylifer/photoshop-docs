.. _IndexedConversionOptions:

================================================
IndexedConversionOptions
================================================


Description
-----------

Options for converting an RGB image to an indexed color model.






Static Properties
^^^^^^^^^^^^^^^^^

+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`colors<IndexedConversionOptions.colors>`                           | The number of colors in the palette. Not valid for all palette types.                                                                                               |
+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`dither<IndexedConversionOptions.dither>`                           | The type of dither.                                                                                                                                                 |
+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`ditherAmount<IndexedConversionOptions.ditherAmount>`               | The amount of dither. Valid only when 'dither' = diffusion.                                                                                                         |
+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`forced<IndexedConversionOptions.forced>`                           | The type of colors to force into the color palette.                                                                                                                 |
+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`matte<IndexedConversionOptions.matte>`                             | The color to use to fill anti-aliased edges adjacent to transparent areas of the image. When transparency = false, the matte color is applied to transparent areas. |
+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`palette<IndexedConversionOptions.palette>`                         | The type of palette.                                                                                                                                                |
+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`preserveExactColors<IndexedConversionOptions.preserveExactColors>` | If true, protects colors in the image that contain entries in the color table from being dithered. Valid only when 'dither' = diffusion.                            |
+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`transparency<IndexedConversionOptions.transparency>`               | If true, preserves transparent areas of the image during conversion to GIF format.                                                                                  |
+--------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------+












.. container:: hide

   .. toctree::
      :hidden:
      :maxdepth: 1

      
      IndexedConversionOptions/palette.rst
      IndexedConversionOptions/colors.rst
      IndexedConversionOptions/forced.rst
      IndexedConversionOptions/transparency.rst
      IndexedConversionOptions/dither.rst
      IndexedConversionOptions/ditherAmount.rst
      IndexedConversionOptions/preserveExactColors.rst
      IndexedConversionOptions/matte.rst
      

      
      
      
      