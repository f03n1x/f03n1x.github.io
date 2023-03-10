---
youtubeId: 429lP0N91YM
---
# Work Experience
* * *
### Lead Programmer at Unlit Games
I worked with Unlit Games on Redemption's Guild, at first I was the only programmer, but as time passed I ended up becoming accustomed to the project and was able to help any new programmers that joined us, along with interviewing people for the job. I helped fix time sensitive bugs for the alpha, beta, early access and full release stages of the game.

This is some of the work I've done, I created the Loot collection and parry system:

{% include youtubePlayer.html id=page.youtubeId %}

It's quite hard to breakdown everything I worked on because I worked on qutie a lot of features, but I will try to keep the list brief:

- #### AI Programming
  - This includes the enemies, and their tactic system, where they can at any point group up with other enemies and surround the player, run to other enemies for help, lure players to ambushes. 
  - General AI sequencing, going from different states, the enemies had 3 basic states, Patrol meant they would walk around in a fixed zone, Caution meant they saw the player just outside their general view range or were alert via a projectile flying close to them, Attack, they know their target and will try to eliminate them.
  - npcs in the tavern, walking basic routes, playing animations
  - escort npcs, that know their start and end point but not their path, at runtime they'll pick pre-defined paths to get to the end goal based on a node system

- #### Gameplay Features
  - General player interactions, class specific features, 

- #### General Programming
  - Feature Manager systems, things like managing how enemies spawn in a map for adventure zones and wave based combat in the Arena. 
  - Sound Manager systems, handling fading music in and out for combat/ambience.
  - Setting up customized editor classes to assist designing the various systems such as skills and enemies
  - Setting up object databases, that help us manage the many individual skills/items/enemies
  - Setting up an object pooling system that splits up into categorizing for various object types

- #### Multiplayer
  - Setting up the player, enemies and all the bits in between for multiplayer. Syncing up skill projectiles, object spawning and handling scene switching while being in a group

- #### Client-Server communication
  - Uploading required data so that players are able to continue their game at a later date, deserializing data so that it sets up the player to play the game

- #### Tool development
  - Setting up a debug command system, so we as the developers are able to test things easier
  - Setting up a server command system, so we're able to address any issues the player has based on their data, give players items/currency/experience
  - Setting up a way to define how an enemy works, from their attack skills, to what chance each attack types are used, to specific events that they can use based on various conditions, all setup in a designer friendly system

- ### Optimization
  - Optimizing multiplayer netcode, this is through the use of passing in the bare bone information needed for objects, i.e. for projectiles passing in force value and start position to let the client handle the rest
  - Optimizing performance, essentially studying the profiler in various circumstances to understand what causes frame spikes and such, and adjusting changes needed

Aside from the above, I've done things like setup enemies (setting up animation controllers, and the individual animation setup), helped with git repository related issues, and have successfully updated the Unity Version that we used on two different occasions.
* * *
### Senior Interactive Developer at FabCom

My role for this job is help develop the FabCom interactive experience, built specifically for use on websites through the use of Unity3D and WebGL. I help fix bugs for multiplayer specific issues, general gameplay aspects, and help with client-server communication.
* * *
### App Developer/IT Intern at TDDA
I worked at TDDA for a year, on their Drug Detection App, the app itself is more a general checklist to help identify if a person is under the influence of drugs or alcohol. The app consisted of checklists, toggling the phone light, and generating a pdf that could be emailed.

The challenging aspects about this job was working on Android and iOS at the same time, switching between to different programming languages and also being the sole developer, where I was in charge of designing, programming, testing and publishing the App.
