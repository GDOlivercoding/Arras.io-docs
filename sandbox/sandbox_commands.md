# Sandbox Regular Commands Docs

**I will refer to your sandbox keybind as `sandbox`, check the README file for more details**

*help menu is in ./help_menus/sandbox help menu.jpg*

## Preset tank
bind: sandbox + +
this `+` is the number 1 in your hotkey bar

this command turns you into a spectator 
where you cannot physically interact with anything
or anyone and just float and... spectate
you can get back by doing `sandbox+q`

## Basic
bind: sandbox+q
Your regular `q` on your keyboard

as mentioned above, this command turns you into a basic and:
    - resets your size
    - if your skills are above 9, set the skill cap back to 9
    - any attributes applied (from /attributes)

## Teleport
bind: sandbox+e
Your regular `e` on your keyboard

Teleport you to the location of your cursor on the map
if held, keeps on teleporting you in the direction of your cursor
Best way to just get somewhere on the map

attribute:
    You can set this to happen whenever you press right click
    by enabling an attribute, refer to attribute directory

## Kill
bind: sandbox+k
Your regular `k` on your keyboard

Kills whatever entity is under your cursor
can be a player, shape or wall
yes, you can kill your own tank by hovering over yourself
and pressing the bind
if held, will attempt to kill anything under your cursor
there are some issues if walls are too small

## Whirlpool
bind: sandbox+w
Your regular `w` on your keyboard

This is also very similar to `Drag`
Click and hold, Grabs the nearest entity and moves it under your cursor
then you can move the entity (while holding) anywhere you want
release to free the entity

## Drag
bind: sandbox+d
Your regular `d` on your keyboard

Read Whirlpool above
Same as Whirlpool except if theres no entity under your cursor
the command will fail
for Whirlpool, if theres no entity under your cursor
it will grab the nearest entity

## Wall
bind: sandbox+x
Your regular `x` on your keyboard

Places a wall on the map
if you click and the drag in any diagnal direction
you can increase the size of the wall
after releasing you may not change the size of the wall
press next to an existing wall to copy its size
cannot be held

walls' types can be changed with `sandbox+z`
see two commands under

## Polygon
bind: sandbox+f
Your regular `f` on your keyboard

Create a polygon at the location of your cursor
hold to create multiple
theres a limit to how many polygons there may be in a sandbox
if you recently changed a polygon with `sandbox+z`
this command will spawn such polygon with same properties
as the recently changed

## Type
bind: sandbox+y
Your regular `y` on your keyboard
may vary if you have qwertz or qwerty keyboard

Change the type of an entity
since this command has a lot of things to it
theres is a dedicated directory (/types and colors) to it

Click and hold over an entity to change its type

for polygons you may change:
    - size (regular, beta, alpha and omega) / crasher (crashers dont have size)
    - type of polygon (egg, square, triangle, pentagon and hexagon)

For walls you may change:
    - wall type (
        behavior, ex.: healing wall, damaging wall, fake wall
        respawn setter,  teleport wall,
        launchpad wall(made up name, but it suits it well)
    )

## Color
bind: sandbox+c
Your regular `c` on your keyboard

Change the color of entity
The color of entity won't change the behavior of entity
Coloring walls and solid walls which reject other colors WILL change behavior
by clicking and immediately releasing the entity
will be colored the last color you used

you may color:
    - players
    - polygons
    - walls

since this is a little messy, there
is a dedicated directory (/types and colors) to it

To put it simply, hold over an entity then move your
cursor around it in a circle, each angle represents a color
release to set color
may be buggy, release c first, then your sandbox keybind

## Vanish
bind: sandbox+v
Your regular `v` on your keyboard

This command cannot be used on other entities
Makes you permanently invisible
no players or entities can see you
this is not like arms race permanently invisibility
you are COMPLETELY invisible, except your bullets of course

press `sandbox+v` again to become visible again

## Invulnerable
bind: sandbox+i
Your regular `i` on your keyboard
this is an `i` as in "i love you" and not an l as in "loser"

This command cannot be used on other entities
Makes you permanently invincible/invulnerable
whenever you are supposed to take damage you dont
and the attacking bullet will take the amout of damage it would
you are still visible to everyone
entities will not be aggressively towards you (crashers, bosses)
the only way to kill a player with `sandbox+i` is to use
`sandbox+k` to kill them

press `sandbox+i` to become vulnerable again

## Team
bind: sandbox+t
Your regular `t` on your keyboard
Change yours or others' team¨
click on an entity to change its team to yours
click anywhere else to change your team

This command is quite buggy i found
change your team to a polygons team
by pressing the keybind while hovering over a polygon

then press the keybind anywhere else
now you should be able to change your and others team
funnily enough, you can actually kill your tank this way
if your a drone tank, changing your team will keep your drones
but they will be able to damage you

TODO: missing docs

## Invite to team
bind: sandbox+y ?????
????????

???????????
???
?????
?
???????????

this seems to be a deprecated command
i dont think it works in any way, shape or form

## Heal
bind: sandbox+h
Your regular `h` on your keyboard

Fully heal an entity
Hover over an entity then press keybind to fully heal it
this only works for players and polygons as walls do not have health
if you press the keybind while not hovering over an entity
you get fully healed

...why im i even explaining this lol

## Skill: subcommand
bind: sandbox+a+

This is a subcommand which means there are
more commands in this command
this subcommand controls `skills`
or how you would know as `upgrades`
(clearing, maxing, adding, reducing etc.)
visit /skills if you wish to know more

`sandbox+a+?` shows the help menu

## Get data
bind: sandbox+g
Your regular `g` on your keyboard

press while hovering an entity to get the entity's data

reveals:
    - name
    - score
    - build

works for players, polygons and suprisingly walls but doesn't give much

you can execute this command with your left click
if you enable the Get data attribute
visit /attributes if you wish to know more

## Infinite level up
bind: sandbox+n
Your regular `n` on your keyboard

Hold this keybind while your cursor is anywhere
and you will expotentially gain score
the score cap is around 4.3 billion (integer limit)

it just gives you score i dont think i need to say more
yeah also, doesnt work on other entities

## Police
bind: sandbox+p
Your regular `p` on your keyboard

Playful command
turns you into a booster with two decorational crosses 
across your tank with blue and red indicating police sirens,
your name will be changed to "TEAM POLICE",
the tank's name is "undercover cop" and will be assigned to you
maxes out your skills, extends your vision and
announces "WOOP WOOP! That's the sound of da police!"

This is clearly a reference to that one song
and maybe arras police on youtube
theres not much practicality to this keybind

## Blast
bind: sandbox+b
Your regular `b` on your keyboard

I'd say playful command since you cant really control it
pushes back any polygons and players around your cursor
including you
can be held, and if held close to you, can propetually push you back

i'd say its pretty satisfying when you put a bunch of alpha eggs
on top of each other and then you press this keybind in the middle
of them all

## Joint
bind: sandbox+j
Your regular `j` on your keyboard

Complicated command
forces an entity to be a set distance away from each other
check `joint.md` in this directory for more details
because even i dont know this one
good for making complex builds like auto opening doors
theres is a good tutorial for this on youtube by
the arras police i think

## Attribute: subcommand
bind: sandbox+a+

this is a subcommand which means
there are more commands in this command

this can change some properties of your tanks such as:
    - no recoil
    - no reload
    - no arena boundary force
    - accepts score
    - is visible on leaderboard
    - binding certain keybind to left or right click

`sandbox+a+?` shows the help menu

check /attributes for info regarding this subcommand

## Zoom-out
bind: sandbox + =
this `=` is located two spaces left from my backspace
it should have a `%` sign above it accessible by shift clicking (unrelated)
if you cant find it, look at your help menu and see what it says its keybind is
also look in your hotkey bar for anything mentioning an equal sign

Extends your FOV (Field Of View), aka Vision
not usable on other entities
some tanks' attack may extend based on this view
drone tanks have a massive advantage,
since they can more accurate guide their drones

in arras.io, the faster a bullet/trap/drone is
the more damage it does
enabling some builder like tanks to see more will make the bullet faster
hence stronger

though this command is mostly used for convenience of
not having to teleport everywhere

## Zoom-in
bind: sandbox + -

though it says its a dash, its located one space away from my backspace
you can find this based on your zoom out key, then try adjacent keys

zooms in by decreasing your FOV
read the bind above, as it mentions all this does

## Reset zoom
bind: sandbox+0
this is a zero located in your hotkey bar

resets FOV
if you decreased/increased your FOV it will set it back to normal
...do i have to say more?

## Smaller
bind: sandbox+,
Your regular comma you have on your keyboard
my comma is to the right of my `m`

makes your tank smaller
hold to propetually make yourself smaller
there is a limit to have small you can be
makes your field of view smaller too
doesnt affect anything else

## Bigger
bind: sandbox+.
a period aka dot
in whatever way you type out your .

makes your tank bigger
hold to propetually make yourself bigger
theres is a limit to how big you can be
its about 40 grid units in diameter
will make your bullets appear slower

## Promote user
bind: sandbox+$
here theres is no apparent $ key
for me, to type out $ i press `alt gr+ů`
google and find out how to make your $ character
then press the second key with the sandbox keybind

promote a user

there are 5 permission levels:

    - basic user

    - arena conductor (access to sandbox commands)

    - arena supervisor (can demote arena conductor
        and promote basic user to arena conductor)

    - arena operator (gains access to $arena,
        can demote arena supervisor and promote arena conductor)

    - arena owner (the owner of the arena, cant be demoted, controls 
        everything, has all the rights of all the previous permissions)

when you create a sandbox you're automatically arena owner
if you join a sandbox you are automatically a basic user

based on these permissions levels you can promote certain users
by default by joining a sandbox, you cant

## Demote user
bind: sandbox+,
i cant seem to reproduce the character
it should be somewhere close to your promote user keybind
it looks like a line getting thinner the further its down

read the command above, as it covers most of what this does too
you can demote anyone lower than you
as a basic user you cant demote

theres a bug where the arena owner can demote themselves and lose the 
permissions of arena owner
they can demote themselves down to arena supervisor