PhidgetsPython
==============

The Python Libraries for the Phidgets System.

The Phidgets System is a great platform for building sensing and control mechanisms using a variety of sensors. They're off-the-shelf and have enclosures, making them preferable to creating custom one-off electronic solutions.

The purpose of this repo is to share a bug fix in the Python library for communicating with the Phidgets 1023-1 RFID Reader.

Using the Python library, as available from Phidgets.com led to this error:<br />
<b>AttributeError: dlsym(0x100474c50, CPhidgetRFID_set_OnTag2_Handler): symbol not found</b>

A description of the original issue (with errors) is described here:<br />
https://www.phidgets.com/phorum/viewtopic.php?f=26&t=6103&p=21896

The master branch on here has fixed this issue.

See the important changes here:<br />
https://github.com/camb416/PhidgetsPython/commit/3b682b7953176eca41a5e9689706bff4d81e7a8a

Screenshot:
![screenshot](https://raw.github.com/camb416/PhidgetsPython/master/screenshot.png)

There's still an issue with a segfault on quit (as seen above). Will likely get around to that eventually.



Originally Downloaded from:<br /> 
http://www.phidgets.com/downloads/libraries/PhidgetsPython.zip <br />
on<br />
http://www.phidgets.com/docs/Language_-_Python#Quick_Downloads <br />
03-19-2013
