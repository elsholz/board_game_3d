# board_game_3d
Open Source Board game made of 3d printed parts.

# Map
Default 4 Players Bases. 
Each Player Base has a forest and a gold mine, as well as enough space for buildings.
Player bases are connected to each other by Paths.
Paths consist of segments, some of those contain events.
Events are chosen randomly, mostly having negative effects for crossing troops.
In the center, there are 4 gold mines unoccupied.
There are also some additional forests distributed on the map.

# Troops and Settlers
|Name|Strong against|Movement|Cost|
|---|---|---|---|
|Cavalry|Artillery|3 Segments per move|5 Food 2 Gold|
|Infantry|Cavalry|2 Segments per move|3 Food 2 Wood 1 Gold|
|Artillery|Buildings, Infantry|1 Segment per move|2 Food 2 Wood 3 Gold|
|Settler|Resources|Can be moved around freely|2 Food|

# Resources
All Resources are available as tokens.
- Gold
	- mined in gold mines
	- finite 
- Food
	- harvested on fields
	- infinite
- Wood
	- harvested in forests
	- infinite but scarce

# Buildings
|Name|Construction Cost|Description|
|---|---|---|
|Corn Field|2 Wood|max 2 workers per field<br>1 food per worker per move|
|Wall Layer|6 Wood|Can be placed on segment borders<br>Up to 3 layers per wall|
|Defense Tower|10 Woodm 4 Food|Can be placed behind walls<br>max 2 towers per wall|
|Barracks|10 Wood|Can Produce troops of any kind<br>max 2 troops per barrack per move|
|City Hall|15 Wood, 15 Gold|Necessary to construct buildings on a base<br>Used to produce Settlers<br>max 3 settler per city center per move|
|Gold Mine|4 Wood|max 2 workers<br>1 gold per worker per move<br>capacity 50 gold<br>Can be placed on a mine|
|Forest Sawmill|4 Wood|max 5 workers<br>1 wood per worker per move<br>capacity 30 wood<br>grows 3 wood per move<br>Can be placed in a forest|
 
# Start
Every player starts with 5 Wood, 10 Food and 0 Gold. In his base he will already have a constructed gold mine, sawmill and city hall.

# optional additional rules
1. Every segment has a name (equal to a village) by having conquered (meaning having troops on this segment) it the player will receive a to this segment specific bonus ressource (like taxes). At the start of the match these segments are being defended by neutral troops, the further you reach from a players base the stronger the defense will be.
2. Fighting will be calculated algorithmically. On special events the player has to roll the dice, depending on the result the event can be rough or not so rough, this will be calculated by an algorithm aswell. 
