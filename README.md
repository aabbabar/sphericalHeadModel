# Spherical Head Model

A Max/MSP implementation of Brown and Duda's structural model for binaural rendering of a monophonic source. Development has been made to allow for binaural rendering of stereo audio.

All files required to initialise. Open brownduda_mono~.maxhelp for a demonstration.

brownduda_mono~.maxpat : binaurally renders a monophonic source.
brownduda_mono~.maxhelp: associated help file and demonstration.
brownduda_stereo~: development for rendering a stereo source.

Constituent parts of brownduda_mono~:

brownduda_head~: models the effect of the head with a pole-zero filter and allpass group delay.
brownduda_calc: calculations associated with brownduda_head~
brownduda_pinnae~: models the effect of the pinna as dense reflections, which vary with azimuth.
brownduda_torso~: models the effect of the torso, crudely, as a single reflection.
