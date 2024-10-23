# Attribute subcommand

**i will be refering to sandbox+a as attr to make it shorter and easier to read**

## All team minimap
bind: attr+t

Show all players on the minimap
this includes players that are not on your team

press again to disable

## Hidden from minimap
bind: attr+m

Hide yourself from the minimap of your teammates
some commands do this by default
like becoming a spectator etc.

how this works with the all team minimap attribute
im not sure


## Shown on leaderboard
bind: attr+l

enabled by default
toggle hiding yourself from the leaderboard
this doesnt work like incognito mode
will COMPLETELY remove you from the leaderboard

when in spectator mode you cannot be visible on the leaderboard

## No reload cooldown
bind: attr+c

now this is the most fun of them all
removes cooldown for all non auto barels
from what i think
will try to shoot every frame (60 fps)

makes you tank shoot extremely fast
i dont know much practicality but
hell yeah, try this with booster,
you will be flying all over the arena

for bullet barels:
    - shoots its bullet every frame

for droner barels:
    - will attempt to produce a drone only
        if there arent all drones at the field already

for trapper barels:
    - same as bullet

this **does not** work for auto barels
such as auto assasin auto barel or auto-3

## No recoil
bind: attr+r

recoil is the pushback you get from shooting a bullet/trap/drone
this will disable the pushback
you can pair this will no reload 
can be sometimes helpful when you dont want to get
distrubed by recoil while making some tests

## No arena boundary force
bind: attr+o

will allow you to go out-of-bounds
for you, this will act like if the arena was 1000x1000
as you cannot go past 1000 on any axis
your bullets/traps/drones will still be pushed
in bounds of the arena

## Pass through walls
bind: attr+w

pretty self explanatory
will also remove all effects of physically
touchable walls

normal wallls will be ignored
fake walls will act the same
black (bouncy) walls will no longer bounce you
respawn setter walls will act the same as before

## Accepts score
bind: attr+s

toggle if your tank accepts score
if your tank can gain score from destroying polygons and players
might make things less distracting

# Actions

these are normal binds that can be binded onto your
left or right click

its disable/enable if its binded to your mouse click

the bind for all of the below are 
`attr+original_key` where original_key
is the key to the bind its replicating

## Teleport

The teleport bind (`sandbox+e`)
whenever you press right click you will be 
teleported to the location of your cursor

## Get data

the get data bind (`sandbox+g`)
by left clicking on an entity you can get its data
problem is left click is always binded to your main barel
also im not sure how this even works anyways
sometimes it says "Cleared selection." randomly

## Drag action

the drag bind (`sandbox+d`)
by left clicking on an entity you can drag it like
the regular drag bind
this is really helpful since draging things a lot
can be tiring

## Blast action
the blast bind (`sandbox+b`)
by left clicking anywhere the regular black bind
will be triggered
i dont find the regular blast bind useful
so why would i found this to be useful