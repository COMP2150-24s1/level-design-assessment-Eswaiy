[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: [Elias Swaiy]
### Student number: [45985847] 

## 1. Player Experience (~700 words)

### 1.1. Discovery
In the first section, the player discovers and learns the primary mechanics of the game including the verbs/actions that the player uses to interact with the game, the objects that are interacted with, and the rules that dictate how the game must be played. Throughout sections two and three, the player discovers more mechanics as well as dynamics that arise as a result of these mechanics

The following screenshot exhibits the encounters in section 1 that enable the player to discover the main game mechanics:
<img width="637" alt="Screenshot 1" src="https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/05bb15ad-57f0-4e0a-873e-a2cfc6fbf568">
-	Space for the player to discover movement/running 
-	Moving platform above hazardous spikes to discover jumping as well as damaging spikes that drain health 
-	Pass through platform that the player can jump up through or fall through 
-	Checkpoints for respawning when player falls into acid 
-	Weapon pickups for player use in combat
-	Enemies for player to discover combat using picked-up weapons
-	Keys required to complete level behind column that is destructible using the staff
  
The game facilitates learning through the design practice of setting the difficulty of the encounters in the first section to be easy in order to introduce the player to these mechanics and skills so that they may begin mastering them for further use in more difficult and dynamic encounters. Moreover, the increase in difficulty throughout the level is gradual in order to allow the player to climb the “hill” of skill and strategy mastery. 



### 1.2. Drama
Dramatic arcs are built through varying levels of intensity throughout the level. The first level starts off quite tame, allowing the player to learn the mechanics of the game. Once the player reaches the second and third sections, the encounters alternate between high intensity through combat situations, and low intensity through moments of rest and healing which gives the player a sense of relief following a tense combat encounter (High -> Low -> High -> Low). Moreover, the end of the third section has a moving platform that moves over quite a long distance to allow the player to reflect on the previous highly intense combat encounter (connective space)

Examples:

![High intensity](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/1321e54d-2d4f-49c5-ad27-41c63dbc3649)

(High intensity: Tension from combat)	

![Low intensity](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/17459ef8-ef0d-4054-810d-31c727f8ebac)

(Low Intensity: relief through rest & healing)

![Connective space](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/40ed106e-2740-4715-8214-4e00612988fb)

(Connective space/moving platform ride: allows for relief & reflection following high intensity encounter

<img width="470" alt="Destructable wall corridor" src="https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/217311e8-0569-4593-856e-1befafc4cd3f">

(The series of destructible walls obstructs the path to the next space and prolongs the reveal of the next encounter, creating tension as the player doesn’t know what to expect; they might encounter enemies, health, a resting space, or even a death trap. This uncertainty arising from blocking the player’s field of view as well as prolonging the reveal creates suspense and tension, and finally relief once they have broken through the walls and find there is no danger on the other side)

Moreover, the encounter below puts the player in a position of power, as they are able to kill the multiple enemies ahead of them simultaneously by activating the falling trap above them:

![Power](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/beb8a250-797b-43c9-97c3-5dd2cfeee7cd)


### 1.3. Challenge
The main challenges in the game are combat against enemies and puzzle solving. The parameters of the enemies were tuned to vary throughout the game in order to modulate the level of difficulty and level of skill required. The parameters tuned were enemy health levels and the number of enemies in any given encounter. Varying these parameters allowed for the difficulty of the game to climb with the player’s increasing skill level without exceeding their capabilities, therefore, preventing boredom and anxiety, hence creating the right conditions for the player to enter the flow state. The challenge of puzzle solving was designed to become more complex as the player progressed through the game to maintain the flow channel.

Combat encounters:

![Health x2](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/fdfb2240-204c-4fb0-8e67-b5785eaecc44)

(Chomper with health set at 2)

![Multiple enemies](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/cde7c79c-e0e8-488d-a982-028daab045c3)

(Multiple enemies in one combat encounter)

Puzzle encounters: 

![Pressure pad door](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/8b150085-338b-4d34-8f42-4074821d69d4)

(Pressure Pad activated trigger door)

![Elaborate puzzle](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/fdc06833-7cfc-4fe4-8a51-817b71df83d9)

(Elaborate puzzle involving pushable box, moving platform, pressure pad, switch, and trigger door)


### 1.4. Exploration
The level design has a non-linear structure in order to encourage exploration; this is achieved through various design choices. Firstly, the player does not have to complete one section to gain access to another, giving them the autonomy to navigate and complete the sections in whichever order they would like. Additionally, the Key-Door to complete the level is accessible to the player from the beginning of the game to provide more context for determining the primary objective of the game (collect the keys and complete the level). Secondly, there are multiple routes in the game that allow the player to go back and explore previously discovered areas for objects and spaces that they may have overlooked. Lastly, triggers (switches & pressure-pads) for puzzle objects (doors, bridges, moving-platforms) are located in separate spaces to encourage the player to explore the level.

![Exploration](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/d130773b-4f4a-4be5-80b6-9cc67a096686)


## 2. Core Gameplay (~400 words)

### 2.1. Moving Platforms & Spikes

![Spikes, Moving platform](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/e5a167ba-d16e-4749-bc8e-2a2f735f6ddd)

The moving platform was introduced in this counter as the player needs a reason to use the moving platform. By having a pit of spikes in the way, the player is forced to use the moving platform to progress any further, therefore, learning the mechanic. Regarding the spikes, this element was introduced along with the moving platform as having an alternative path hovering above the spikes suggests to the player that the spikes may be dangerous and if they miss the platform they will learn that spikes cause damage.

### 2.2. Passthrough Platforms & Health Pickups 

![Health   ptpf](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/1fd917eb-2558-450f-8736-51d89cd789dc)

When the player spots the health pickup, they’ll have to go through the passthrough platform in order to collect it, and in this way, the player learns both mechanics.

### 2.3. Checkpoints, Acid & Weapon Pickup (Staff)

![Acid, Staff, Checkpoint](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/b91bb64a-915a-487a-a398-b0aef9b67a49)

The acid and checkpoint were introduced as these mechanics work together (player falls in acid and respawns at checkpoint). Moreover, the staff pickup ahead of the acid is used to invite the player to move towards the acid and fall in, in order to allow this introductory encounter to occur.

### 2.4. Chompers

![Chompers](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/3caefd14-9cc8-47c9-beb2-8ccfb12d3848)

The Chomper is introduced in a sequence with plentiful space in order to allow the player to learn about its attack range, mobility, and to provide enough space for combat. Fighting the Chomper in a tight space may be difficult upon the first encounter.

### 2.5. Weapon Pickup (Gun) | Spitters | Keys

![Gunpickup, Keys, Spitters](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/305d028b-addb-4404-8d76-7c72bd6f220c)

The Key is protected by the spitter, which encourages the player to engage it, and the gun is the ideal weapon to fight the spitter due to its long range projectile attacks. Moreover, the key being protected suggests to the player that it is an important item. 


## 3. Spatiotemporal Design
 
### 3.1. Molecule Diagram

![Molecule Diagram](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/99eb2820-6203-4946-a2e0-4bdf343b2042)


### 3.2. Level Map – Section 1

![Section 1 Map](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/6fa36cdc-8e5c-473f-981e-867617bba780)


### 3.3.	Level Map – Section 2

![Section 2 Map](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/5215b94c-affa-4b3e-8d0b-0b0c75cd2d93)


### 3.4.	Level Map – Section 3

![Section 3 Map](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/746621a4-188f-47eb-8221-dd9ff05e1a99)


## 4. Iterative Design (~400 words)
Iterative design allowed me to determine poorly designed mechanics and encounters in real-time through testing and prototyping and improve upon them right away. Early-stage prototyping included hand-drawn paper prototypes for designing encounters and rough concepts for sections. These paper prototypes allowed me to fully develop an idea without having to build anything on Unity first. Other forms of prototyping included writing out encounters in detail, which further helped to develop a fully fleshed-out idea once something came to mind. 

Paper prototypes:

![20240412_181535](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/e535e6ce-f90f-42d7-b03f-eadbdb1fa9d0)
![20240412_181525](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/c4e21590-3994-441c-a3e3-6a65df02c545)
![20240412_181829](https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/3d082fd9-1409-4412-8abb-b38829f92557)

Written encounters:

<img width="671" alt="Screenshot 2024-04-12 194105" src="https://github.com/COMP2150-24s1/level-design-assessment-Eswaiy/assets/79948327/0803af01-130a-4cf2-8658-736e588977df">


Moreover, a lot of testing was carried out throughout the design of this level. Constant testing in real-time allowed me to determine design faults relating to mechanics, dynamics, pacing, challenge, and difficulty. I also carried out play testing, allowing friends and family to play the level throughout various stages of design and provide feedback on their experience. I avoided using industry jargon when asking feedback to prevent misunderstandings and instead asked them casual questions such as “Was it entertaining?” “How difficult was it?” “Could you find the keys?” and “How was the pacing?” The final design ended up quite different from the low-fidelity prototypes that I created, but they helped to get the ball rolling. 

I believe one encounter that would benefit from further iterative design is the final enemy encounter in section 3. In this encounter, the player loses their weapons and must avoid enemies in front of them to get to the weapons pickups in order to go back to a room with a hoard of Chompers guarding the final key. My issue with this encounter was that sometimes the Chompers ended up “syncing together," appearing as a single enemy as opposed to a hoard, due to them being cramped in a tiny room. Through designing and testing further iterations, I believe this issue can be solved, allowing for a more enjoyable final combat encounter.



## Generative AI Use Acknowledgement

I did not use any AI tool in the making of this assignment.

