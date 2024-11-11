# Arras.io Commands

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

## $afk or $a

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
$a

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

## $report

Report the last 10 minutes of chat messages
improper use of the command will result in punishment!

now i dont want to say anything, but the developer
will probably not care, and anything regarding slurs,
swears, or potentially unwanted harrassing messages will be ignored
use the $toggle command to get rid of that person or choose a different server

parameters:
$report <reason>

example usage:
$report racial discrimination

---

Now for the *mostly* hidden commands

## $auth

This way you can synchronize your discord account
with your arras.io in your browser
i am pretty sure this doesnt do anything *yet*
there are arrasio account scheduled for the future
this will probably be the way of syncing them

to use this command message the arras.io bot (arras
#8547)
in direct messages of the bot type `$login` and press enter to send the message

the bot will respond with an authentication code
reveal the spoiler and copy the whole command

then insert it into arras.io command

**as said by the arras.io once loged in, do not install any userscript as they might steal your account**

## $arena

a command with subcommands made for sandbox
any sandbox owners and sandbox operators have access to all of the subcommands
also any arras.io admins can use these commands in the game
but theres a high you chance you wont be able to

check the `arena_command.md` file in this directory

## $nexus

the most special command of all
i haven't knew til yesterday

**only available in sandboxes**

run `$nexus` in sandbox
this will teleport you to the "sandbox nexus"
where you can visit other public sandboxes

more info in the `sandbox nexus` directory