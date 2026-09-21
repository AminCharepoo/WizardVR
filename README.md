# WizardVR

A VR dungeon-crawling game developed as a four-month team project for Northeastern University's NUVR club.

Players fight through multiple dungeon rooms using a wand and sword before facing a final Golem boss. The game combines gesture-based spell casting, melee combat, enemy AI, VR interactions, and room-based progression.

## Gameplay

The player enters a dungeon equipped with:

* A wand in their right hand for casting spells
* A sword in their left hand for melee combat
* Health and speed potions stored on their belt

The player progresses through three rooms of skeleton enemies before entering a final boss room containing multiple skeletons and a large Golem boss.

The objective is to **survive the dungeon and defeat the Golem**.

### Combat

Players have two primary ways to fight:

**Wand**

The player draws a specific shape with the wand to cast a spell. When the resulting spell collides with an enemy, it deals damage.

**Sword**

The player can grab and use a sword for close-range melee combat.

**Potions**

Health and speed potions can be stored on the player's belt and consumed during gameplay.

## Key Features

* VR hand-based interactions
* Gesture-based spell casting
* Sword-based melee combat
* Enemy detection and pursuit
* Enemy attack and health systems
* Golem boss encounter
* Health and speed potions
* Physics-based object interactions
* Multi-room dungeon progression
* In-game tutorial UI
* Custom spell audio
* Five-person team development using Git

## Technical Implementation

### Spell System

The spell system uses wand gestures as the input for casting.

The player draws a predefined shape with the wand. Once the correct shape is recognized, the corresponding spell is created in the scene.

The spell uses collision detection to determine when it hits an enemy. On collision, the enemy takes damage.

The project currently contains one spell.

### Enemy AI

Enemies use Unity's navigation system to move through the dungeon and pursue the player.

The enemy system handles:

* Player detection
* Movement toward the player
* Attack behavior
* Enemy health
* Damage
* Death behavior

The same systems are used to control the skeleton enemies encountered throughout the dungeon.

### Boss

The final room introduces a large Golem boss alongside additional skeleton enemies.

The Golem uses its own combat behavior, including throwing rocks at the player.

### VR Interaction

Objects can be picked up using the Oculus Quest 2 controller grips.

The interaction system uses Unity physics and colliders to allow the player to interact with physical objects such as the sword and potions.

### Inventory

The player can store consumable potions on their belt.

The inventory system handles storing and accessing the health and speed potions during gameplay.

### Level Progression

The dungeon is divided into multiple rooms.

Players must defeat the enemies in each room before progressing to the next area. After completing three skeleton-filled rooms, the player enters the final boss encounter.

### UI and Tutorials

The project includes an in-game UI system containing menu buttons and visual tutorials to introduce the player to the game's mechanics.

### Audio

Custom audio was created for the spell system to provide audio feedback when spells are cast.

## Development

This project was developed over approximately four months by a team of five.

My contributions focused heavily on gameplay programming, including:

* C# gameplay systems
* Enemy AI
* Enemy health and attacks
* Player combat
* Spell damage
* Potion inventory
* Room progression
* UI and tutorials
* Spell audio
* Level design

## Challenges

### Enemy AI

One of the major challenges was creating enemy behavior that could consistently detect, pursue, and attack the player within a VR environment.

The enemy system was developed around player detection, navigation, attack behavior, and health management to create a complete combat loop.

### Combat Collisions

Another challenge was making VR combat interactions behave reliably.

Both the sword and spell system rely on Unity's physics and collision systems to determine when attacks interact with enemies. Getting these interactions to respond consistently was important for making combat feel responsive.

## Technologies

* **C#**
* **Unity**
* **Git / GitHub**
* **Oculus Quest 2**
* Unity Physics
* Unity Navigation

## Assets

Monster models and animations were sourced from the Unity Asset Store.

The gameplay systems, enemy behavior, combat systems, UI, level design, and other listed contributions were developed by the project team.

## Project Status

**Completed**

The project was developed as a four-month club project and includes a complete playable dungeon sequence ending in a Golem boss encounter.

## Future Improvements

Potential future improvements could include:

* Additional spells
* More enemy types
* Additional dungeon levels
* Expanded inventory mechanics
* Additional boss mechanics
* Save/load functionality
* More advanced enemy behaviors

## Team

Developed by a five-person team as part of Northeastern University's NUVR club.

**Amin Charepoo** — Gameplay Programmer

