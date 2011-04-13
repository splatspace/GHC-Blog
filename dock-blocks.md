<!--
post#: 3.a
summary: discussion of the numeric blocks project
-->

Hey there! This kicks off a three part series describing our projects in a bit more detail. First up, the number blocks project I described in our [first post][intro], which Jeff Crews has named the Dock Blocks.

<img src="http://farm6.static.flickr.com/5142/5614622981_d3b0911eb5_z.jpg" />

# The idea

The whole idea behind the dock blocks is extensibility. They're goal is to provide a physical prop for all sorts of math activities (and any other activities an enterprising teacher can think of to use them for). The current focus has just a numeric display and lets the various blocks communicate by "docking" to each other, or to a master "station" blog (which holds the more expensive programmable bits). The reason for this is so that it's easy for a teacher to buy or create more of the little bits--which students actually use--without risking the costs of a broken computer or more expensive heavy duty microcontroller.

We want this to be extensible. Ideally it should be easily programmable "in the field" so a teacher can put in any idea they have, or can pull down new software to use with it from a website.

# The prototype

Crews has fabricated the basic physical components from materials he's found at local craft shops and hardware stores, which should make it easy for a teacher to source the same component whereever they are.

The block is a hollowed out wooden block; Jeff bought several for a few dollars at the craft store, and hollowed them out with a drill and dremel. Standard snaps (also from the craft store) will be mounted on the side, and connected through the cube by a generic stove screw from the hardware store. These snaps are conductive, and carry a ground and signal line from block to block as they're connected.

Inside them, we're looking at using an [MSP430][msp430] to control the logic, all communicating via the signal line.

As described, there will also be a central "master" block. Crews is advocating a rocketship, and I don't think anyone wants to disappoint him.

Check back soon, for more info on the dock blocks, and the next two parts in this series describing our other projects!

[intro]: http://www.element14.com/community/groups/splatspace/blog/2011/04/08/introductions 
[msp430]: http://processors.wiki.ti.com/index.php/MSP430_LaunchPad_(MSP-EXP430G2)?DCMP=launchpad&HQS=Other+OT+launchpadwiki
