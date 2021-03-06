.. _UIEvent.UIEvent:

================================================
UIEvent.UIEvent
================================================

   :ref:`UIEvent` **UIEvent** (:ref:`String` **type**, :ref:`Boolean` **captures**, :ref:`Boolean` **bubbles**, :ref:`Object` **view**, :ref:`Number` **detail**)


Parameters
----------

+--------------+--------------------------------------------------+
| **type**     | The event type. See UIEvent.type property.       |
+--------------+--------------------------------------------------+
| **captures** | Set to true if this event can be captured.       |
+--------------+--------------------------------------------------+
| **bubbles**  | Set to true if the event bubbles.                |
+--------------+--------------------------------------------------+
| **view**     | The ScriptUI element that this event relates to. |
+--------------+--------------------------------------------------+
| **detail**   | The click count for a mouse-click event.         |
+--------------+--------------------------------------------------+



Description
-----------

Creates an event.

The UIEvent object is normally created by ScriptUI and passed to your event handler. However, you can simulate a user action by constructing an event object and sending it to a target object's dispatchEvent() function.


