
To do for trAInsported:
=========================

**Map (Editor)**
[x] Tile map
[x] Random environment pieces

**Sandbox**
- Events:
	-[x] "Init"
	-[x] "chooseDirection"
	-[x] "New Passenger"	-- special argument if the passenger's a VIP.
	-[x] "Arrived at Passenger's tile"
	-[x] "Arrived at Passenger's destination"
- Functions:
	-[x] "drop off passenger"		-- removes passenger from train
	-[x] "pick up passenger"
	-[x] "Random"
	-[x] "Print"
	-[x] "New Train"

**Server**
- Stage Special fights between the two best AIs every two hours.

**Security**
[x] Before download/upload, add a line that won't allow the scripts to be run without the game.
[n/a] Automatically replace windows line endings with unix line breaks.

**Game**
[x]	Add VIPs
[x]	Add Hotspots
- Randomize order in which players get to move?
[x] increase # of waypoints
[x] buy new trains
[x] rework train movement: make it pixel-independet and make it work with percentages.
- Add statistics for passengers at round end
- Make game deterministic!

**Tutorial**
tut 1: 
[x] Controls
[x] Init game, print
[x] Placing train
[x] Picking up passenger
[x] Letting passenger get off
tut 2:
[x] Lua control structures (while, if)
[x] Junctions
tut 3:
[x] Multiple Passengers
[x] Smart choosing of directions (depending on passenger's dest)
tut 4:
[x] euclidean distance

**Visual**
[x]	clouds
[x] trees
- water
[x] Urban setting
- weather?
- Seasons change graphics?
[x] rails with sidewalks
- speed controls
- don't let passengers stand on the rails.
[x] show hotspots

**Misc**
[x] Add tipps?
- No guarantee that game's outcome is always the same...
[x] Status message box
[x] make sure globals.lua is the same for server and client!
[x] train movment on client is now no longer allowing overshoot -> same for server!
[x] possibly make server and client use the same files?!
[x] tooltips
- rewards!!
[x] Make "Last Match" logging use only one querry...
[x] Log Date along with "Last Match" and display on website
[x] screen resolution set at first start!
[x] Tutorial "tutorial continued" when pressed F1 !
[x] Tutorial "cursor keys"/"arrow keys"
[x] Rename "End Match" button in simulation
[x] Add switch for rendering clouds
- Different statistics for different game modes/map sizes.

**Maybe**
- buy code lines using in-game cash?
- handicapped people
- option to transport multiple passengers?
- modify payment method in-game?
- two or three rail types?
- game mode where map is NOT passed to ai.init? (Fog of war?)
- Repair costs?
[x] Split up rendering of map images into multiple threads?
- dither full screen
- scrollbar for console
- click on AI to focus on train
- print kostenlos?
- Expose train positions to users

**Website**
[x] rank of players?

**Bugs**
[x] generator can generate empty maps?
[x] default resolution... how to change?
[x] sometimes Simulation does not render new map for some reason.
- nil pointer when in simulation
[x] fast-forward problem: stops showing updates when on fresh connect.
[x] fails to render new map is a new map is given while still rendering the old one (simulation)
- Tutorial 3: jumps over ai.foundDestination part
- Error Scripts/train.lua:643: attempt to index index field 'image' (a nil value)
[x] Trains stop on live server
[x] train colors are wrong in simulation!

**Windows:**
- Added configFile.lua
- Changed screenResolution writing
- READ NUMBER OF CPU CORES on WIN!
- picture colors are different??
