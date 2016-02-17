# Ways to NOT make money
## A basic Python 2.7.9 / Python 3.5.1 Cookie-Clicker style (incremental) game. 

If anyone can help me edit the game, please post an issue telling me to add you, and I will add you (once I have added you, please close the issue)!

Also, if you have downloaded this game and find any bugs, please post them to the 'issues' page (the exclamation mark on the right-hand side of the browser). Thanks!

IMPORTANT: Do pull-requests to "future" branch, not master branch, unless completely necessary to merge to master.

NOTE: Game is for use with Windows/Linux (?) Support for Mac OS X is in development

NOTE: This game in the master and python3 branches currently requires the user to download Python to run. An executable file is in the ".exe version" branch!

NOTE: For Python 3.5.1 version, visit python3 branch. (Too, see #19)

Line Amount: 1284 lines (and counting!)

File Size: ~58KB (Game itself, photos take up an extra ~650KB, other files take up ~18MB)

Version: 0.6.3b2

Changelog:

     0.6.3b2:
            -Added in-game open browser for issue-reporting
            
     0.6.3:
            -Updates are rolling in!
            -Tweaked the savefile, so they don't constantly refresh
            -Changed the setup of the 'issues' box
            -IMPLEMENTED AUTOUPDATING for savefiles!

     0.6.2:
            -EVEN MORE MAJOR OF AN UPDATE!
            -Added multiplayer (you can play with your friends on the save device!)
                -Changed the mechanics of savegame()
            -Report issues in-game, you don't have to open web browser!

     0.6.1-alpha:
            -MAJOR UPDATE!
            -Improved the "cannot affords" and "no requirements", changing the sign to a label that appears in the same place instead of a pop-up window (because those are annoying).
            -Added "million" things to prices (which is great!)

     0.6.0-3:
            -Added bells to "cannot affords" and "no requirements".
            -Fixed more bugs (qlstudio edit this, I have no idea what else you fixed).

     0.6.0-2:
            -Fixed a variety of bugs (thanks qlstudio).
                -Fixed the OverflowError for the buildings themselves
                -Checked for conflict with all the "-illion"'s, no conflict (so far).

     0.6.0-1:
            -Further added to the "million", creating "billion" to "quintillion", which should delay the OverflowError further (most annoying error so far).
            -Fixed the "million", and now there should be no conflict.
    
     0.6.0:
            -Implemented a "millions" thing, which should prevent (or at least delay) the OverflowError
    
     0.5.3-3:
            -Fixed two main bugs, the timevar and totalclicksvar bugs.
     
     0.5.3-2:
            -Fixed a variety of bugs. (HOORAY FOR BUG FIXING)
     
     0.5.3-1:
            -Fixed the savefile (YAY)
            -Implemented an upgrades button
            -Started on stats
     
     0.5.2:
            -Added a colour changed on click of +Money Button (Yes, it's addictive)
            -Fixed Gold Button
            -Fixed a bug in which more than one gold would make a sticky button. (Only allowed one gold to exsist at a time)
            -Doubled Chance of finding Gold.
            -Working on a Stats Menu.
            
     0.5.1:
            -Fixed the upgrades button (it makes the main screen wider instead of creating a new window)
            -Starting work on background colours
            -Still fixing gold button (the previous update was a lie)
            
     0.5.0:
            -Probably fixed gold button
            -Added new upgrade for Money Printers (Costs $7,777,777)
            -Made a new upgrades button (less crowding)
            
     0.4.3:
            -Shrunk the code down by 100+ lines
            -Changed gold appearances to randint function
            -Fixed a bug in which upgrades don't change MPS
            
     0.4.2:
            -Added gold button (increases balance by MPS*50)
            -Fixed most of the bugs (PyCharm!)
            
     0.4.1:
            -Downloading images is no longer required (Thanks to Git Hub for Desktop)
            -Simple animation added. (To be improved)
            -Increased +Money Size (Easier for touchscreen users.
            -Bugs fixed (Prior to this upadate)
            -Made the change log easier to read. (Order Reversed)
            
     0.4.0:
            -Added new building, Sharemarket Crash (969 MPS, costs $42,000)
            -Changed the names of the upgrades (less bland)
            -Ironed out a LOT of the bugs
            -Changed the code for upgrades AGAIN
            -Added background

     0.3.0:
            -Added a new upgrade, Better Click Boost (Costs $200,000)
            -Changed the code for upgrades

     0.2.1 (not to be confused with 0.2-1): Fully fixed the savefile, and fixed bugs.

     0.2-2: Partially fixed the savefile.
    
     0.2-1*: Changed the save system so that it included an external savefile.
    
     0.2.0*: Added a save system (which needs fixing!), and a new building: Counterfeit Company (321 MPS, costs $9,001).

     0.1.3: Fixed a bug in which some labels and buttons don't update.

     0.1.2: Added placeholders for the Tkinter window.
    
     0.1.1: Changed from pack and grid to only grid, saving space and making the whole code work
    

    
Things to add in the future:

    *New Upgrades
        -Bank Robbery
        -New Currency
        -Fort Knox Heist
    *Make a game server (Play on any device)
    *Make imports - DONE!
    *Add pictures - DONE!
    *Make the game more interactive
    *Do some html stuff (i.e. make this game browser-based)
    *Automatic savefile converter? - DONE!
    *Change upgrades (still way too inefficient)
    *Add Progressbar (See #26)
    
    
Cyber-Shadow's to do list:

     Project: Visual Overhaul!
          New background. (Due to copyright claims... (Jokes))
          Probably pictures for all purchasable assets.
          Stopping deforamation of program
          More Animations
          Removing all ugly default grey.
          Remove crapping moving money animation. (R.I.P 2 hours)
          Make a Notification Box that contains notifications like: Not Enough Money! & other simple notifications. (This Will be inplace of the Moving money animation.
          
     Bug test marathon & Management of user bug testing. (Support Email?)
     
     Temporary boosters?
     
     
     
     
     
     
