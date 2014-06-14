j23-sound-pgb-helloworld
========================

June 14, 2014  Fixed the problem listed below. 

May 8, 2014 Created an interesting problem. Using wifi and the Phonegap Developer App I updated the code to work on both Android and iOS, but forgot to test it on Phonegap build. I had not included the device plugin in my config file. So the advanced file has not been working since May.


April 16, 2014 Finally Success!




I have got sound working using Phonegap Build 3.4 html5 audio play tags activated using javascript.

Also using the Device plugin I have got working polyphonic playing of multiple .mp3, .wav or .m4a

Quick playing of the files using .play then .pause as a pre-load (This should be put in an onDeviceReady function)
Record of audio to the Download folder or the root of the sdcard. Very finicky about naming when recording. Flexible on playback. 

Just found out that if you make a folder on you sdcard, then that folder can be saved into using the start record button.



The index.html code can be used on win8 Chrome. It does not work on many other platforms. However if you want to do any advanced sound work I would suggest using the Media plugin.






may 7, 2014 trying to get recording working for iOS by setting the path using

var path = (device.platform == "Android") ? "/android_asset/www/audio/" : "/audio/";


Note: Recently when testing on google chrome found .m4a sounds working fine using html5 sudio


************************************************************************************************************

###Disclaimer: I spend my time getting complex things working in simple ways. I have no idea if I am doing anything correctly so please beware if you use my work. If you like this App and can hum, play or sing please help the musically illiterate, use a flash capable computer to add your favorite song at http://www.rocksetta.com 


