# dungeon_rgb
Making of a dungeon rgb game, with a basic damaging system, loot system, player shooting and an drag and drop inventory 
WASD to move the player, press or hold (Left Mouse Button) to shoot 3 tiers of arrows
Press (J) to damage the player (10 dmg) and press (K) to poison the player
You can open the inventory by pressing (Tab). Once open you can drag and drop items to different lootslots. You can also drag health potions to the healthpotion slot, as long as there isn't >= 10 health potions. You can see your health amount in your inventory or under the player model in game.
Killing enemies will drop lootbags, which can contain a few different items at the moment: bows, healthpotions and rings
I have created a system for the ring items to be randomly generated depending on which lootbagtier the enemy drops, but there is only one tier of lootbag in the demo atm. You can see the randomization in the hierarchy: Player UI/ The UI/ Items. every time you press play you can see the items get different stats and names. You can also see the randomized rings on play inside the player inventory.

