Lavable
=======

Taking vanilla minecraft lava generation to the next level

In Vanilla, all you need is a cauldron, a piece of dripstone and a bucket of lava (and a couple building blocks) and you
get a fairly reliable - albeit a VERY slow - infinite lava generator.

In Vanilla dripstone uses a random tick and every 5.859375% of the time it will fill the cauldron underneath it with a
full bucket of lava.

The basic idea
==============
- block crafted from 1 bucket of lava above 1 dripstone above one cauldron 
- you have a 5% chance of a random tick "filling" the block with lava (vanilla mechanic)
- you can insert more dripstone to boost the 5% chance to a max of .. say 20%?
- and you can insert more cauldrons to increase capacity?

Things to work out
==================
- Do we rather generate 10mb for a random tick, rather then relying on random tick
- Do we make it a multiblock, put two next to each other to give more output, so giving an incentive for multiple next to each other
- Use actual world ticks, random ticks feel too vanilla for a modded block

Definite things
===============
- It's a tank, so you can pipe lava out (maybe pipe lava back in?)
- API, so we can "generate" other fluids (I'm looking at you Pneumaticraft Oil)


