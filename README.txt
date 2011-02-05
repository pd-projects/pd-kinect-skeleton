
This is a patch for Pd-extended that receives data from the Kinect
camera skeleton tracking and draws the info to the screen using Gem,
and controls sounds with the hands.  It was created during the NYC
Patching Circle in January 2011.

It was created on Ubuntu/Maverick using Pd-extended 0.42.5.  For
getting the data from the Kinect camera, we used OSCeleton, which
relies on NITE and OpenNI software from PrimeSense:
https://github.com/Sensebloom/OSCeleton

In particular:
NITE-Bin-Linux32-v1.3.0.18.tar.bz2
OpenNI-Bin-Linux32-v1.0.0.25.tar.bz2

Here's the official source:
http://www.openni.org/

For installation instructions, try:
http://www.keyboardmods.com/2010/12/howto-kinect-openninite-skeleton.html

Or video of how the data should look:
http://www.joystiq.com/2010/12/10/primesense-releases-open-source-drivers-middleware-for-kinect/#continued
