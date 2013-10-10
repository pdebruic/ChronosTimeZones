ChronosTimeZones
=======

The Chronos date and time library for Smalltalk requires a set of time zone rules to deal with daylight savings time transiations. 

The repo includes a probably up to date set of chronos time-zone rules that are updated regularly


#### updating the rules yourself
1. Using a linux that can run a 32bit Pharo 1.3 image
2. download this zip file from my dropbox that contains an image+vm+script
    https://dl.dropboxusercontent.com/u/4460862/chronosUpdater.zip
3. unzip the archive and run updateTimeZonesLinux.sh


If things go according to plan the script will download the latest rules, extract them, have Chronos process them, and leave an upated time-zones directory next to the image.
