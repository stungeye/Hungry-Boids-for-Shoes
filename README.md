**Hungry Boids v0.6 - A Shoes Application**

**Author** : [Wally Glutton](http://stungeye.com)

**Summary** : A hungry swarm indeed! A flocking simulation à la [Boids](http://www.vergenet.net/~conrad/boids/pseudocode.html).

**Notes** : My home-rolled Vector class appears to be quicker than the matrix library Vectors.

**Required** : You must have Shoes installed to view the boids.

**Get Shoes** : [http://github.com/shoes/shoes#readme](http://github.com/shoes/shoes#readme)

**Learn Shoes** : [http://cloud.github.com/downloads/shoes/shoes/nks.pdf](http://cloud.github.com/downloads/shoes/shoes/nks.pdf)

**Original Processing Sketch** : [@ Open Processing](http://openprocessing.org/visuals/?visualID=7493)

**Lua Port** : [http://github.com/iamwilhelm/frock](http://github.com/iamwilhelm/frock)

**License** : This is free and unencumbered software released into the public domain.


**Change Log** :    

v0.1 - The initial swarm.

v0.2 - Replaced custom random method with (min..max).rand
- Mouse clicks add food. Careful not to add too much.

v0.3 - Seems Shoes 0.r646 can no longer draw a zero radius circle (Magnus Adamsson)

v0.4 - No longer using a $app global to access Shoes methods within the Food and Boid classes.
- Moved class definitions above Shoes.app block as this was causing a problem for OSX builds.
- Decreased the Stay Visible Damper by 50.
- Fixed some spelling errors.
- Assigned explicit app title, height & width.

v0.5 - In Shoes Raisins an oval :radius now acutally defines its radius, and not the diameter like in early versions of Shoes.
- Changed all references to RADIUS to DIAMETER and draw oval using :width.

v0.6 - Changed license from CC Attribution to Public Domain.
