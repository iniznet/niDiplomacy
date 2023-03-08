# niDiplomacy (niznet Diplomacy) 

An Experiment to make the WRECK & modSys work in python 3 with diplomacy mod based on Diplado.

## SOURCE

Forked from 
[Diplado](https://github.com/diegoami/Diplado).

__There might be serious issues in this mod, so use at your own risk.__

## Installation

I don't recommend to install this mod if you don't know what you are doing. It is not stable and might cause serious issues in your game.

## KNOWN ISSUES

* Multiplayer seems to be broken in many places

## FIXES / FEATURES

Some fixes:

* Lords return reliably from exiles
* Constable's menu to sell prisoners from the garrison is shown when there are prisoners in the dungeon
* Patrols' prisoners are put in the dungeon and not into the garrison
* Travellers now keep track of ransom brokers
* The companions' dialog when they are sent on a spy mission to a town owned by the player's kingdom is correct
* Changing minister will not abort a quest you did not start
* Removed menu option to delegate quest, as this does not seem to work
* Exiled ladies do not appear in courts
* The dialog for quest to delivery food shows the right quantity of food

Some additions:

* Can spar with your army in the arena
* No crazy charge in battle of your party (they await your orders)
* Body guards
* Import / Export companions
* Whistle for your horse (key M)
* Taunt your opponents, so that they will attack you (key O)
* Main screen informs you how many lords are in town / castle hall

Features removed

* Training on the training ground, including trainer, does not cause injuries
* Relation changes during tournaments

Also on the **development** branch

* Option to turn the hold ground command on or off
* Option to assign allied lords to a default control group
* Minimap, troop ratio and kill count in the battle screen, with the option to turn it off 

**master** releases' save files are backwardly compatible, but **develop** releases may contain more interesting features.

## Credits

Many to keep track of

* the Diplomacy mod maintainers (Waihti, hessuu, fisheye, rubik, jrider, Mjollnir, Akmar Nibelung, Parsifal, Somebody, diegoami) 
* and other Taleworlds  forum users: Dj_FRedy, Jinnai, lazeras, Caba`dr, Glabrezu, Efe Karaca


## COMPILING

1. Install a release from **https://github.com/diegoami/Diplado/releases/** as described above.
2. Set up Python 3.9
* Edit `source/compile.bat` to point to the location of your Python 3 (Unless python 3 is your default python)
* Execute `source/compile.bat`
* Copy the full content of the directory into the Mod's module directorzy
