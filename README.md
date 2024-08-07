# APC-mc-modpack
### Minecraft Modpack for the APC Minecraft Server

## Disclaimer:
This Git REPO is designed to privately distribute these mods to a small group of people to play on our private server. 
None of these mods are developed by me and all rights belong to their original creators! Pls dont sue me thx

## aeonull's guide to setting up Modded Minecraft

## Step 1: Update your Java!!
(pls do this)
https://www.java.com/en/download/

## Step 2: Install Forge Mod Loader
1. Download the FML installer at this link. Be really careful NOT to fall for fake download buttons. Wait ~5s and press 'skip' in the top right. Link: https://adfoc.us/serve/sitelinks/?id=271228&url=https://maven.minecraftforge.net/net/minecraftforge/forge/1.19.2-43.3.0/forge-1.19.2-43.3.0-installer.jar
2. Run this .jar file. Use the installer to install for client. More than likely the default directory is what you want.
3. Open the Minecraft Launcher, and next to the PLAY button, select forge. Launch the game at least once and make sure it doesn't crash!


## Step 3: Download the mods! Two ways to do this:


### Method 1 (automated install):
In this method, we are going to clone the GitHub repository into the Minecraft mods installation folder. This will install all the mods for us!

1. Make sure you have Git installed on your computer: 
https://git-scm.com/download/win
2. Download the update_or_install_APC_modpack.bat from the #minecraft-info channel on discord.
3. Close out of any file explorer windows, and make sure your game is fully closed.
4. Run the .bat file from step 2 to install the latest version of the modpack!
5. Assuming no errors, you should be all set to start playing!

If you have issues with this, you can also run the same commands in command prompt yourself:

2. open 'Command Prompt' (press windows key, type 'cmd', hit enter)
3. Run the below commands (recommended one line at a time):

(The below commands are correct and intentional, modifying them in any way is not recommended! Include the . in the last command or it won't work!)
```
RD /S /Q %HOMEPATH%\AppData\Roaming\.minecraft\mods
MD %HOMEPATH%\AppData\Roaming\.minecraft\mods
cd %HOMEPATH%\AppData\Roaming\.minecraft\mods
git clone https://github.com/aeonull/APC-mc-modpack .
```

4. If no errors, nice! Launch the game, tune the performance using the various graphical and RAM settings, and connect to the server!



### Method 2 (manual install):
If you have issues with the above method or don't want to install Git, you can also install the mods manually:

1. On your desktop, use Windows + R or type 'Run' into the search bar
2. type %appdata% and hit enter
3. Look for .minecraft
(Consider making a shortcut to this folder! You will likely be coming back here.)
4. Open the mods folder! This is where you will add your mods in the next step.

5. Click the green Code button on the upper right hand corner of this page
6. Click download .zip
7. This will download all the mod files into a big zip file for you!
8. Unzip this file
9. Look inside the unzipped folder, move all the files from this folder into the mods folder we opened in step 3!

Final Step: Launch the game, hope it doesn't crash! You might consider adjusting your settings, adding performance mods like Optifine, or shaders to enhance your visuals. Happy gaming!
