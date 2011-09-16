MOB117 - Consume SAP on your Mobile Device in under an hour
Eric Vota - eric.vota@paccoast.com 
@ericvota on Twitter
---
Relevant files:
index.html - This is the bulk of the "application"  Read the comments in the code for details about what each section is doing
abap.txt - This is the code from a class in ABAP that implements the HandleRequest method of the IF_HTTP_EXTENSION interface.  You will use this
           to create a Handler that you will use in an ICF service (transaction SICF) on the ABAP application server.
icon.png - You can change this file to be a new image that you want to display on your app, this is just the default PhoneGap icon
assets directory - In here you'll find all the javascript, css, and datafiles.  You don't HAVE to use these if you aren't using phonegap and/or if you just want
				   to link to the hosted jQuery and jQuery mobile files (hosted by jquery).  The data directory contains a JSON file (zjson_teched) that you
				   can fool with if you don't want (or can't) connect to the SAP server
AllSessionMaterials - There is a zip folder in here with all the code in it and the presentation.  If you want to work outside of git, just download the zip file 
						extract it somewhere on your computer and get to coding!
				   
Notes for testing:
You can test the app in any old browser although IE is not great at rendering jQueryMobile yet.  I used Safari because it is the closest to what an iPhone/iPad would use,
but Chrome and Firefox work fine as well.  Additionally, if you didn't want to "package" an application via PhoneGap (or any other tool), you could always just
upload the index.html (and any supporting files) to any old web server (even the ABAP web server) and test via the Mobile devices browser by simply entering the URL
in the browser.

Please feel free to contact me if you have any additional questions.  I don't live in my email box, but check it at least once a day.