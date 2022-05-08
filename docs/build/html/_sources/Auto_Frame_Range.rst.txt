Auto Frame Range
==============================

A Timeline Utility that Automatically Updates and Set Scene's Frame Range to Match Action, NLA, or Sequencer

.. image:: images/AutoFrameRange.png

Mode
----

**Action**: Auto Frame Range Checks the Action of Objects

.. image:: images/ActionAutoFrameRange.gif


**NLA**: Auto Frame Range Checks NLA Strips

.. image:: images/NLAAutoFrameRange.gif

**Sequencer**: Auto Frame Range Checks Video Sequencer Strips

.. image:: images/SequencerAutoFrameRange.gif


.. note::
  
  If you Turn On Only Selected on NLA and Sequencer Mode, It will not Update When You Select the Clip

  It will Only Update if you Move the Strip, that is One of the limitation of this feature


  .. image:: images/StripsLimitation.gif





Action Mode
-----------

**Settings**: Check Manual Frame Range

**Keyframes**: Ignores Manual Frame Range, Only Use First and Last Keyframe Of Action (Curve Frame Range)

Only Selected
-------------

Limits the Checking to Only Selected instead of all objects in the scene


Preferences
-----------

You Can Turn Enable / Disable Auto Frame Range in Preferences

.. image:: images/AutoFrameRangePreferences.png

