# particletest-pixi
An example of the Pixi ParticleTest demo with basic time travel

**pixiparticletest.html** is the basic Pixi ParticleTest demo

**pixiparticletest2.html** separates the the dude and sprite structures, the dude structure is updated each tick, and a view() function applies the changes in the dude structure to the sprites

**pixiparticletest3.html** moves the update of the dude structure into the view() function - the information can be calculated parametrically based upon a seed and a time value. For time travelling we store the seed and the t each update, and we can recreate the historical state from these two values.
