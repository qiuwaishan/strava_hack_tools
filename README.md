Strava hacks script collection
===============================

I will uploading here my collections of scripts to get some hacks from Strava.... 

**strava_traces_downloader.py**

with this script you can reconstruct a gpx file from the public strava activity information. without premium account or any else. 

This script doesn't download the original GPX file.  is just some a reconstruction, and is not better than the original GPX File.

When you aren't logged, and the activity is public, we can get 100 points only. Is not bad, but when you are logged and the activities is from a friend, we can get hundred of points (resulting a better GPX file). 

now we don't suppont login. only we can create a GPX with 100 points. 

usage: strava_traces_downloader.py [-h] -a ID_Number [-o output.gpx]

Download GPS Traces from Strava.

optional arguments:
  -h, --help            show this help message and exit
  -a ID_Number, --activity ID_Number
                        ID of activity to download (default: None)
  -o output.gpx, --output output.gpx
                        name of GPX file output. (default: output.gpx)
                        
                        

