
Overview
========

jquery-confirm-button is a jquery-ui plugin.  It provides an extension
of jquery-ui's button widget that gives you a modal button similar to
buttons that are found on mobile platforms.


Rationale
---------

This gives you a quick mechanism for providing non-intrusive
confirmation.  This is generally easier than providing a dialog
for confirmation.


Usage
=====

Usage is very similar to jquery-ui's button.  In fact you can pass all
of the normal jquery-ui button's option as the 'button' option.

  $('<query>').confirmButton({
		button: { 
			label:  "Format C:\\"
		},
		confirmLabel : 'REALL?'
		
	});
  $('<query>').bind('confirmedclick', function(){
		//gets fired upon confirmed click
  });


Events
------

* 'confirmedclick' -- gets fired upon clicking the button in confirm mode
* 'click' -- The 'primitive' button click event this fires in both normal and confirm mode


Options
-------

* button -- The button option gets passed to the button itself This is more useful for initialization as you can still use .button()
* confirmlabel -- The text to set the label of the button to in confirm
* confirmStyle -- name of style to show only when in confirm mode
* normalStyle -- name of style to show only while the button is in
  confirm mode 


