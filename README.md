DV-DS-iDTech1 ["Aetherius" iDTech1 Packages - Allows "Aetherius" to run with other iDTech1 games]

- Allows you to properly run "Aetherius" in Doom 1 mode, as it adds some sprites/actors that don't appear normally in Doom 1 like the Super Shotgun, Chaingunners, etc. It will also add a custom intermission map for Episode 4: Thy Flesh Consumed.

- Allows you to run "Aetherius" with other games on the Doom engine, such as Heretic, Hexen & Strife. However only Flora is playable currently in these modes. Corvus, Baratus, Daedolon, Parias, and StrifeGuy aren't available as classes at this time, but might be implemented at later dates. :P

HOW TO INSTALL / RUN / ETC:

  [Note: if you have downloaded this as a file off the repository's site, the main folder[s] below inside the archive file will have the postfix '-master' appended onto them [i.e. "DV-DS-idTech1-master"]. Either consider that postfix in the folders for the command lines below, or rename the folders inside to remove the '-master' post fix. I usually don't use zips for testing, but I use a git client to directly upload the revisions of these repositories to Github and to download them as well, so they don't append '-master' to the foldernames on my end.]

 - Important - Make absolutely sure you got DV-DS-ComboPack [@ https://github.com/LordMisfit/DV-DS-ComboPack ] working right before you do anything here. Refer to that repository's README.md file for more information.

 - Installing 1 - Make sure you unzip the entire "DV-DS-idTech1" folder inside the zip file to your designated GZDoom folder. Do not try to install the subfolders within into "DV-DS-ComboPack" or into your main GZDoom folder, or you've done flapped it up and have to do everything up to this point on both repositories over again. :V
 - TL;DR: So basically make sure "DV-DS-ComboPack" & "DV-DS-idTech1" are seperate subfolders in your main GZDoom folder. :P

 - Running - 1. There is no launcher packed for use with DV-DS-idTech1, you'll have to rely on command lines for now. My general method is to create a batch [.bat] file and name it something you'll remember. Remember you can right click a .bat file and "edit" them to change the command line used inside.

 - Running - 2. To run Heretic w/ "Aetherius" Command line: "start gzdoom.exe -iwad heretic.wad -file "DV-DS-ComboPack" "DV-DS-idTech1/Heretic" +hud_scale 0 exit" 
 - Note: "Aetherius" highly recommends using "hud_scale 0" for HUDs, so keep that in mind if you play this and go back to a different mod and your hud looks odd, you'll likely need to enter "hud_scale 1" or so in your console when you play said other mod. :P
 - Note: Hexen's patch can also be loaded with Heretic if you want to use the console to "summon" the monsters from Hexen in Heretic. Just add "DV-DS-idTech1/Hexen" in the above command line BEFORE "DV-DS-idTech1/Heretic" to do so.
 - Note: Putting "start" and "exit" around a command line makes the CMD prompt that pops up immediately disappear so you don't have to manually close the window after the command runs. However if you're making a shortcut that's not a .bat file, you don't need "start" or "exit" in those command lines.

 - Running - 3. To run Hexen w/ "Aetherius" Command line: "start gzdoom.exe -iwad hexen.wad -file "DV-DS-ComboPack" "DV-DS-idTech1/Hexen" +hud_scale 0 exit" 

 - Running - 4. To run Hexen: DeathKings of the Dark Citadel w/ "Aetherius" Command line: "start gzdoom.exe -iwad hexdd.wad "DV-DS-ComboPack" "DV-DS-idTech1/Hexen" "DV-DS-idTech1/HexDD" +hud_scale 0 exit" 

 - Running - 5. To run Strife w/ "Aetherius" Command line: "start gzdoom.exe -iwad strife1.wad -file "DV-DS-ComboPack" "DV-DS-idTech1/Strife" +hud_scale 0 exit" 
