# ISAACLIKE (WIP)
## Description
- Open Source recreation of a well known game "The binding of Isaac" in Pygame!
- Project is meant to be an enviroment for RL

- *All rights reserved to game owners*

## Conents
*main.py*  
- main loop and logic of the game
- minimap
- tear shooting


*proceduralboxestest.py*
- fully implemented procedural level generation that avoids stacking rooms (2x2 square of rooms)
- fully implemented longest path algorithm (for boss room)
- implemented door mechanism  TOADD: closing the doors while enemies in the room / button not clicked (with visual animation)
- fully implemented empty room layout


*groups.py*
- Sprites logic and drawing logic


*sprites.py*
- different logic for different entities
- TEAR (bullet) logic
- CollisionSprite logic
- Rock logic TOFIX: rocks sprites tend to preserve through rooms, but without collisionboxes
- Enemy_greed logic (basic enemy)
- Spider logic (basic spider)
- TOADD: coin logic


*player.py*
- movement for player
- collision detection for player

*level_editor.py*
- gemini driven level editor for custom levels with saving
- avaible to add enemies from sprites.py
- TOFIX: sometimes editor allows for placing mutliple objects at one location




