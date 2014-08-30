BruneClient
===========

####Brunelleschi Unity Client v0.0.10.0
8/28/2014

**Oculus Path Integration**
 * Oculus assets moved into main project
 * 4 Mode character movement and selection finished and added
  1. mouse_walk - body bound to head. look and QE turn both
  2. look_walk - mouse turns head, QE turns body, Tab re-aligns
  3. freeze_point - pointer appears controlled by mouse, body bound to head
  4. look_point - combination of freeze_point and look_walk
 * Oculus Main Menu added
 * Oculus Web Viewing Rooms (3) added
 * Oculus Model Settlement available
  * text-entry settlement selection scene added
 * Oculus Model Individual Districts (all 20) available
  * text-entry settlement selection scene added
 * 3D Settlement Menu navigation
 * Look to highlight/select from raycasts to collider triggers

**Universal UI Upgrades**
 * Framed District Map in most main buildings
 * Look(Oculus) or Mouse-Over(both) to highlight and see name on all buildings
 * Background Music (written for Brune!) added
 * Sound Options menu structure
  * mute/unmute
  * volume 1-10
 * Sound menu triggers with Options button and “O”

**PC Path Character Controller Upgrade**
E-Q turning

**Settlement Modeling**
Building Terrains have been enabled in the model settlement script

**Bug Fixing**
Adjusted ‘through the wall’ benches in Port Authority Office
Hitting ‘H’ while logging in should no longer pull up the Help menu
H for Help and M for Map works throughout PC Path Game Scenes
H for Help and M for Map disabled in non Game Scenes


***


####Brunelleschi Unity Client v0.0.9.0
8/20/2014

**Individual District Representation**
 * Added 20 new individual district scenes
 * Now able to load into first individual district (Fields) from Model Settlement Login
 * New Buttons in Model Settlement Login
 * Settlement Map menu in individual districts takes you to new district scenes
 * Settlement Map menu in full model settlement includes option to switch to individual district loading

**Bug Fixing**
 * Turned next to river in Fields the correct direction
 * Turned Lot 1 in Residential District correct direction
 * Turned Lot 15 in Plaza District correct direction
 * CapsLock now toggles between (no-mouse + mouse-follow) and (mouse + no-mouse-follow)

**Brunelleschi Unity Oculus Inner Courtyard Demo **
 * Oculus test scenes
 * Look at buildings to highlight and see name
 * Look at door for 5 seconds to highlight go through


***


####Brunelleschi Unity Client v0.0.8.0
8/9/2014

**Settlement Map**
 * Unavailable Districts in the Settlement Model are now unavailable for Teleportation
 * Fixed “flicker” problem with M for Settlement Map
 * Returned Mouse-over district highlights
 * Mouse-over district texts now visible in Settlement Map

**UI Improvements**
 * Radial loading image for Settlement Model
 * Splash loading screen for Singleplayer
 * Desk Menu collapses to view Brune.com
 * CapsLock now toggles both cursor visibility and camera-to-mouse binding


***


####Brunelleschi Unity Client v0.0.7.0
8/2/2014

**Settlement Map**
 * Quick access to Settlement Map with S in both maps

**Map Desks**
 * Map Desks unified into 2 shared desk models
 * Maps are now all Render Textures

**Terrain**
 * Normalmap bumping added to terrain textures
 * Grass added to maps


***


###Changelog for Brunelleschi Unity Client v0.0.6
7/28/2014

***Web Views***
 * Changed web views from Awesomium to Coherent UI
 * Web views now work for x86_64
 * Inserted Coherent UI web views into the settlement maps
 * Web views accessible from Desk menus


***Bug Fixes in Model Settlement***
 * Settlement Map teleports
 * Desk accessibility from inside Main Buildings
 * Auction House door to inside
