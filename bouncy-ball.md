<!--
post#: 3.b
summary: discussion of the bouncy ball project
-->

Hello again! 

This is part two of a three part series, introducing our projects in a bit more detail. If you haven't already, you can read [part one][part1], which introduced the dock blocks. Today, I'm going to introduce an educational aid we're calling the bouncy ball. Suggestions for a more impressive name are welcome!

![prototype of the bouncy ball][proto]

# The idea

The bouncy ball is an aid to understanding basic physical principals. Force, acceleration, inertia, kinetic energy--these aren't the most intuitive concepts, and the earlier you can get a student to grasp them on some level the easier they'll find the harder concepts to come. The bouncy ball aims to make these concepts more concrete, by tying these physical laws to visual display and tactile games with a ball. With an acceleromter connected to LEDs or other visual stimuli, games centered around tossing or dropping the ball can illustrate the strength of an impact, the acceleration the ball experiences in flight, or a variety of other concepts.

# The prototype

Our fabricator, Jeff Crews, has whipped up a prototype for this out of the most unassuming of objects--a dog toy he got for a few bucks from a big box store. The holes in the exterior are filled in with clear epoxy with LEDs mounted inside, which connect to an Arduino inside the ball. The accelerometer--a key piece of this assembly--is a [MMA7455L][accelerometer].

The ball is cut along open along one orbital plane to allow the placement of the inner electronics. An O-Ring, placed around a perpendicular orbital groove, holds the halves back together, so that it can continue to bounce. Pleasanty, it's a very simple construction, easy for someone to put together with a little bit of work. As Crews pointed out, if you can't get a ball with conveniently placed holes, you can easily drill or cut out your own.

We're going to experiment with some other ball enclosures, but the basic construction is unlikely to change.

Check back again soon--we'll have part three up describing the last of our projects: the Piano Player.

[part1]: http://www.element14.com/community/groups/splatspace/blog/2011/04/13/the-projects-part-one
[accelerometer]: http://www.freescale.com/files/sensors/doc/data_sheet/MMA7455L.pdf

[proto]: http://farm6.static.flickr.com/5269/5614621995_64126db865_m.jpg
