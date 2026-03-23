# ⭐ Project Star Rework ⭐
Welcome to Project Star Rework GitHub.

We are dedicated to reviving and completing the lost vision of the original Super Mario Galaxy E3 2006 demo. Following the cancellation of the project by the original team (SPG64), we have stepped in to finish what was started.

Our Mission:

- Complete the reimagining of the 2006 E3 build.

- Squashing legacy bugs and refining gameplay.

- Optimizing for Wii U (and potentially original Wii hardware).

Join our Discord Server to follow our development updates and help us bring this piece of gaming history to life!

# 📒 Installation Guide

## Requirements :

- An original copy of Super Mario Galaxy (disc)
- A Wii with Homebrew Channel (real)
- A SD card or USB Drive
- CleanRip
- Files to download from the "releases" on this GitHub
- Dolphin or Riivolution (currently not supported)

# Step 1 - Wii Modification

Your Wii must have the Homebrew Channel installed on it. If this is not the case, there are many videos on the internet that explain how to do this. 
We strongly recommend that you visit https://wii.hacks.guide/, as this site explains the method very clearly. 

When modifying your Wii, it is important to install protection against bricking (meaning that your console becomes temporarily or permanently unusable in most cases due to improper handling). 
PriiLoader or BootMii (installed as boot2) can protect your console from this. 
If you cannot set BootMii as boot2, set PriiLoader. In most cases, it is best to set both, but if this is not possible, set at least PriiLoader. 

I know that explaining this quickly may seem unclear, but I think https://wii.hacks.guide/ will explain it much better than I can.

# Step 2 - Format the USB Drive or SD Card to FAT32

Before doing anything, we will first format your SD card or USB drive.

WARNING: this is very important, formatting will erase everything on your device. If you have photos, videos, or other important files on it, transfer them to your computer beforehand, as formatting will erase everything.

You must format it from your PC.

If you have Windows:

Open Explorer -> This PC -> right-click on the flash drive or SD card -> Format, select FAT 32 and Allocation unit size: default -> click Start.

If you have macOS:

Open Disk Utility -> in the left column, select the USB key or SD card -> click Erase -> select MS-DOS (FAT) (this is FAT-32) and Master Boot Record (MBR) layout -> click Erase

If you have Linux (Ubuntu, Debian, Mint, or other) 

Install GParted and launch it -> Select the USB key or SD card -> in the Device menu -> Create Partition Table -> msdos -> right-click -> New -> Type fat32 -> Apply

# Step 3 -  CleanRip

Download CleanRip from https://oscwii.org/library/app/CleanRip.

Unzip the file and place the apps folder in the root directory of your SD card or USB drive.

Insert the SD card or USB drive into your Wii.

From the homebrew channel, click on the CleanRip icon and press “Start.”

CleanRip will ask you to choose a device, depending on what you have connected to your Wii, either the SD card or the USB drive.

The software will then ask you to set several options. Here is what you need to enter:

New Device → YES

Chunk Size → 1GB or 2GB
Either one works, it doesn't matter.

Dual Layer → NO

File System → FAT32

Next, insert your Super Mario Galaxy disc. The software will automatically copy the disc's contents.

This may take a long time, around 10 to 20 minutes.

CleanRip may create several files on your USB drive or SD card (such as part1.iso, part2.iso).

If this happens, you can use Wii Backup Manager on your PC. If there is only one file, there is no point in doing this.

Downloadable from here: https://wiibackupmanager.co.uk/downloads.html

Start the software and put the files that CleanRip created in it -> convert them to ISO or WBFS

and then you've got it!

# Step 4 -  Dolphin

Open Dolphin and click on the Config icon (the one with three lines and dots on it), go to the Paths option and click on Add. Put your Mario Galaxy backup that you made earlier in a new folder, 
place this folder where you want, then select the location where your folder is in Dolphin, close the window, and you should see SUPER MARIO GALAXY in the Dolphin menu.
<img width="779" height="104" alt="image" src="https://github.com/user-attachments/assets/92c87937-52a9-4dce-badb-2c8fb820c30c" />

Right-click on it and click on Properties.
In the window, go to Filesystem.
You should see everything that is in your Super Mario Galaxy backup. Right-click on “Disc” and click on Extract entire disc.
and select the folder where your Mario Galaxy backup is located, or another folder of your choice.

Unzip the ZIP archive you downloaded from GitHub and go to "project-star-world-continued-interest-master\source_fs\files" COPY EVERYTHING in the files folder to the location where you extracted the files with Dolphin earlier in the "files" folder.

Then open Dolphin, click on the File option at the top and select Open User Folder -> then go to the GameSettings folder and copy everything in “\project-star-world-continued-interest-master\asm” to the GameSettings folder in Dolphin.

Thenclick on the Config icon (the one with three lines and dots), go to the Paths option and click Add. Select the folder where you extracted “disc,” go to sys and click Add.
REMOVE the folder we added previously, otherwise we will have two SUPER MARIO GALAXY icons.

Then close the window, right-click on SUPER MARIO GALAXY - Properties and select Patches -> If you have done everything correctly, you should see a list of patches to apply. We recommend selecting everything EXCEPT Press B instead of A to select pause menu option (as it makes the game unplayable). we recommend applying the rest unless you want to play the original Super Mario Galaxy but with lots of bugs since we replaced some files earlier.

⭐Now i can FINALLY say, You completed everthing in this guide, click on the game icon and enjoy !⭐

If you have had any issues with anything, please let us know in “issues” on this GitHub page. I would be happy to help you.

# 🛠️ The team / Credits
TechGuys TechSpot & Games : Game tweaker
RTGgamerz306 : Game devlopper
JustAlex : His Good Egg Galaxy recreation is used in game
GoldyBer : His Star Get theme recreation is used in game
Me (DaCat) : Github repository and Discord server (i guess)

## I need your help, If you feel able to help me with this project, it would be a pleasure (I'm really very bad at SMG modding)

# 🛠️ Original Project Star World Team / Credits

galaxymaster2007

Galaxy Master

Mr-SiliconGraphics

mariomadproductions

SPG64

togemet2

saladplainzone

Captain Byte

SimonTime

seeingvoices

Marionova

Hiccup

EmmaNerd

blameitontherobot

Zyphro

SY24

# 💬 Join us on Discord !
We have a Discord server, join it to find out the latest announcements about the game and chat with the community.
https://discord.gg/dafjsS62eZ
