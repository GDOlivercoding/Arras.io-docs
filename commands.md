# Arras.io Commands Documentation

Arras.io has a few commands which can be accessed through the game's chat system

To use a command, press enter to open the chat bar, type "$" (all commands have the dollar sign prefix, even the game's bot on discord)
followed by the command's name and its parameters

## $help

This command shows the help menu for some regular commands usable in any mode, lets cover those first

## $leaderboard or $b

$leaderboard lets you change from which servers to display the leaderboard from
from what i can remember, this is only usable in old dreadnoughts

this command shows you either all players across all 3 old dreadnoughts servers or
just the server you're in right now

parameters:
$leaderboard <default or global>

default will show the leaderboard for the local server and global for all

example usage

$leaderboard default
$b global

## $toggle or $t

Very simply just disables chat messages, all chat messages from now on will be dis/enabled
all messages before the execution of this command will be invisible until they disappear
a good way to either keep your child safe or play in a more focused environment
enter the command again the reenable chat messages

parameters:
$toggle

example usage:

$toggle
$t

## $channel or #c

Select the channel your messages are being sent to 
by default, your messages can be seen by anyone

NOTE: this command doesn't seem to work
if you know how it work, hmu on discord or
leave a comment on this github repo and ill edit
so far, it seems like you can only target your messages
globally

parameters:
$channel <team or global>

example usage:
$channel global

## $afk

Prevents you from being pushed when AFK in base
thats the command description
in reality:
    - when AFK you cant disconnect
    - if you get pushed out, the game will push you back in
    - you cannot take ANY damage while $afk

a very simple tool preventing pushing out of base
disconnecting while AFKing and getting pushed to the corners
and killed with drones since you cant take damage

enter $afk again to stop afk

parameters:
$afk

example usage:
$afk

## $status or $s

Check how long the arena has been open for 
and how long will it last for

upon executing the command, a popup will be shown
on the top middle of your screen
telling how long has the server been up
and how long the server can be alive (maximum)

note that a server can be closed if its inactive
or if a minigame is won

parameters:
$status

example usage:
$status
$s

