---
title: "Devlog #7 Smelting the Alpha level into a playable demo. "
date: 2022-05-05T17:38:21.848Z
featured: "false"
---
Creatures Of War fans, 

Over the last four weeks the team has been hard at work attempting to get the trailer and alpha closer to the finish line. For the trailer we need to create all of the art assets that will be showcased. For the Alpha we need to rig a couple of features that are lingering. We also need to perfect a few remaining bugs on existing systems. This has been quite the task as one of the new features that is being rigged is an "Item_Drop_System". This system focuses on analyzing the players inventory and deciding on what regents, ammunitions, or treasures to drop for the player based upon a number of gameplay factors. 

Think about playing a game where you killed a ton of enemies, but you also used up all of your bullets. If the game did not read the inventory of the player, every enemy death would have an equivalent chance to drop either health, bullets, or treasure to the player and the odds would never tip in any direction. If the algorithm never adjusted and a player ran out of ammunition, they would have the possibility of running out of ammo, and then possibly not being able to beat the game. It is for this exact reason that we need an algorithm to run over the inventory periodically to determine the needs of the player. If a veteran of the game is always stocked on bullets and regents, then more treasure would drop as the algorithm would lean that way. This in turn would then reward strong gameplay mechanics by increasing their in-game money which is then used to upgrade their weapons.

Another fun feature that we have been working on is getting the player to traverse the level fluidly via the use of ladders, ropes, elevators, and ziplines. These systems are currently in working order, but they are a bit crude when it comes to varying velocities. For example: The player can enter the rope midair by walking, jumping, and catching the rope midair. The transition into grabbing the rope midair will be a slow transition because the x velocity was determined by the player walking. On the other end of the spectrum, we have the player enter the rope midair by running, jumping, and catching the rope midair. The transition into grabbing the rope midair will be a fast transition because the x velocity was determined by the player running. While we have two distinct scenarios here, at least we do not have variable velocities like some games if running up hill! That means that if we have trouble coding an algorithm that determines animation mixing based upon the players X velocity, it will be ok. We can always hard code in two edge cases. 

Anyways you can see that the programming features can get a bit complicated. The team is working hard to iron out all of these coding bugs as well as get the SFX's, art, and music in their proper places come alpha testing time. If you are interested in testing out the Alpha of Creatures of War, please send an email to Tim@creaturesofwar.com



Until next time, 

Tim @ Chaos Entertainment