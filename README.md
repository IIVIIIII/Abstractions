# IIVIIIII Abstractions
A library of custom Max abstractions. Be aware that some of these abstractions are dependant on others within this repo. It is recommended that all abstractions are downloaded together to insure that they all work.

### [edgeBang~]
Output bang message when a received signal value goes from non-zero to zero.

### [pan]
Pan audio between left and right outlets. Use third inlet to set pan level with 0 being hard left, and 100 being hard right.

### [phaseVocode]
Phase vocoder by Cycling74 that has been modified to have a stereo output and higher resolution.

### [pitchShift]
Basically just Cycling74's help file for the pitchshift object in an abstraction for convenience's sake.

### [playPitchDestiny]
Generate a start message to be sent to a play~ object that will playback the loaded file at a determined pitch. Maintains set playback duration and adjusts pitch by changing playback destination (note that the calculated destination may exceed the length of the file).

### [playPitchDuration]
Generate a start message to be sent to a play~ object that will playback the loaded file at a determined pitch. Maintains set playback destination and adjusts pitch by changing playback duration.

### [randEnv]
Generate a pseudo random envelope with the general contour of an ADSR envelope.

### [randRange]
Retrieve random integer value within the range set by the left inlet as the minimum and the right inlet as the maximum. Min and max values can be negative but must be integers and are included as possible outcomes.

### [relativeFile]
Retrieve absolute pathway to a desired file by supplying its location relative to the current patch.

### [spaceBang]
Output bang message from this object whenever the space bar is pressed. Can be toggled on/off from first inlet.













### [HINHpoly]
Patch for a poly~ object used to playback an audiofile from a random point with separate indeterminate envelopes applied to left and right channels. Pitch can be adjusted too making it kinda like a sampler with wacky amplitude modulation.

