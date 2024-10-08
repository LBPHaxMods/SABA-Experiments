# 3rd Person Camera Mod
This is a blueprint that allows you to use either the mouse or gamepad (right-stick) to move around the camera. Note that this requires no camera areas, and replaces the Single Screen Camera blueprint.
## Known Issues
* Any sound events using the animnotifier AnimNotify_PostAkEvent will come from 0,0,0. This is because for an unknown reason, the game does not use the 3rd person camera as the listener **(if you know how to fix this, please tell me!)**
* The game will not kill you if you go off-screen. (will likely not fix)
* Does not work with multiplayer (waiting for mods to work with multiplayer before fixing)
