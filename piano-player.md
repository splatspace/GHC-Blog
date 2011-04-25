<!--
post#: 3.c
summary: discussion of the piano pen/player idea
-->

Okay folks, this is the last in this (very short) series: the Piano Player.

<img src="http://min.us/jnvQcq.JPG" width="300px" />

# The idea

The piano player is a musical microcontroller on wheels. As described in our [first post][intro], it's primarily a tool to introduce musical composition and music playing at an earlier age, in a cheap and easy manner. Interestingly, from talk with local teachers we've also found that it can be used in a variety of other lesson plans involving pattern matching, spatial reasoning, and linguistic skills like alliteration and rhythm. This isn't that surprising, given the known links between music and other subjects, but it's promising all the same.

One of the reasons we really like this project is that it makes an incredibly cheap musical instrument. The interface to create music is literally a metal board and magnets--the sort of thing you can easily hand out to kids without worrying about any damage as you might with traditional instruments. 

# The prototype

Peter Reintjes created a number of boards as the interface one day by stamping them out of metal and spraying the boards with white paint. The final version will need some softer material around the edges, but will still be easily fabricated in most locations. The magnets are just cutouts of black magnetic tape.

The player is an assembly which rests over the interface board, and contains a series of LEDs and light sensors to read the music. The magnets don't reflect light, which the sensors read as "notes" when the player is slid across the board. An attached arduino translates the read "notes" into the actual musical notes with a direct digital synthesis (dds) sinewave generator. The tempo is governed simply by how fast one moves the player across the composition board.

So there you have it, all three of our projects. Keep checking back here as we continue to document the progress we're making, and to find out what the final project to be submitted for the challenge will be!

[intro]: http://www.element14.com/community/groups/splatspace/blog/2011/04/08/introductions 
