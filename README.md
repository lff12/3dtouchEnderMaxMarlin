# 3dtouchEnderMaxMarlin
Marlin configs for 3d touch from Trianglelabs for Ender Max

I had huge issues with all of the published firmware for the 3b touch BL touch clone from Trianglelabs on my Creality Ender Max, so I created my own.

I've included 2 configs here both for Marlin 2.0.8.1 and include the configuration.h for the stock firmware as I made no other changes other than for the bltouch
The first is the stock Ender Max
The second is for use with a clone of the dual metal extruder with bondtech style gears as used in the CR10 pro - only difference is that esteps for extruder changed to 134.9 (if you accidentally use this the lcd menu lets you change it back)

Both are configured for bilinear, allows for extra offset (because 10mm just isn't enough)
Also retains all babystepping etc. You need to add G29 command to your gcode somewhere to enable levelling.
I set to default of 4 probes (i.e. 16 in total) which is slow so included both configuration.h files in case you want to alter it

Please let me know if you want a version of this firmware with different settings, I might be able to accomodate.
