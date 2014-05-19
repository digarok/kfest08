kfest08
=======
A silly demo in Applesoft BASIC.

History
=======
A couple of years ago I was playing around with making image converters using gdlib in PHP and outputting to hex data or straight to Applesoft BASIC statements.  I decided to make a little demo with that, and then I ended up writing a BASIC meta-language interpreter that made it easier to move modules around.  I don't have that parser any more, but this file is the stitched together output that you can execute in Applesoft BASIC.

Running
=======
To run it, put the text file on an Apple disk (or disk image for emulators).
Then boot into BASIC and type "exec demo.txt" to load the program into
the BASIC interpreter.  Then you should be able to "run" the program. 

If you want to skip that step in the future, you can "save" it to disk like
a normal basic program.

Huh? Show me!
=============
If you just want to see what the demo looks like, I did a capture (without sound) which you can see here: https://www.youtube.com/watch?v=qzDl4fjtFMg

Why?
====
While I don't think this is a great example of BASIC programming or anything, it does show some things that others might benefit from.  For instance, this shows you how to control the Double Low Resolution (DLR) mode of the 80-column Apple II computers.  In general, I would like to encourage more people to post their code for older platforms on Open Source code hosting platforms.  It would help us all to see more examples of techniques used and would save a lot of reinventing the wheel for enthusiasts like myself.
