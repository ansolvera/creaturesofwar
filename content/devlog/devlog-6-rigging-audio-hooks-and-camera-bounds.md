---
title: "Devlog #6 Rigging Audio Hooks and Camera Bounds"
date: 2022-04-01T18:06:51.505Z
featured: "false"
---
Hello everyone,

I am very excited to discuss the current state of Creatures of War. In the last month we have been working very hard to rig the camera and audio systems. One of the joint goals I shared with my sound effects developer was to achieve realistic audio effects throughout ones playthrough. Ironically, we are able to achieve this affect while tackling our camera bounds system. The remainder of this blog post will be going through these two systems and the upside they offer to the player experience over traditional systems. 

The audio effects we are rigging are based upon realistic audio events that occur in our everyday world. For example, if you fire a weapon outside, the sound of the weapon disperses into the air and albeit the sound is loud, the sound has little echo and disperses rather quickly. If you fired that same weapon in a small room in a house, the sound would bounce off of the walls many times producing large amounts of echo. In our game engine we are creating artificial overlays on top of each of the areas the player will be visiting. This means that we will be overlaying large outdoor areas as well as the smallest crawlspace the player can squeeze through. The effect will be created by adding in custom amounts of reverb to all sound effects that occur based upon the size of the location you are in. This will give the sound effects a 3D quality to them even though these events are taking place in a 2D universe. 

An added benefit of creating artificial overlays on top of each area is that the camera systems can hook into these bounding areas we have created. One of the primary benefits is that the camera will follow the player until the camera reaches the end of a bounding area. The player will then have to venture into the next area for the camera to move again. This is great for creating suspenseful areas where ambushes can be set up as the player will not know what is behind the next door. Insert audio events that will allow the player to listen to the idle sound effects of a velociraptor waiting to pounce on unsuspecting prey here. 

These systems are currently being created and still need to be stress tested to make sure they work fluidly. I am very excited to get these systems working perfectly across the entire alpha level. Looking to the near future we need to rig environmental triggers so we can fire the ambushes I referred to earlier in this post. The Alpha will be nearly complete once we have the audio hooked in, the camera responding intelligently to player actions, and we have events firing correctly. 

If you are interested in ALPHA testing Creatures of War, please send an email to [](mailto:CREATURESOFWAR@GMAIL.COM)tim@creaturesofwar.com

Until next time,

Tim @ Chaos Entertainment