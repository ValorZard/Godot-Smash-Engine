# Godot-Smash-Engine
Open Source SSB Engine
This was forked from NyxTheShield's project and updated to the current version of Godot (as of this writing Godot 3.2)

Things that work:
Dashing
Crouching
Landing *Jump
Double Jump
Directional Air Dodge
Ledges
Stage Collision and Platforms

Advances Techniques

Melee Wavedash
Melee Perfect Wavedash
Perfect Ledge Dash
RoA Platform Drops (Drop while Running)
RoA Wavedash (Air Dodge on Jump Squat)
Pivot Ledgedrop

Things still left to do:
Make attacks do damage
  - add knockback
  - add hitstun
  - add armor
  - add i-frames
Reorganize state stuff so that its not just a bunch of constants, while still making the state machine easily modable and generic.
  - current plan is to maybe put all of the states into a giant dictionary, or just use a mutable enum. /shrug
Add Rollback (Godot GGPO)
  - I want to use this repo https://github.com/FlutterTal/godot_ggpo
  - That project is still being worked on, but if we can get that working in Godot, I'd like to port this project into GGPO
  
