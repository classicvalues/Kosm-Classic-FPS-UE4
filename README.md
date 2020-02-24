# Kosm: Classic FPS Pack For Unreal Engine 4
> Classic Arena First-Person-Shooter Mechanics.<br><br>A powerful tool with fully customizable Blueprints to tune your project up - this Pack includes 2 Character Blueprints defined as VQ3 (imagine Visor from Quake) and CPMA (Full Air Control Support), an AI Bot and Ragdoll, 6 Projectiles (Rocket Launcher, Nailgun, Lightning Gun, Shutgun, Portal Gun and Railgun), 2 Maps for you to make all your testing, plus an Health/Armor System and much more.<br><br>
This Pack is composed by a <strong>.uproject file</strong> which you can freely customize using Unreal Engine 4.<br><br>

<img src="https://kosm.vtxfactory.org/imgs/loading.gif" />

**Website @** <a href="https://kosm.vtxfactory.org">Kosm</a><br>
**Current Development Build:** v0.4 <a href="#pack-patch_notes">(view Changelog)</a><br>
**Unreal Engine Compatibility Version:** v4.24<br>
**Network Replicated:** Coming soon.<br>
**Input Compatibility:** Keyboard/Mouse, Gamepad Controller and VR Set Compatible.<br>
**Supported Operating System:** Windows 32/64-bit, Linux and Oculus-Rift ready.<br>
- <a href="https://www.youtube.com/watch?v=fKr9Qey_Jk8">Watch Teaser</a><br>
- <a href="#download-demo">Download Demo</a><br>
- <a href="https://vtxfactory.org/dl/Kosm_Documentation.zip">Manual Guide and Documentation</a><br><br>

<img src="https://kosm.vtxfactory.org/cb/assets/screenshots/02.jpg" /><br><br>
- <a href="#kosm-pack">Kosm-PACK</a><br>
<a href="#pack-includes">Includes</a><br>
<a href="#pack-patch_notes">Patch Notes</a><br>
<a href="#pack-known_issues">Known Issues</a><br>
<a href="#pack-installation">Installation</a><br>
<a href="#pack-buy">Buy</a><br>
- <a href="#unreal-engine-4-qol-improvements">Unreal Engine 4 QoL Improvements</a><br>
- <a href="#contributing">Contributing</a><br>
- <a href="#contact">Contact</a><br>
- <a href="#licensing">Licensing</a><br><br><br>
# Download Demo
You can test our PACK functionalities with our DEMO showcase below, on Testing_Grounds Map.<br><br>
Check our <a href="https://github.com/vtx-factory/Kosm-Classic-FPS-Pack-UE4/releases">Releases</a> section to download the binaries for your platform.<br><br><br>
# Kosm-PACK
<img src="https://kosm.vtxfactory.org/imgs/includes_2.jpg" />

## PACK Includes:
**&#9632; 2 CHARACTERS** with distinct movement:
- **VQ3 movement Character** <a href="https://kosm.vtxfactory.org/vid/vq3-mov.mp4">(preview)</a><br>Longer the Bunny-hop, faster the travel.<br>
- **CPMA movement Character** <a href="https://kosm.vtxfactory.org/vid/cpma-mov.mp4">(preview)</a><br>Full Air Control - forward vector is controlled by the direction of player's crosshair and Character gains Acceleration when swinging mouse.

**&#9632; 6 PROJECTILES:** 
- **Rocket Launcher Projectile**<br>
- **Nailgun Projectile**<br>
- **Lightning Gun Projectile**<br>
- **Shotgun Projectile**<br>
- **Railgun Projectile**<br>
- **Portal Gun Projectile** <i>(Experimental/WIP - Portal Gun is GPU Intensive, please refer to the manual to know how to disable it if not using)</i><br>
<a href="https://kosm.vtxfactory.org/vid/projectiles.mp4">(preview)</a>

**&#9632; AI BOT** with Hearing/Sight Perception System <a href="https://kosm.vtxfactory.org/vid/ai-fight.mp4">(preview)</a>

**&#9632; HEALTH/ARMOR** Pickups & System <a href="https://kosm.vtxfactory.org/vid/pickups.mp4">(preview)</a><br>

**&#9632; 2 MAPS:**
- **Fortress Map** <a href="https://kosm.vtxfactory.org/vid/fortress.mp4">(preview)</a><br>
- **Testing Grounds Map** <a href="https://kosm.vtxfactory.org/vid/testingg.mp4">(preview)</a>

**&#9632; OTHER FEATURES:**
- **JumpPads**
- **Toggle 1st/3rd Person Camera**
- **Cycle Center/Right Weapons**
- **Custom Crosshairs and Speedometer**
- **Footsteps, Misc Sounds and Attenuation Settings**
- **Player's HUD** 
- **Radial/Splash Damage** 
- **Damage Indicators** 
- **Toggle Crouch** 
- **Bunny-hop** 
- **Weapon Zoom**
- **Double Jump** 
- **Dash** 
- **Walk**<br>

## PACK Patch_notes:
Below you'll find all changes and tweaks made from previous to current version of the project:
<details>
  <summary><i><strong>(In Development)</strong></i> v0.5 <strong><i>- ETA: February, 2020.</i></strong> </summary>
  
- Added Network Replication for Online Gameplay.<br>
- Added Shotgun Bullet Sprites to Weapon Muzzle when firing.<br>
- Increased Shotgun spread.<br>
- Increased Perfomance across all platforms.<br>
- Improved VQ3 and CPMA Acceleration detection.<br>
</details>
<details>
  <summary>v0.4 <strong><i>- Release Date: 27-12-2019</i></strong></summary>
  
- Added Portal Gun Projectiles. (In/Out Flow)
- Added Shotgun Projectile. (Namely "Shutgun")
- Added Lightning Gun Projectile.
- Added JumpPads.
- Further upgraded VQ3 Character jump gained Acceleration.
- Aligned Projectile with Crosshair on Weapon Zoom-In.
- Added variable to reduce Zoom-In Mouse Sensitivity.
- Fixed applied Ground Friction on VQ3 Character Tap-Jump.
- Weapon won't change to the already selected one.
- Dash uses only X/Y Axis, now you won't be able to gain Height while using it.
- Speedometer aligned to center when number of digits increase.
- Fixed previous existing delay on the next fired Projectile when firing any weapon and immediately switching to another one at the same time.
- Added Audio Spatialization to Footsteps, Jump and Double Jump, Projectiles, On Hit Explosions and Landing so you can better perceive where the sound is coming from (behind, below, directional left/right, etc)
- Added 1st/3rd Person Camera Toggle.
- Added Deathcam.
- Player will no longer keep firing Projectiles if killed while shooting.
- Fixed Nailgun Splash Damage, now it won't propagate to characters that are really close to each other.
- Added diagonal Dash movement.
- Added Crouch movement Animation on 3rd Person Camera.
- Added smooth Crouch.
- Upgraded Project Compatibility to UE v4.24.
- Added Deathscream and Fatal Fall Damage.
- Bots no longer freeze when killed while in the air.
- Added Lightning Gun kickback impulse.
- Added Zoomout Animation on Deathcam.
- Added Center/Right Weapon Selection.
</details>
<details>
  <summary>v0.3 <strong><i>- Release Date: 12-10-2019</i></strong></summary>
  
- Increased Terminal Z Velocity.
- Corrected "Physics and Collisions" for Player Controlled Characters.
- Added Lifespan to Projectiles so they won't propagate infinitely.
- Added level restart on KillZ trigger.
- Added Auto-Respawn to Player Characters.
- Further tuned VQ3 Character movement.
- Added Damage Indicators.
- Added Sound Attenuation over distance.
- Added Radial/Splash Damage.
- Added AI with Sight and Hear Perception.
- Added Footsteps Audio.
- Added Health/Armor System.
- Added Health and Armor Pickups.
- Added Nailgun and Railgun Projectiles.
- Added Individual HUDs for each Character.
</details>
<details>
  <summary>v0.2 <strong><i>- Release Date: 25-08-2019</i></strong></summary>
  
- Optimized Mouse Acceleration detection for the VQ3 character to work better. (further updates will be coming on next patch)<br>
- Revamped Rocket Launcher Projectile animations and particles.<br>
- Aligned Projectile with Crosshair.<br>
- Fixed a SpawnedDecal error.<br>
- Upgraded Project compatibility to support Unreal Engine v4.23.0 Preview 6.<br>
- Added an extra ragdoll for you to test collision and physics.<br>
- Each character has its own HUD and individual speedometer, which now displays and works correctly when switching Characters.<br>
- Removed jump cooldown node so CPMA character won't stay glued to the ground when jumping on the edge of a slope or when the space between stairs is too narrow.<br>
- Increased map Bound Scale limits to remove artifacts from viewport.<br>
- Checked Use Flat Base for Floor to avoid the situation where characters slowly lower off the side of a ledge. (as their capsule "balances" on the edge)<br>
- Increased trimp multiplier on slopes.<br>
- Added Character and Weapon Switch capability.<br>
- Increased step height so character can step up stairs.<br>
</details>
<details>
  <summary>v0.1 <strong><i>- Release Date: 05-08-2019</i></strong> </summary>
  
- First build deployed.<br>
</details>

## PACK Known_issues:

- [ ] <strong>NETWORK:</strong> Fix Lightning Gun delay issues on Client.
- [ ] Unintended rotation when spawning Ragdoll_Noobot in 3rd Person Camera. (while pressing "N" in 3rd Person Camera)
- [ ] You won't be able to fire projectiles when switching to 3rd Person Camera. (Pressing "N") (to be implemented later on)
- [ ] Portal Gun is still a WIP, there will be bugs - Projectiles won't pass through Portals, only Characters. (to be implemented later on)
- [ ] Tap-Jump to be detected exactly as Pogo jumping is.

## PACK Installation:
Kosm-PACK is composed of a <strong>.uproject file</strong> that you can open on-the-fly using Unreal Engine. A .pdf manual is included for further installation instructions, character selection and blueprint editing.<br>
## PACK Buy:
- <a href="https://unrealengine.com/marketplace/en-US/slug/kosm-classic-fps-pack">Unreal Engine Marketplace</a><br><br><br>
# Unreal Engine 4 QoL Improvements<br>
Here's some tips to improve your experience using Unreal Engine:<br><br>
**&#9632; Show Frame Rate and Memory in Editor**<br>Go into <strong>Edit > Editor Preferences</strong> and type "Show Frame Rate and Memory" in <strong>Search Details</strong>, then check it.<br><br>
**&#9632; t.MaxFPS 300**<br>When playing the active level in editor viewport, it caps your fps to 60. To increase the cap, go to <strong>Edit > Project Settings</strong> and type "Console" in <strong>Search Details</strong> field to bind your <strong>Console key</strong>. Now click <strong>Play</strong> from the <strong>Editor Viewport</strong>, click your binded key and write <i>t.maxfps 300</i> in the newly opened command prompt.)<br><br>
**&#9632; r.VSync 0**<br>With your <strong>Console key</strong> already binded, click <strong>Play</strong> in the <strong>Editor Viewport</strong> and write <i>r.vsync 0</i> to disable Vertical Sync.<br><br>
**&#9632; Uncheck FOV Scaling**<br>Go into <strong>Project Settings</strong> and type "FOV Scaling" in <strong>Search Details</strong>, then uncheck it.<br><br>
**&#9632; Uncheck Mouse Smoothness**<br>Go into <strong>Project Settings</strong> and type "Mouse Smooth" in <strong>Search Details</strong>, then uncheck it.<br><br>
**&#9632; Change Mouse Sensitivity**<br>Go into <strong>Project Settings</strong> and select <strong>Input</strong> from the left column, then scroll down until you see <strong>Turn</strong> and <strong>LookUp</strong> inside <strong>Axis Mappings</strong>, then just change the <strong>Scale</strong> property.<br><br>
**&#9632; Enable Blutilities**<br>Go to <strong>Editor Preferences</strong> and search for Blutility and check the box to enable it. With Blutilities you'll be able to design several new kinds of tools and workflows based on Blueprints that add new capabilities to the Editor like Scripted Actions (e.g. Bulk Actions), Automation and Editor Widgets. <strong>Right-click in Content Browser and select Editor Utilities > Blutility/Editor Widget</strong> to start using them.<br><br><br>
# Contributing
If you'd like to contribute to this project in any way, please feel free to pull a request or contact us directly.<br><br>Feel free to contact support if you have any suggestions or run into any trouble editing the blueprints.<br><br><br>
# Contact
<strong>Website</strong><br>www.vtxfactory.org<br><br>
<strong>Feedback & Information</strong><br>info@vtxfactory.org<br><br>
<strong>Bug Report & Dev Support</strong><br>support@vtxfactory.org<br><br><br>
# Licensing
This project is published under MIT License which allows very broad use for both academic and commercial purposes.

You are very welcome to modify these mechanics and use them for your own commercial use - if doing so, please keep a link to the original repository and refer to <a href="https://vtxfactory.org/dl/Kosm_Documentation.zip">Manual Guide and Documentation</a> for more information.
