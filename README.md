# Moodle-Presentations2Go
Moodle Activity plugin for retrieving and presenting video files from Presentations 2Go Learning video platform.

About Presentations 2Go Learning Video Platform
Increase student engagement and retention with live video streaming and video on demand of lectures, classes and events. Presentations 2Go is a comprehensive solution for recording and capturing of live events, management of content, metadata and multiplatform streaming. Capable of streaming to any device, campus and worldwide.
Presentations 2Go suite of video capture software lets you make easily rich media content by simultaneously capturing and broadcast live video, audio and any presentation source.
Presentations 2Go Video Server is the most complete solution for Learning Video Management. Setup your campus video portal on-premise or in the cloud and start with lecture capture, live webcasting and flipping the classroom.
Users can upload their own video or audio files to a secure environment, and use the video portal to share them with other users. Use Presentations 2Go capture solutions to link presentations to video images and send them out live. They can also be made automatically available on demand.


About Moodle
Moodle is a learning platform designed to provide educators, administrators and learners with a single robust, secure and integrated system to create personalised learning environments. You can download the software onto your own web server or ask one of our knowledgable Moodle Partners to assist you.
Moodle is built by the Moodle project which is led and coordinated by Moodle HQ, an Australian company of 30 developers which is financially supported by a network of over 60 Moodle Partner service companies worldwide.


About this project
This public code makes it possible to integrate restricted videos from a Presentations 2Go video platform into a Moodle course as activity module.
Moodle administrators can setup multiple video respositories for the staff. Course creators can assign a dynamic list (query based), or individual videos to an activity. 
Students can view the videos without signing in to the video platform. 

Restrictions
- Moodle plugins cannot handle numbers in the projectname, e.g. ptogo instead of p2go
- You can upload zipped plugins into Moodle but this requires the root of the zip only contains a folder with the plugin name 
- When removing this plugin, all of its activity content and repository settings will also be permanently removed !!!!! We haven't found a way around this!
- For now, when upgrading, overwrite the plugin content serverside to prevent dataloss 
- Do not DELETE the plugin server side, uninstall via the moodle plugin administration. Otherwise the Moodle database will be inconsistent.





