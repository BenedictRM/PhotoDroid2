# PhotoDroid2
A reworking of what we had before, but now the camera turns on

You need to have openvcv linked in Eclipse as a library project
Same with appcompat_7

Make sure you dl opencv manager from the android marketplace onto your mobile device

I copied over the layouts will made, the main activity now just turns on the camera.  I think this will give us a solid place to start.  The opencv package
comes with an image manipulator thing too so we could probably copy a lot of that.  This current version was based heavily on one tutorial thatcame with the
opencv package. 

We should try our best to keep the target sdk = 19 -- beyond 19 we have to figure out this whole Intent thing and might have to change opencv source code to 
get it to work so lets just avoid that.  