This text file contains responses to commonly asked questions in #usw-support of the TrixyBlox discord server
If you find the response you're looking for, copy the response from **ANSWER** down to right above the === bar.

Created by firestranded#1038, Kage#7892, and vagueadvice#7710

=================================================================================================================================

tags: resourcepack, bars
**ANSWER**

Bars appear like that when you don't have the __resourcepack__ installed correctly

**__If you're on a server:__**
If you're on a spigot/paper server, then install the server loader plugin from https://www.spigotmc.org/resources/usw-server-loader.106454/ and put it in the "plugins" folder of your server. 

If you're not on spigot/paper then make sure the link corresponding to your player limit is in the resourcepack section of your server.properties file.
> 10 Players: http://resourcepack.host/dl/6OYRoGeXyU7EdAgEtK9gjnQlhUp3H0DY/USWRP-10-PLAYERS.zip
> 25 Players: http://resourcepack.host/dl/nIJPWxlIiEJxE8aEPTaNqbeQhFEU4LLq/USWRP-25-PLAYERS.zip
Then, restart your server.

If you're on a LAN server, make sure everyone downloads the resource pack corresponding to your player limit above, and put it in (Pause Menu -> Video Settings -> Resource Packs -> Open Folder)

**__If you're on singleplayer:__**
The resource pack should've come embedded in the world. Try holding F3+T to reload resource packs. If that doesn't work, try
installing the resourcepack manually from:

> 10 Players: http://resourcepack.host/dl/6OYRoGeXyU7EdAgEtK9gjnQlhUp3H0DY/USWRP-10-PLAYERS.zip
> 25 Players: http://resourcepack.host/dl/nIJPWxlIiEJxE8aEPTaNqbeQhFEU4LLq/USWRP-25-PLAYERS.zip

To install it, go to (Pause Menu -> Video Settings -> Resource Packs -> Open Folder) and drag the .zip file in there.

=================================================================================================================================

tags: location, place, where
**ANSWER**

If you're looking for a specific location in the USW world, try looking at the
USW Cartography website! (https://sites.google.com/view/usw-cartography/home)

=================================================================================================================================

tags: extract, resourcepack
**ANSWER**

Make sure you do not extract the resource pack!
Simply put the resource pack in your resourcepack folder at: 
(Pause Menu -> Video Settings -> Resource Packs -> Open Folder)

Then enable it! You may have to hold F3 and press T to reload your resource packs.

=================================================================================================================================

tags: extract, datapack
**ANSWER**

**__Only do this if your datapack is outdated or if there is an error when you join the world!__**

Make sure you do not extract the data pack!
Simply put the data pack in your datapack folder at (World Folder > Data Packs), deleting the old one if there is one already there.

**If you don't know how to locate your world folder**, it's located in your "__**saves**__"  folder.

The easiest way to find your saves folder is in the minecraft launcher.
> Open the Launcher, then go to (Installations -> Latest Release (or whatever profile you're using) -> Folder Icon to the Right -> Saves)

=================================================================================================================================

tags: spectator, head, cheats
**ANSWER**

You're in spectator mode!

**__If you're on a server:__**
In your server console type ``op username`` where username is your minecraft username, then in chat type /gamemode survival.

**__If you're on singleplayer:__**
Go to (Pause Menu -> Open to Lan -> Cheats ENABLED -> Done) then in chat type /gamemode survival.

=================================================================================================================================

tags: download
**ANSWER**

Here's a video tutorial for downloading the map!

https://cdn.discordapp.com/attachments/1046141629070848070/1046486252163174501/USW_Basics_and_Download.mp4

=================================================================================================================================

tags: server, host
**ANSWER**

The USW team recommends server.pro on the medium tier, but it's possible to get USW working on the free tier of Aternos.

=================================================================================================================================

tags: saves, folder, .minecraft
**ANSWER**

If your worlds aren't properly showing up in game, that means you haven't properly put the world in the saves folder.

The easiest way to find your saves folder is in the minecraft launcher.
Open the Launcher, then go to (Installations -> Latest Release -> Folder Icon to the Right -> Saves)

Make sure your world folder is __**unzipped**__ before putting it in the saves folder!

**__Unzipping on Mac:__**:
Double click the zipped file.

**__Unzipping on Windows:__**:
Right click the zip file and select "Extract All".

=================================================================================================================================

tags: datapack, tampered
**ANSWER**

Before trying any of these, please note that USW was not built to be run on forge servers.

Forge servers often cause problems that are not USW's fault and we cannot help you with.

Please try using Vanilla or Fabric.

**__This usually means you have a bad datapack.__**

If you're on a server:
> First try deleting the advancements folder of your world.
> Make sure your server is off before removing it, then start it up again after doing so.

**__For both servers and singleplayer:__**

If the above step hasn't worked and you haven't made any progress on the world, it's most recommended to just reinstall the world completely.
If you haven't made progress, then refer to the guide on updating your datapack below:

> First, download the USWDP.zip (ultimate survival world data pack) file from the patreon link that corresponds to your player limit (https://www.patreon.com/TrixyBlox/posts)
> 
> After you've downloaded the file, go into your (World Folder -> Datapacks) 
> 
> Delete the already existing USWDP.zip File and Replace it with the newly downloaded version.

**If you don't know how to locate your world folder**, it's located in your "__**saves**__"  folder.

The easiest way to find your saves folder is in the minecraft launcher.
> Open the Launcher, then go to (Installations -> Latest Release (or whatever profile you're using) -> Folder Icon to the Right -> Saves)

=================================================================================================================================

tags: server-loader, uswdp, datapack, resourcepack
**ANSWER**

The Server-loader.jar and the USWDP.zip files are circumstantial files that you might not need.

**__USW-ServerLoader.jar:__**

The server-loader.jar file is a file for Paper & Spigot servers. They're designed to install the USW resource pack easily on these servers. If you are not using paper or spigot servers, you can ignore this file. If you are using paper and spigot servers and would like to learn how to use the file, Step 5 of the guide in the post shows how to do it.

**__USWDP.zip:__**

The USWDP.zip file is the datapack for the Java version of the world. This is for people who need to update their existing datapack. If you are only looking to install the world, you can ignore this file, since the world file already has the datapack and resource pack in it.

=================================================================================================================================

tags: memory, ram, lag
**ANSWER**

If you're facing a lot of lag in your USW on java, you might need to allocate more ram.

First, you need to go onto the Minecraft launcher. Then click on installations. Then, you will click on the installation you are using for minecraft. (If you're just playing vanilla this should be the latest release)

Then, you need to click on more options on the lower right. 
You should see something that says Java Arguments and some text below it. You're looking for the text that says  -Xmx2G -XX:
It should be in the front. In order to allocate more RAM, you need to change the 2 infront of the G. You should allocate around 1/4 of your total computer ram, so it should be 3 for people with 8gb of ram, 4 for people with 16gb of ram, and 8 for people with 32 gb of ram. After you changed the number, you want to hit save and try playing the world again.

=================================================================================================================================

tags: black, texts, vanilla-tweaks
**ANSWER**

Black text appears when you're using Vanilla Tweaks.

USW currently isn't compatible with Vanilla Tweaks, so you'll have to remove it.
