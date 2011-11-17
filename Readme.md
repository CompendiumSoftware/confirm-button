
Overview
========

jquery-confirm-button is a jquery-ui plugin.  It provides an extension
of jquery-ui's button widget.


Rationale
---------

This gives you



Usage
=====


Events
------

* 'confirmedclick' -- gets fired upon clicking the button in confirm mode
** this is the only new event on top of button
* 'click' -- The 'primitive' button click event this fires in both normal and confirm mode
* since this is really an extension on top of jquery-ui button any button events will still fire 


Options
-------

* button -- The button option gets passed to the button itself This is more useful for initialization as you can still use .button()
* confirmlabel -- The text to set the label of the button to in confirm
  mode



