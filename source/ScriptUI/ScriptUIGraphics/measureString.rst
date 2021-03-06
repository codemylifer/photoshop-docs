.. _ScriptUIGraphics.measureString:

================================================
ScriptUIGraphics.measureString
================================================

   :ref:`Dimension` **measureString** (:ref:`String` **text**, :ref:`ScriptUIFont` **font**, :ref:`Number` **boundingWidth**)


Parameters
----------

+-------------------+------------------------------------------------------------+
| **text**          | The text string to measure.                                |
+-------------------+------------------------------------------------------------+
| **font**          | The font to use. Default is the font value in this object. |
+-------------------+------------------------------------------------------------+
| **boundingWidth** | The bounding width.                                        |
+-------------------+------------------------------------------------------------+



Description
-----------

Calculates the size needed to display a string using the given font.

Returns a Dimension object that contains the height and width of the string in pixels.


