# tracking-crabs
Automating the detection and tracking of multiple crabs in webcam video

A phD project by Cesar Herrera.

## Description

  Has webcam video of many crabs moving around shoreline and needs to identify their movement patterns over time and in the presence of different variables e.g. competing crab species.
  
  Has tried many options and currently stuck getting ICY and Blender to work with his particular in-situ data especially lack of ability to programmatically identify a crab from the background (i.e. if you use motion you get the grass and other things, can't currently use color but maybe, perhaps shape but often obscured by environment?)

## Current Ideas and blockers

* Tracking using ICY
  - Have to manually identify the crab since currently cannot find algorithmic way to identify crab
  - Imagery lacks contrast between crab and background that usually exists in lab setting tracking software
  
* Tracking using Blender
  - Have to manually select the object to track

* OpenCV
  - Differentiating between crabs movement and other flora movement e.g. grass et al.
  
  
## Untried potential resources

* http://ctrax.sourceforge.net/index.html
  * Looked at by researcher; potentially required contrast in imagery between object and background? But documentation mentions using diff between mean background image and movement images to identify objects of interest. (http://ctrax.sourceforge.net/ctrax.html#usage)
  
 * http://derek.simkowiak.net/motion-tracking-with-python/
    * A simpler approach but perhaps possible to then remove objects that display no change in location over longer time periods as Fauna.
  
 * http://personal.ee.surrey.ac.uk/Personal/Z.Kalal/tld.html 
    * Pie in the sky option.

