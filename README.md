# Altium Designer Scripts
This is a list of my most-used Altium Designer scripts with a brief comment on each.\
\
Cheers!\
Ryan Rutledge, CID+

# Credits
I owe many thanks to other script writers who have contributed to the Altium-Designer-addons script repo. Special thanks to 
* Corey Beyer
* Tony Chilco
* Matija Markovic
* Brett Miller
* Petar Perisin
* Stephen Thompson

Many other members of the Altium Designer community have also rendered invaluable feedback, encouragement, and inspiration for my scripting work. There are too many to list without forgetting somebody, but special thanks to
* Eric Albach
* Randy Clemmons
* Rhys Drummond
* Michael Hoopes
* Darren Moore
* Jack Olson
* Tim Phillips
* Mark Ross
* Dennis Saputelli


# My Must-Have Scripts
These are my must-have scripts. For scripts that weren't created by me, I have contributed to them _because_ they were so useful to me that I wanted to enhance them even more, and pay back some of the help they gave.

## [Distribute](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/Distribute)
Has GUI. This script evenly distributes parallel tracks by their pitch or their clearances. It can also set arbitrary pitch or clearance and center tracks between pads or vias.

## [Fillet](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/Fillet)
Has GUI. This script creates fillet(s) on selected joined tracks. Works with tracks at nearly any angle with multiple configuration options.

## [QuickSilk](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/QuickSilk)
Has GUI. This script allows you to very quickly place reference designators and comments interactively around a component with configurable clearance settings and so that changes to the text grow in a logical direction.


# Other Scripts to Highlight
These are other scripts I have found particularly useful

## [FindUnmatchedPorts](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20SCH/FindUnmatchedPorts)
No GUI. Schematic Script. This script helps find unmatched or floating ports within project schematic sheets.

## [AutoPlaceSilkscreen](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/AutoPlaceSilkscreen)
Has GUI. It's safe to say QuickSilk would not exist without this script by Stephen Thompson. This script can help automatically place reference designators in clear areas.

## [LayersAndObjects](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/LayersAndObjects)
Has GUI. Very handy script for troubleshooting internal layer IDs not matching stackup layer order.

## [RepositionTestPoints](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/RepositionTestpoints)
No GUI. Place testpoints interactively simply by clicking an object in the destination net.


# Other Scripts I've Created
These are scripts that I originally created to address specific needs at work or to address requests posted to the Altium Designer user forums.

## [AssemblyTextPrep](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/AssemblyTextPrep)
Has GUI. This script is a utility tool to help with positioning and sizing .Designator special strings in a PCB document.

## [PCBObjectInspector](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/PCBObjectInspector)
* _My go-to script for debugging_

No GUI. Select items in a PcbDoc and run `_Inspect` to inspect the underlying properties of selected items.

## [PolygonBenchmark](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/PolygonBenchmark)
No GUI. This script is a utility tool to benchmark the relative repour times of the polygons on a .PcbDoc.

## [ReturnViaCheck](https://github.com/Altium-Designer-addons/scripts-libraries/tree/master/Scripts%20-%20PCB/ReturnViaCheck)
Has GUI. Based on an Idea posted to Altium Designer community. This script is a utility tool to help detect high-speed signal vias without a nearby return via.
