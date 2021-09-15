# impactParticleSystemInUnity
 guide (prefab maybe one day)

0. Make a particle system.

1. Duration : 0.05

2. Start Size : 0.2 (light burst) || 0.6 (fat burst).

3. Start lifetime : 0.3 (speed++) || 0.5 (speed+).

4. Start speed : random between two constants : 5 - 30

5. Set color you want.

6. Turn off looping.

7. Play on awake : disable.
---------
if you want that the particle system doesn't herit parent's transform things like rotation :
8. Simulation Space : world
---------

*/ EMISSION TAB /*
9. Bursts : new element (click "+").

10. Count : 60 (for more particles).

*/ SHAPE TAB /* 
11. Shape : Sphere.

*/ RENDERER TAB /* 
12. Render mod : Stretched Billboard.

13. Material : Sprites-Default.

If you want a fade-out-look for the end of your effect:
/ Add Alpha key making it going from normal value to 0.

--------------------------------------
BONUS :
It can make a very different particle system if you set in Trail Material the "Default-Line".
Can make an other particle system and gain time.

