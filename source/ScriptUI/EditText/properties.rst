.. _EditText.properties:

================================================
EditText.properties
================================================

   :ref:`Object` **properties**


Description
-----------

An object that contains one or more creation properties of the container (properties used only when the element is created).

Creation properties of an EditText object can include:                            multiline: When false (the default), the control displays a single line of text. When true, the control displays multiple lines, in which case the text wraps within the width of the control.                                         readonly: When false (the default),  the control accepts text input. When true, the control does not accept input but only displays the contents of the text property.                                         noecho: When false (the default), the control displays input text. When true, the control does not display input text (used for password input fields).                                         enterKeySignalsOnChange: When false (the default), the control signals an onChange event when the editable text is changed and the control loses the keyboard focus (that is, the user tabs to another control, clicks outside the control, or types Enter). When true, the control only signals an onChange() event when the editable text is changed and the user types Enter; other changes to the keyboard focus do not signal the event.                                         wantReturn: Only applies to multiple line edit controls in ScriptUI Version 6.0 or later. When true the RETURN/ENTER keystroke is considered as text-input advancing the cursor to the next line. The default value is false.