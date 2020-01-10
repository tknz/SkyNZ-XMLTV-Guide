# SkyNZ-XMLTV-Guide
XMLTV Guide for Sky TV NZ Pulled from the air waves

I built this to integrate TVHeadend with Plex via TVH Proxy. TVHeadend did a pretty terrible job of grabbing the EPG and it had non ASCII characters to top things off. I'm not sure who's fault the invalid characters are whether it's Sky or TVH but nonetheless this is a workaround so Plex will ingest.

There is a script that runs to clean up the XML file and then pushes it to GIT where plex consumes it for DVR.
