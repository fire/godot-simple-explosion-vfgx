# Notice
This repository is a fork of GodotSimpleExpolsionVFX by drcd1 (https://github.com/drcd1/GodotSimpleExplosionVFX).
Original repository works with godot 3.2 but not with godot 4.2. This repository inlcudes the same VFX that works in 4.2

This is a simple version transition that aims only for VFX to work and nothing more. I won't be supporting this repo by any means :)

# Godot Explosion VFX

A very simple way to setup realistic explosions in the Godot game engine that react to lighting.

<img width="75%" alt="Explosion Gif 1" src="demo.gif">
<img width="75%" alt=""Explosion Gif 2" src="demo2.gif">

## Dependencies
- Godot 4.2
  
## How to use
(Parameter names are different, please use try and error approach. Parameters might not affect as expected.)
- Edit properties of the explosion by editing "ExplosionMaterial.tres".
- Emission Fallof Multiplier and Emission Falloff control how fast the flames disappear. (Emission Fallof Multiplier can result in visual problems, I keep it at 0.5) 
- Emission Color Ramp allows to modify the color of the flames.
- Smoke Color Ramp allows to modify the color of the smoke.
