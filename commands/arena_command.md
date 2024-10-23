# The sandbox $arena command

This command is available in sandboxes where
you have the `arena owner` or `arena operator` permissions

To create a sandbox, select the sandbox tab in the main menu
click on a empty sandbox in your preferred region and click play
Creating your own sandbox automatically grants you the `arena owner`
permissions

You can get `arena operator` on any sandbox if you ask the owner
if they can give you the permissions using `sandbox+;` though for 
this you might want to read the sandbox documentation

## $arena

Just writing $arena will reveal the help menu for the following commands:

## $arena size 

Change the arena's size
More specifically change the borders of the arena
where regular tanks won't be let out of bounds

you can put the arena size as "dynamic"
ive taken a little bit of effort of figuring out how
the arena scales

i've found that the arena scales by:
    1 player: 40x40
    2: 56x56
    3: the same as two

i cant spawn more players so feel free to experiment yourself

so the arena scales by how many players there are (default)

or two integers (numbers with no decimals) which have to be:
    - even (multiplicable by 2)
    - higher than 0
    - equal or lower to 1000

note that the middle (of the arena) is always going to be 0, 0
for example::
    $arena size 200 400

the middle of the arena is 0, 0
the top left is 100, 200
the bottom right is -100, -200

parameters:
$arena size <dynamic or 2 integers>

example usage:


$arena size dynamic

$arena size 1000 1000

$arena size 2 2



wrong:


$arena size 0 0

$arena size 1 1

$arena size 41 77

$arena size 9999 9999

$arena size random letters



## $arena team

Set the number of teams, from 0 (FFA) to 4 (4TDM)
0 = FFA
1 = no one can hurt one another (like nexus)
2 = 2TDM
3 = 3TDM
4 = 4TDM

TODO: add more documentation here

parameters:
$arena team <integer from 0 to 4>

example usage:


$arena team 4

$arena team 0

## $arena spawnpoint

Set a location where all players spawn by default
i think this is quite self explanatory:
if a player's spawnpoint isn't set by a respawn wall (check the sandbox documentation for that one)
they player will spawn at the set coordinates

the two parameters represent the width and height on the x and y axis
they may be passed as float (numbers with decimals)
if the number exceeds the arena's bounds, the player will spawn closest to where they would've spawned 

parameters:

$arena spawnpoint <x> <y>

example usage:

$arena spawnpoint 21.7 45.4

spawn players in the exact middle by default:

$arena spawnpoint 0 0

## $arena close

Close the arena
a little bit of a troll command
this command will call upon the arena closers as they shall destroy and close the arena
the server will be closed, any players, walls, shapes will be destroyed
if there are no killable players (invicible, spectators)
the arena will just close
after closing the arena, the tag of the sandbox will be reusable

BIG NOTE: as you can probably tell, this is a very dangerous command, 
this is why you should be careful to whom you're giving arean operator

parameters:
$arena close

example usage:
$arena close


## $arena public

Allow this server to be displayed in the sandbox nexus
i have yet still to find out where the sandbox nexus is
though, when you execute this command, it is certainly public; players will join your sandbox
best if you want your sandbox to have attention

parameters:
$arena public

example usage:
$arena public

## $arena private

Prevent this server from being displayed
The opposite of `$arena public`
this is executed by default
will not let players join your sandbox unless they have the link to it

parameters:
$arena private

example usage:
$arena private
