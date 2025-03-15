This Bin file is for a skr mini E3 V3 Bl touch using the z end stop for the prob.

I provided the Config files for Congfig Files For Marlin-2.1.2.5

Change this for how many point's you want the Prob to touch for ABL. I have it set to 4.
#define GRID_MAX_POINTS_X 4

You will have to edit your Prob offset's.
#define NOZZLE_TO_PROBE_OFFSET { 10, 10, 0 }
