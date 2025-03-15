I was haveing a hard time Getting my printer to print on the bed. Every time i would start a print it would print above the bed. I found the Cura Start gcode that works Great.
Also if your prob is crashing to your bed when you do a ABL. You probably have the z end stop wire switched.


This Bin file is for a skr mini E3 V3 Bl touch using the z end stop for the prob.

I provided the Congfig Files For Marlin-2.1.2.5

Change this for how many point's you want the Prob to touch for ABL. I have it set to 4.
location - Configuration.h
#define GRID_MAX_POINTS_X 4

You will have to edit your Prob offset's.
Location - Configuration.h
#define NOZZLE_TO_PROBE_OFFSET { 10, 10, 0 }

If you want Prob offset wizaed enabled uncomment this.
Location - Configuration_adv.h
//#define PROBE_OFFSET_WIZARD 
