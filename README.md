OmniFormTracker
===============

Omniture Form Tracker JavaScript - Tracks all form processes on a page and creates a path. Once page leaves on (Refresh, Navigate, Form Submit) send list to omniture. Tracks with Omnuture s.tl() "o" custome link type.

## Details

* Reports string with Bar "|" separators and identifies error clicks with Asterisk "*"

   `textarea | field | selection | option | checkbox | *checkboxerror` 

* Report on Errors Corrected. Changes "error" to the class that signifies an error on a form element. 

   `var errorflagclass = "error";`
   
* Reports with either form element 'id" or "name" in patch. Reports with the form "id" first and the "name" as fallback. If there is no "id" or "name" defined for the form element "No ID or NAME" is returned. 

* Edit `/*SEND SPECIFIC PROPS*/ /* s.linkTrackVars = 'prop5,prop6,events'; */ /*SENDS ALL ON PAGE*/ s.linkTrackVars = '';`
If you set `s.linkTrackVars` all omniture events on page will report. If defined only the narrow scope will be corrolated to the form tracking

## License

License: GPLv2 or later

License URI: [http://www.gnu.org/licenses/gpl-2.0.html](http://www.gnu.org/licenses/gpl-2.0.html)

## [Donate](http://bt.zamartz.com/1hXxxk2)
