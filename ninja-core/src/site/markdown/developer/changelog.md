Version 1.1.x (current)
=======================

 * PLZ ADD YOUR CHANGES HERE :)
 * Fixes in Validation (phil)
 * Validation for controller parameter fields as well as validation for injected beans (phil)
 * Servelt-Ninja bridge - support for loading Servlet Filters and Servlets using ServletModule (zoza)
 * Cleaner cookie handling (removed dependencies servlet cookies) (ra)
 * Support for force-setting default language via NINJA_LANG cookie (ra)
 * Messages stuff moved from Lang to Message (cleaner)


Version 1.1
===========
 
 * Bugfix: explicitly set content type of result keeps untouched by ResultHandler now (roughy/henning)
 * Added HttpOnly option for the session cookie (roughy)
 * Added support for simple parsing of post forms (aka application/x-www-form-urlencoded) (zoza)
 * Added support for simple rendering of objects in html templates (reyez)

 
Version 1.0.8
=============
 
 * Fixed bug + test with flash scope: https://github.com/reyez/ninja/issues/70 (zoza / ra)

Version 1.0.7
=============

 * Support XML payload parsing on Content-Type: application/xml
 * Fix for multiple values in request "Accept-Language" header

Version 1.0.6
=============

 * Better way to retrieve constraint violations in controller methods (https://github.com/reyez/ninja/pull/58)


Version 1.0.5
=============

 * Fix possible NPE in field validation of controller methods.


Version 1.0.4
=============
 
 * Bump to Gson 2.2.2
 * Fixed encoding issue in TestBrowser that showed up on some English macs


Version 1.0.3
=============
 
 * Added better sending of Json payload to NinjaTestBrowser
 * Utf-8 now default character set when client does not specify correct Content-type
 * Added tests to context
 * Fixed bug where incoming payload was not parsed by correct bodyParser
 
 
Version 1.0.2
=============
 
 * cleanup with develop and master => now only develop active
 * added missing license headers
 * fixed some spelling errors


Version 1.0.1
=============

 * 2012-09-05 Better default http cache-control header handling (no-caching by default).
 * 2012-08-27 Support for better testing whether routes are handled by framework (NinjaRoutesTest).
