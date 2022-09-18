Arduinolyzer.js
===============

A logic analyzer for the Arduino, implemented in Node.js and HTML5


Overview:

Refer to the Instructables page:

[tbd]

Todo:

Sketch
-- Remove String objects
-- Make all variables global and reuse indices when necessary
   (Or verify that the compiler uses the fastest access mode possible)
-- Possibly code sample functions that are optimized for channel 
   arrangements (e.g., remove extraneous shifting, OR'ing and calls)
-- Use a decreasing call to malloc() during setup() to find the largest
   usable array.
-- Port to Pi & Edison

server.js
-- Remove express, formidable and morgan to make the code smaller and
   reduce dependencies.
-- Reloads of the client '/' and '/index.html' should reset the serial
   port. This would allow interrupting the hardware via client.

index.html
-- Add time-axes and markers
-- Try HTML5 server-sent events instead of socket.io

## Original post

[instructables](https://www.instructables.com/Arduinolyzerjs-Turn-your-Arduino-into-a-Logic-Anal/)

Author: [Catoblepas](https://www.instructables.com/member/Catoblepas/)
