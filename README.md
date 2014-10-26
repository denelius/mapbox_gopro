Mapbox GoPro video map overhaul based on https://www.mapbox.com/blog/gopro-video-maps/ The demo is designed to get you up and running with a working example in a few as steps as possible. For a more robust setup consider a dynamic upload from the GPS enabled device direct to your favorite database. Possible use cases include visualizing video captured by UAV or quad copter and automation from device to final output.

4 files are required; place them in a folder anywhere on your local environment/server-public_html:

Video file - you are welcome to use the reference included in the demo until you switch it out with your own

mapbox_gopro_min.html - click on this file to run the application in the browser

rotate_video.js - main workings, leave as is for demo OR adjust content/settings to point at your material

north.png - icon file, use or replace with an icon of your choice

To add your own content:

1.) change the video ref to point at your video - line 29 mapbox_gopro_min.html

2.) replace pjson content with json specific to your video - line 1 rotate_video.js 

3.) adjust mapbox access token and key to your account - lines 158 - 159 rotate_video.js 

4.) adjust map center and zoom factor to your path lines - 159 rotate_video.js

