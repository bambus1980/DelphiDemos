#Location Sensor Patch

##Brief Description 
This demo shows you how to use the LocationSensor on Android Service in Delphi Seattle. 
This demo contains a patch because there is a bug in Delphi (https://quality.embarcadero.com/browse/RSP-12635) that not allow you to use LocationSensor on Android Service (more info here http://www.danielespinetti.it/2016/01/using-locationsensor-on-android-service.html).
To use the demo create, in patch folder (same level of .grupproj), the files System.Android.SensorsDD.pas and System.SensorsDD.pas following the instructions provided in http://www.danielespinetti.it/2016/01/using-locationsensor-on-android-service.html.
The patch is figured out by Daniele Spinetti and Daniele Teti.

##Language
- Object Pascal

##Delphi Supported Versions
- Seattle

##Platforms supported 
- Android

##Keywords 
- Android, Service, Location