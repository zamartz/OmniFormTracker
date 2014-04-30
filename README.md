OmniFormTracker
===============

Omniture Form Tracker JavaScript - Tracks all form processes on a page and creates a path. Once page leaves on (Refresh, Navigate, Form Submit) send list to omniture. Tracks with Omniture s.tl() "o" custome link type. Adobe SiteCatalyst

## Details

* Report String - string is reported with Bar "|" separators and identifies error clicks with Asterisk "*"

   `textarea | field | selection | option | checkbox | *checkboxerror` 

* Errors Corrected - Changes "error" to the class that signifies an error on a form element. 

   `var errorflagclass = "error";` 
   
   If the from uses a class to identify errors when the element is clicked to be corrected it will now repport with an error flag.
   
* NAME or ID - reports with either form element 'id" or "name" in patch. Reports with the form "id" first and the "name" as fallback. If there is no "id" or "name" defined for the form element "No ID or NAME" is returned. 

* Tracking Correlation - If `s.linkTrackVars ="";` is set to be blank, all omniture events on page will report. 

   If defined only the narrow scope will be correlated to the form tracking.
 `/*SEND SPECIFIC PROPS*/  s.linkTrackVars = 'prop5,prop6,events'; `

## License

License: GPLv2 or later

License URI: [http://www.gnu.org/licenses/gpl-2.0.html](http://www.gnu.org/licenses/gpl-2.0.html)

## [Donate](http://bt.zamartz.com/1hXxxk2)
