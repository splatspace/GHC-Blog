<!--
post#: 3.c
summary: discussion of the piano pen/player idea
-->

Okay folks, this is the last in this (very short) series: the Piano Player.

The piano player is a musical microcontroller on wheels. As described in our [first post][intro], it's a tool to introduce musical composition and music playing at an earlier age, in a cheap and easy manner.

The "interface" is literally a board of metal, on which a student can place magnetic panels to indicate notes. The advantage to this interface is that it is *incredibly* cheap. When Peter began prototyping it, he was able to stamp out a number of boards for a few dollars. This is a serious advantage for musical education, as one of the costly parts is getting enough instruments for every student.

The player uses a row of light sensors to read the non-reflective magnetic panels, which the microcontroller translates into notes with a direct digital synthesis (dds) sinewave generator. The tempo is governed simply by how fast one moves the player across the composition board.

We have a working prototype of this, though the final step of translating the digital data of reading the magnets into actual music needs more work. While square wave noise is pretty simple, we're still working on proper music.

[intro]: http://www.element14.com/community/groups/splatspace/blog/2011/04/08/introductions 
