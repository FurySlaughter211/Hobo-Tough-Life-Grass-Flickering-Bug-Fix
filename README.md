Instructions to set up the mod: 

Step 1: Install BepInEx



1. Download **BepInEx 6 IL2CPP** from:
   https://builds.bepinex.dev/projects/bepinex_be


2. Download the **Unity IL2CPP** version (Windows x64)
   (You'll find it under Artifacts.)


3. After the download is complete you have to extract the ZIP into your game folder:

   C:\Program Files (x86)\Steam\steamapps\common\Hobo Tough Life\

   If you're not comfortable with copying the files around you can also:

   1. Press Windows + R
   2. Type cmd (this will open your terminal)
   3. A black box should appear
   4. If the ZIP file is currently in downloads you can copy paste this: cd Downloads
      If it's not just replace Downloads with the name of the current location
   5. Then copy paste this while keeping the quotation marks as shown and replacing the [variable] with the filename:
      tar -xf "[variable].zip" -C "C:\Program Files (x86)\Steam\steamapps\common\Hobo Tough Life"

      If you don't have the game over Steam just replace the path with your own game path


4. Your game folder should now have a BepInEx folder


5. Now run the game once and close it (If a black box pops up it's working)
   This will make BepInEx create necessary files

6. Navigate to the Hobo Tough Life\BepinEx\plugins folder and drop the GrassBugFix.dll in there
