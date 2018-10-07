# Safeguard
Design Document: https://docs.google.com/document/d/10jtAlhoJLU_Mr-GSfiQ4CmBl5haUXxVf7bTOlKZ3cNo/edit?usp=sharing

NOTE: Please unzip Safeguard(win)_Data.zip and place the contents in the same folder as Safeguard(win).exe and UnityPlayer.dll. 
Then simply run the exe in order to play the game.

Objective:
The objective of the player is to replace the four factories on the corners of the map with more eco-friendly replacements.
In order to do so they must gather reources to build these replacements.
While try to gather the factories will spread pollution around the map on a turn by turn basis.
The player wins if they are able to replace all four factories without the pollution covering 80% of the map.

Controls:
Select a character to activate,
once a character is activated you can use the buttons on the left side of the screen to preform actions.
In order to preform an action a character must have enough action points (noted on the top right corner of the screen).

Actions:
Move - Action Point Cost: 0
Once you have selected this action you can click on any tile within the characters movement to move the character to that tile.	
	a character can only move to a tile if it has enough movement to reach that tile (noted on the top right corner of the screen).

Gather - Action Point Cost: 2
Once this action is selected the active character will gather resources from their current tile.
	Once you have gathered from a tile you will resive resources based on that tiles type. You cannot gather on an Empty Tile.
	You cannot Gather on the same tile until it's cooldown of 3 turns has worn off.

Rush - Action Point Cost: 1
Once this action is selected the active character will gather resources from their current tile.
	This differes from the Gather action as the character will gather Shell and Leather.
		Shell can be used to replace Ore and Clay
		Leather replaces Wood and Sand
	You cannot Rush on the same tile until it's cooldown of 3 turns has worn off.
	Also when Rush is used it increments the tiles pollution level by one.

Clean - Action Point Cost: 1
Once this action is selected the active characters cleans off one point of pollution from their current tile.

Build - Action Point Cost: 1
Once this action is selected the active character will will build a Building on their current tile. Once a building is built it remains for 3 turns, during that time
	none of the tiles adjacent to the buidling will increment their pollution, even if the turn ends.
	In order to create a building you need to have the proper materials, any combination of 2 and 3 is enough.
	The build action is also used to replace the four factories on the corners of the map with eco-friendly alternatives.
		in order to replace a factory you must have 3 each of Clay, Sand, Ore, and Wood and there can be no pollution on the tiles adjacent to the factory.
	Resources gain from rush (i.e. Shell and Leather) can only be used to build Building not to replace Factories.
