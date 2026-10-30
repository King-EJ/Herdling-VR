# Herdling-VR
VR Mod for Herdling

<img width="683" height="1024" alt="Herdling vr" src="https://github.com/user-attachments/assets/eaa9349a-68b4-4bba-af0e-da5c767096aa" />


HERDLING VR  -  VR mod (Unity 6000.2, IL2CPP x64, URP, BepInEx 6)
==================================================================
Version 0.2.4 (test build)

INSTALL
  
  1.unzip to game folder, only tested with virtual desktop XR,
    to disable Mod rename winhttp.dll to winhttp.dll.bak.
  2. Start your OpenXR runtime first (Virtual Desktop / SteamVR / Quest Link), then the game.


CONTROLS (the VR controllers are an Xbox GAMEPAD for the game - the game's own pad controls and prompts)
  X + Y together ........ START (pause menu)
  
  Left stick click (L3) . switch FIRST / THIRD PERSON
  
  Left grip + Y ......... VR SETTINGS MENU (stick up/down choose, left/right change, A toggle, B close;
                          saved straight away; no game buttons are sent while it is open)
                          
  Left grip + X ......... re-centre the view
  
 
  
  Every button can be changed in the config ([Controls.Pad]: Action1..4, LeftBumper, RightBumper, LeftTrigger,
  RightTrigger, LeftStickButton, RightStickButton, Start, Menu, Back, DPadUp...). Setting LeftStickClick to a
  button makes L3 that button (then switch the view in the settings menu).

VIEW
  * Third person (default, GameCamera): you are where the game camera is; your view turns with it.
    ThirdPersonStyle = Follow: you follow behind the player at a fixed height, the right stick turns you.
  * First person: you are the player's eyes (the head is hidden), the right stick turns you.
  * Menus / pause: the game's picture on a screen in front of you. In play the HUD floats in front of you (its
    black parts see-through). Cut-scenes: you see from the game camera.

ARMS ON THE CONTROLLERS
  * The player's arms follow your controllers - in first person exactly where your hands are, in third person
    copied onto the player as if you were standing where the player is (ArmsInThirdPerson).
  * First person: FirstPersonBody = HandsOnly shows just the hands (and the staff).
  * HandOffset / HandRotation in the config move / turn the hands on the controllers. ArmsMode = Game turns it off.


