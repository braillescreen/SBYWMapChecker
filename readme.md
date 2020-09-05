# Scrolling Battles (You're World) map checker.
A basic program to check data from a map, such as how many zones, travel points, etc. there are.

## History
I simply wanted to see how large my maps were on SBYW, so I made a simple script to let me do that.

## List of what the checker can scan for
* Signs
* Zones
* Sound sources (2D and 3D sources (now deprecated) are counted as one set of sources).
* Platforms
* Staircases
* Checkpoints
* Doors
* conveyor belts
* Hazards
* Travel points
* Walls
* Death zones (see the server change log for more info)
* Vanishing platforms

## Running
There is a release build available, for those who do not have the time or knowhow to run this code. Go grab it at the releases page.

When you run the script, the following will occur:
* An input box will come up asking you for the file name. If this is blank, it will default to a file called "map.txt".
* If the file doesn't exist, you will be told and the program will exit.
* If it does exist, it will start scanning the file. This shouldn't take more than a few seconds, should be almost instant depending on map size.
* An alert will show displaying this map information in detail. It will then exit.

## Attribution
If you find a way to incorporate this into any of you're projects, I ask that you mention that I created this script and possibly a link to the repository (https://github.com/braillescreen/SBYWMapChecker).
