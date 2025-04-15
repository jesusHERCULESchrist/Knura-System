# The Knura System
![Knura from Gloth](https://i.imgur.com/dDE5fM4.jpeg)

## What is the Knura System?
The Knura system is a brand new planet for the Kerbol system.  Knura is a Super-Neptune, with a radius about half-way between that of Saturn and Neptune.  Aesthetically it is quite different from either real-world counterpart; its apparent surface is a bright
sky-blue, and it banded with white and grey clouds.  It has two white-blue rings - a thin inner ring sheparded by the twin asteroids Hop and Skip, and a wider outer ring sheparded by the first two major moons, Gloth and Chople.  

## Major moons

### Gloth

If Laythe is like a smaller Kerbin, then Gloth is definitely a small Eve.  It possesses a thick, high-pressure atmosphere and an inky green hydrocarbon ocean that spans the entire surface.  Landing is easy, but punching back up through the atmosphere is no small task.  

### Chople

Chople is quite unlike anything in our solar system.  It appears like a great piece of green sea glass, with its surface knapped into high plateaus, ridged moutains and deep, scooped out basins.  Its surface is defined by the Grand Craggle, a spanning network
 of valleys that terminates in a deep, ciruclar crater.  What could have carved such a fluid feature out of this glassy world?

### Basil

Basil is almost like the Muns long-lost big brother.  It has about twice the radius and surface gravity, and other than its nifty blue shade it has a very similar surface, peppered with both large and small craters.  Its most prominant feature is the Mare Lamenta - the
sea of tears - a vast frozen lava-field from the moons more geologically active ancient history.  

### Ollagander

A small, squat, grey moon.  Almost hypnotically boring, if it wasn't for its unique polar icecaps - the only ones to be found in the Knura system.  Perhaps the bombardment that scarred its surface with its 7 distinctive rayed craters blew away its more 
equatorial ice covering.  Alas, we may never know.  

### Lema

The most distance major moon of Knura, Lema is undoubtedly one of the strangest.  Its surface hold evidence of ancient asteroid impacts that left huge, hemisphere-wide craters.  Over time the ejecta has fallen back to the surface to create steep, white peaks of blasted 
ice.  These highlands loom high over the surface-wide purple-grey ocean of ice shards and slush.  

## Minor moons

### Hop and Skip

Hop and Skip are Knuras closes orbiting moons, hiding within its innermost ring system.  They are true twins, both of similar size and composition, and covered is the same slick dusting of eccreted ice.  Their one major distinguishing feature its Hops pronounced 
equatorial bulge.  Owing to their tiny size and closeness to Knura, landing on these moons can prove quite the challange.  

### Run
Runs highly eccentric orbit, which brings it from the outer limbs of the Knura system to the ring-gap sheparded by Gloth, has resulted in it becoming stretched into an oblong, potato-like shape.  Its reddish-brown colour suggests a similar composition to Gloth.  

### Hilli and Sixle

Not much is know about these bodies, other than their distant, eccentric orbit, and fantastically high albedo.  Perhaps you should pay them a visit?  

## What is this readme for?  Who even?

At the time of writing this, this mod is not yet public.  It has FAR too many wrinkles that I want to iron out.  The main reasons im writing this readme now are threefold:-
- It'll serve as a fun point of reference down the line when I actually DO release the mod.
- Its a good way to start jotting down the small amount of environmental lore than the system has - what the moons are made out of, their geological history, etc.
- It lets me write out explicitly the plan-of-attach for what still needs to be done.
Plus, in a sick, twisted way, I just really like using github.  Makes me feel like a real programmer B)

## What still needs to be done

- There is a bug, either in my configs or in Kopernicus, that is causing huge amounts of floating scatters.  Given that the scatters in Kopernicus have collison (and given that i can't disable that for some reason - another bug), this makes landing on planets a bit of a hazardous activity.  That needs to be fixed
- I have added four custom scatters so far, and three of the four work perfectly, but one of them - a sort of ball-shaped rock that you find in Mar Lamenta, consistedly hovers a few metres above the ground.  NO idea why.  It is superfisally related to the previous floating scatters issue, but i think it is something else as i have never seen this specific scatter actually sitting on the ground like it should.  
- I need to work in support for Scatterer.  Gloth is a pain in the ass right now because you cannot visually tell how high its atmosphere is, and adding scatterer support would resolve that.  Also clouds would be nice.
- Another thing that makes Gloth a pain in the ass is that its got a weirdly small sphere of influence relative to its size and gravity.  You can compare it to Lema, which is smaller, but has a vastly larger sphere of influence.  I think this is related to its proximity to Knura, as Hop and Skip also have weirdly tiny spheres of influence.  
- Sixle has these odd, pixellated cliffs.  I think this is probably a result of a crappy heightmap with too many abrupt height changes.
- Hilli and Sixle, and probably also Chople, should have reflective surfaces when you land on them.  Parallax adds this in a really ideal way, but it also exists in the game to a degree - Pol for example has a reasonably reflective surface.  I need to figure out how to replicate that.
- I cannot for the LIFE of me figure out how to place easter egg structures, or "cities" are they are referred to in the config.  This might need another mod to be added to the mix.
- Some of the moons scaledVersions need some work - some of them are just a bit ugly and smoothed out compared to the moons actual surface, but Gloth has the additional issue that its scaledVersion coastline doesn't match its actual coastline in all cases.  This also effects in biome map.
- Speaking of biomes - i need to impliment science messages.  I have ideas for specific places but the though of thinking of something funny for every single unique location is... exhausting.
- There are two gaps in the outer ring, similar to the gaps in the inner right that Hop and Skip sit in.  Naturally i'd like to fill them with two more asteroids.  The last unused pair of names i have is Divot and Dent, which i like a lot, so i'll probably use them unless a divine beam of inspiration hits me.

![Gloths coastal groves](https://i.imgur.com/tFQWh6K.png)