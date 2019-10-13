# ChunkyOrbitsQuest
Chunky Orbits gravity sim for the Oculus Quest

Chunky Orbits is a simulation of free-floating objects in space based on real life physics. Each object in the scene attracts each of the others in a cosmic tug-of-war that we call Gravity. Tap out a few boulders and contemplate the wonders of the Universe. 

Fill your Universe with a collection of cosmic chunks: boulders, white dwarfs, comets, and chunky fireballs. Add some trails to your rocks to trace their paths. Or bust out the sparkly photon cannon - a delete button with a kick! It's a big physics based playground. Create a random cluster of boulders and watch as they collect into larger, chunky groups. Launch a super-massive White Dwarf and observe how it affects the other bodies in the system. Create a small 'solar system' and see how many chunks you can get into orbit. 

Get up-close and personal with Gravity.
 
Created by Don Whitaker
BrainBlinks.com

Changelog:

v0.92 | October 13th, 2019

Small update to fix most of the know issues with the initial release. I would of done all these before release if I thought 350 people would download it in the first 2 days. 

* 'Reboot' orbits should now behave as intended. 
* Fixed angle or the 'ergonomic' front-pointing line for movement
* adjusted menu angles 
* Music player is working again. If you don't like a dong, you can toggle the music off/on to play another random track

v.9 | October 10th, 2019
  * Inital port from PC version of the sim
  * Converted from SteamVR to Oculus SDK
  * Converted from Unity 5.6 to Unity 2019.1
  
PC version changelog:
  June 23rd - v1.11

Fixed a bug where the player would move in the wrong direction after rotating using the right stick. 
April 26th - v1.1

New movement option.You can now move around the sim with controls that are similar to classic first person controls. Use the left touchpad/stick to move and the right touchpad/stick to rotate. You can also point with your left hand to modify your direction or go backwards by pulling back on the left touchpad/stick. The old 'accordian' style movement is still available for those who like it.
Change your scale by pressing in on the right touchpad/stick and then pushing it forward or back.
Gamepad users now need to press the Start button on the menu menu instead of the A button.
Some small changes to the way the main menu detects input and decides whether to launch the gamepad or tracked controller version of the sim.
Updated to Unity engine v 5.6
Updated to SteamVR plugin v 1.2.1
December 20th - Release v1.0

Photon torpedo now lasts a bit longer and travels a bit farther
December 16th - Beta7

You can now create, delete, and grab chunks with both hands. 
Option to turn the background music on and off
Option to turn the help text on/off
Added a particle stars effect to the area around the player. Gives a little more sense of depth and motion.
Tweaked the calculations of the gravity sim. It's now even more similar to RL physics. I've stil taken a few liberties for the sake of fun and easy interaction, though.
December 9th - Beta6

Support for Oculus touch models. If you're using Touch you should now see a proper representation of the controllers. Vive users should see their Vive wands.
Refined the help text. Easier to read, more specific info, and proper positons for Touch/Vive. Please let me know if any of these help text objects seem out of position.
White Dwarf now behaves like the other chunks - hold trigger to create, release to set it free.
Center Stone no longer locks in place. It does have some 'drag' added to the physics sim to keep it from moving freely. White Dwarf has this drag as well. I think it's nice to be able to set up some orbits with these (mostly) stationary objects.
New 'cursor' object visible when selecting menu items. Easier to tell exactly where to 'poke' to select items.
Absorber chunks are now take on a random color when created.
I got rid of the transparent 'currently selected tool' icons. They were reduntant since the same info is on the help text screens. They also cluttered up the view.
December 2nd - Beta5b

Added haptic feedback to tracked controller version. SteamVR added Oculus touch support for haptic feedback yesterday, so I went ahead and put it in the sim. You should feel little rumbles whenever you choose a menu item or create/delete a chunk.
December 1st - Beta5a

Fixed a couple of the 'currently selected' icons that weren't displaying correctly.
Re-enabled single-pass stereo rendering and disabled GPU instancing. They don't seem to be working together in Unity 5.5 and performance was better with stereo rendering on.
Switched to Linear color space.
November 30th - Beta5

New chunk: Comet. A small rock with a sparkly trail. Also added Comets to the Chaos reboot mode.
You'll see a transparent icon above your right hand to remind you what tool is currently active.
Fixed a problem with the menu icons triggering other menu icons when they overlap.
A few adjustments to the Chaos mode. More variation in each random reboot. 
Update to Unity 5.5. Should provide some improvement in physics performance. I did notice some trouble with single-pass rendering, so that is turned off for now. Not a big deal for Chunky Orbits since the scene geometry is fairly simple.
November 22nd - Beta4a

New reboot option: Chaos 
New objects on Reboot are placed in front of the player instead of in the center of the playspace. Look down if you want the new chunks to spawn below you, look up if you want them above.
Particle effect when a White Dwarf consumes a chunk
Move the pinch and pull direction indicator back to the centerpoint between your hands. Fixed jittery motion of the indicator, too.
November 18th - Beta4

Molten Chunk. A destructive projectile with fancy-schmancy particles. 
Asteroid Belt. New option for rebooting your universe that spawns 150 small Absorbers that orbit a center stone.
The mini solar system Reboot now creates random orbits for the 3 planetoids plus a sparkly comet with eliptical orbit. 
Adjusted the menu positions so they are less likely to interect your other hand when activating.
Menus now disappear when you move away from them or span a new chunk.
Fixed a case where chunks would get stranded in space and not included in the gravity calculations.
November 3rd - Beta3

New Menu system. Press the Menu button on either Vive wand to open and close a menu of 3D icons. Poke at them with your controller to select 'em. Left hand brings up the ReBoot universe menu, right hand brings up the list of Chunks that you can add to your Universe. Rift+Touch users can use the A and X buttons. 
Fixed a problem with the Center Stones not absorbing chunks.
October 26th - Beta2a

Improved performance. I optimized the main game loop that caclulates the gravitational forces. It's now twice as fast and more consistant across all rendered frames. Should provide a smoother experience and allow you to add more rocks to the scene before performace decreases. On my system I can get nearly 300 chunks going before I start to see frame drops. 
Fixed the texture on the Vive wand on the title screen. Wrong button was highlighted. 
New Universe starts with 100 rocks instead of 42. Soon you'll be able to choose what to spawn when you reboot your Universe.
October 17th - Beta 2

You can now create Rocks with Trails that help you track their motion through space.
The new Absorber chunk will consume any smaller rock it touches.
New Atrract and Repel tool will pull or push rocks toward your hand.
You can now grab existing rocks. Just get close to a rock and point to highlight it, then press the right Grip button to grab it. Release the button to set the rock free.
You can also delete rocks. Any time you're holding a chunk, just press down on the touchpad to delete it.
Players can change their scale - from a normal human size to a 100 meter giant.
Removed the boundaries from the tracked controller version.
October 10th - Early Access Beta 1

Initial support for tracked controllers with 4 items that you can add to the sim - rocks, white dwarf, center stone, and photon torpedo
Pinch and Pull movement system 
Simple 'reset' button
new loading screen for player to choose between gamepad and hands
Vive wand models in-game
simple text-based help system that describes each button and option
Fixed a problem with the Gravity sim that was causing incorrect behaviour. I'd messed up my calculations during a intense bout of optimization. o.O
September 30th, 2016: Steam Release

Changed name from Gravitas to Chunky Orbits
Released on Steam. Itch customers now receive Steam key as well.
Raised minimum purchase price from $0 to $1.99
August 31st, 2016: v0.92

Added support for HTC Vive (via OpenVR). If you try this on your Vive, please let me know how it works for you. I'm still kind of flying blind with Vive support - don't have one yet. []-)
August 24th, 2016: v0.91

Updated to Oculus SDK 1.6
Performance improvements with Unity's new Single Pass Stereo Rendering
Thrust is now on Triggers
Can now Roll the ship with shoulder buttons
April 20th, 2016: v0.9

Updated SDK for shiny new Rifts (runtime 1.3)
Added some windows to the ship.
September 8th, 2015: V 0.7 Initial release for Rift

A quick and dirty conversion from a Gear VR app, still a few references to the ear VR controls in the audio. I'll re-record that eventually. :)
This version was built using the integrated Rift support in Unity 5.1.2f1 - so I believe it is actually using Oculus SDK 0.6.0.2.
  
  
