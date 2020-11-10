# board_game_3d
Board game made of 3d printed parts

# Map
Default 4 Players Bases. 
Each Player Base has a forest and a gold mine, as well as enough space for buildings.
Player bases are connected to each other by Paths.
Paths consist of segments, some of those contain events.
Events are chosen randomly, mostly having negative effects for crossing troups.
In the center, there are 4 gold mines unoccupied.
There are also some additional forests distributed on the map.

# Troops and Settlers
|Name|Strong against|Movement|Cost|
|---|---|---|---|
|Cavalry|Infantry|3 Segments per move|5 Food 2 Gold|
|Infantry|Artillery|2 Segments per move|3 Food 2 Wood 1 Gold|
|Artillery|Buildings|1 Segment per move|2 Food 2 Wood 3 Gold|
|Settler|Resources|Can be moved around freely|2 Food 1 Gold|

# Resources
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
|Corn Field|1 Wood|max 2 workers per field<br>1 food per worker per move|
|Wall Layer|2 Wood|Can be placed on segment borders<br>Up to 3 layers per wall|
|Defense Tower|5 Wood|Can be placed behind walls<br>max 2 towers per wall>|
|Barracks|10 Wood|Can Produce troops of any kind<br>max 1 troop per barrack per move|
|City Center|15 Wood 15 Gold|Necessary to construct buildings on a base<br>Used to produce Settlers<br>max 1 settler per city center per move|
|Gold Mine|n/a|max 2 workers<br>1 gold per worker per move<br>capacity 50 gold|
|Forest|n/a|max 5 workers<br>1 wood per worker per move<br>capacity 30 wood<br>grows 3 wood per move|
 

