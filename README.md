Overview
Revenge of the Hamster is a 2D platformer that takes reference from many classic games such as Super Mario Bros. and Sonic the Hedgehog.  The game is inspired by some Covid-19-related real-life events in Hong Kong, where the government requested pet owners to surrender their hamsters for killing to stop the viral spread. Through the game, players can control the hamster to fight for its dear life by running through different places in Hong Kong. After completing 4 levels, the hamster will finally gain its freedom.

Scope of Project
Story
The game relates to real-life events from late 2021 that took place in Hong Kong. The government wanted to cull hamsters under the accusation of spreading Covid-19. Our game tells a story of one of those hamsters who embarks on a journey to prevent that from happening. He travels through various places in Hong Kong in order to find the cure.

Feature Scope
Initially, the game was designed as a simple run-and-dodge game. However, after careful planning and consideration of the variety of the actions, we decided to implement some special abilities for the hamster, namely invisibility and shooting. Players need to not only pay attention to the enemies and obstacles on the way, but also actively look for collectibles to get the powers in order to finish the levels. On the other hand, there are three different pickup items for players to recover the health of the hamster. If the hamster runs out of hearts, it will be revived and transported back to the nearest checkpoint.

There are 4 levels developed in the game.. The first level acts as a tutorial that allows players to get familiar with the controls and the mechanisms of the game. The complexity and difficulty of the levels increase as players progress. To assist the storytelling of the game, transition scenes are also implemented between levels.

Character Design
As real-life events are the main source of inspiration,  the main characters of the game were already determined when we came up with the story, such as the hamster and the officials chasing after the hamster. Therefore, the point of emphasis was the art style of the characters. Pixel art is the hallmark of indie games and there are plenty of assets and tools in that area. We outlined the characters we need and solicited the sprites from different sources on the Internet, such as the Unity Asset Store. Some of the sprites were further modified using Adobe Illustrator and Adobe Photoshop. 

Scene Setting
During the game planning stage,  we decided to emphasise the general atmosphere of Hong Kong so that the player can have an immersive experience. We included both the urban and outdoor parts of Hong Kong to add some diversity to the scenes. The arts used in the scenes were mostly acquired from the Unity Assets store; to make them fit our design better, some of them were modified by using tools such as Adobe Illustrator and Adobe Photoshop. 

Coding
The game was developed with C# and Unity. Throughout the project, the Unity Collaborate tool was used for sharing and syncing works between different team members.  The team was split into two functions during the coding stage: one was responsible for developing the game mechanisms and the other was responsible for the level design. 



Game Elements
Main characters

The hamster
A brave hamster who is determined to escape the gruesome end the government has planned for it. It is wandering around Hong Kong to find the cure for the  COVID-19. 

Labman
Workers from the lab of the government. They are trying to hunt down the hamster and finish the job.

Bird
The common bird that you can find in the city. Due to its carnivorous nature, it will hunt the hamster whenever possible. However, as the city has a low level of visibility, the bird can only detect the hamster when it is in a certain range; otherwise, it will hover in the sky and look for possible prey.


Collectibles

Cherries
The favourite food of the hamster. Eating 20 of them will help the hamster recover one heart. The number of cherries collected also serves as the score of the game.

Full health pickup
A health pickup that gives full health to the hamster.

Heart
A health pickup that gives full health to the hamster and extends the health bar by one heart.

Attack Potion
A potion that is scattered around Hong Kong. No one knows how it is made and why it is everywhere. The only thing known is that it will give the hamster the ability to shoot laser bullets. 


Obstacles

Spike
A common trap that is placed almost everywhere on the maps. The hamster has to be careful or else one misstep can cost its life.

Saw
It will kill the hamster instantaneously. It is either stationary or moves within a predefined routine.

Spikehead
This is another trap that gives a quick death to the hamster. More often than not it will move up and down, trying to pin the hamster to the ground. Yet, it can be stationary too.


Miscellaneous

Moving Platform
A life-saving transport that the hamster relies on. It moves to and fro across different gaps in the world.



Evaluation: Four Game Elements
Aesthetics
While preparing this game, our aim is to reflect on Hong Kong's life during the pandemic. For this reason, we tried to introduce people’s lives by adding details such as hiking forests or wandering around the empty LKF.  We wanted to intensify the contrast as the difficulty of the levels increases as the game progresses. For this reason, we have darkened the tilemap colour palette in the harder levels to highlight the main character and enemies. The character animations and animated environment objects are hand-drawn and created by Adobe Photoshop.

Story
Our story begins before the actual gameplay takes place. The player witnesses, in textual form, a scene when the protagonist of our game, a small hamster of brave heart, promises to his caged brethren that he will find a cure and liberate them, and save their furry lives.  As the game progresses, the player travels with the hamster from a fictional laboratory to three different real-life locations in Hong Kong, getting closer to his goal with each level. He starts his journey in the wilderness surrounding Tai Mo Shan, then he proceeds to LKF to question people of questionable morals, and finally, he finds the cure deep under Penny Bay.  

The story is told using transition scenes between levels where the player finds a description of the events happening in the game and how the story progresses. The presented plot also introduces new mechanics - powers the player can use. We used an idea similar to those of X-Men, mutations. By making the virus mutate, we gave justifications to functionalities that aid the hamster during his journey.

The game ends with a plot twist - our hero indeed finds the cure and helps his people. However, he doesn’t cure himself because he enjoys his new powers (and maybe new powers we don’t know about?) and decides to run an underground gang in which he rules indisputably. 

Mechanics
To navigate our video game, players can use “AWSD”. As they progress through each level, they will encounter checkpoints which will save their progress and allow them to respawn in the most recent checkpoint upon death. At the end of a level, they will encounter a flag which will carry them over to the next scene and levels. 

As the player faces enemies and obstacles throughout the levels they will encounter various pickups the player can make use of to aid their quests. There are conventional health pickups, collectible cherries, and power-ups. All of these pickups are carried over from scene to scene. For example, the hamster can keep the extended health bar throughout the levels. From the start of the game, the player can also use invisibility which is toggled by the ‘I’ key, a power that it received from the COVID experimental lab. 

The player will have to face obstacles and enemies throughout the scenes. There are stationary obstacles that will kill the player upon contact and moving obstacles that will kill the player upon contact. The enemies will detect the player object upon entering a predefined radius and chase the player upon detection. The enemies, unlike the obstacles that kill the player instantly, only damage the player and remove one heart from the player’s health upon contact. 

Technology
Our video game was developed with the Unity Game Engine and is thus compatible with Windows and Apple machines. We utilised various aesthetic elements from the Unity Asset Store without which our game would remain functional but lifeless.

Future Plans
Due to the time constraints set on our team for the development of this video game, we did not have the chance to explore other aspects of the game that we initially had planned earlier. In the future, we could further enhance the gaming experience by addressing these initial plans and additionally implementing new features that could provide even more polish.


Our most substantial plan that could not be accomplished was the implementation of a boss fight at the end of the video game. This was initially intended to be a hand-crafted sequence of events where the player would progressively enter stages of varying attack patterns while the boss’ health was being depleted. Establishing a kind of boss fight like this in the future would appropriately conclude the story of our videogame.

In addition to our initial plans that could not be accomplished, we also wish to update our aesthetics. Many of the pixelated art is not consistent aesthetically and this could certainly be improved on to give the game a consistent art style throughout the various levels. We should do so bearing in mind that we do not remove the diversity of themes and designs which set the levels distinctly apart from one another in a tone befitting of the overall narrative. 

In the foreseeable future, our team could consider implementing higher quality and unique voice sound effects for the individual characters (ie. hamsters, doctors) and narration intermediary scenes that explain the narrative of the game. 

And finally, our team also wishes to implement friendly and interactable non-playable characters throughout the game. These characters could be vendors, providers of quests, or just characters the player can talk to and learn more about the lore of the world they are inhabiting.

All of these changes above, excluding the boss fight, although minor, add so much depth to the overall tone and attention to the detail of the video game. We believe these small details will be appreciated by players and express the passion for the small world that has been created by the team. 

Conclusion
Revenge of the Hamsters 2D platformer game project was created over the course of 3 months. The final game contains the development's fundamental features and scope.  The game, which reflects the pandemic period in a tragicomic way, is designed to be enjoyable and playable for everyone.
