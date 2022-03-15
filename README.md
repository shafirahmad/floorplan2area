# floorplan2area
Calculate the estimated floor area given an image of a floor plan

This program allows users to upoad a floor plan, do some quick area demarcations, and get the estimated total floor area. It should work with both metric (mm/cm/m) and imperial (feet/inches) measurements. Area given in sqm or sqft. 


## Steps to calculate 
1) upload an image of a floor plan (in png, gif or jpg)
2) apply transformations to the floor plan to get it to fit guidelines (rotate, skew etc)
3) Use a ruler to calibrate x and y scaling
4) Draw/Fill the various layers with colored pixels (eg: external walls, internal walls, outdoor, indoor, carpeted etc)
5) Arrange layers to get final image output
6) Estimate floor area (in metres or in feet/inches)
7) Add rulers/distance measurements to the final plan
8) export the plan

## Features needed (and wish list)
1) Transorm image (potential fisheye corrections?) - or use another program to straighten the image first
2) Layered drawing with overlay (semi-transparent)
3) scaling calculations
4) guidelines (do we need angled guide lines, eg 30deg, 45deg, 60 deg?)
5) calulate no of color pixels based on scale

## Absolute bare minimum features to have (MVP):
1) Upload image (pre-straightened, ie no perspective transform needed)
2) Use ruler to calibrate x and y scaling
3) fill needed area with pixels (rectangular) - single layer
4) calculate no of pixels and multiply by scaling factor to get estimated floor area
5) done!

Suggestions welcome.

Software Licence:
All Rights Reserved
(C) 2021 Shafir Ahmad
