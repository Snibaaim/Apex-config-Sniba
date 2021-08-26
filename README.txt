# APEX CONFIGS & TWEAKS

# Autoexec
1. Go to the games directory. Steam: (C:\Program Files (x86)\Steam\steamapps\common\Apex Legends\cfg) - Origin: (C:\Program Files (x86)\Origin Games\Apex\cfg)
2. Create a new file called "autoexec.cfg" (without the Quotation marks).
3. Paste everything from [autoexecSniba](https://raw.githubusercontent.com/Snibaaim/Apex-config-Sniba/main/autoexecSniba.cfg) in it.
4. Save and make the file read-only (Right click the file, select properties, check the read only box).

Steam:
1. Right click the game in steam, hit properties > General > Launch options.
2. Add "+exec autoexec" (without the quotation marks or .cfg at the end).

Origin:
1. Right click on the game inside of Origin and go to "Game Properties".
2. Switch to the "Advanced Launch Options" Tab.
3. Add the Command line argument "+exec autoexec.cfg" (without the quotation marks).


# Videoconfig
1. Press Win+R while you are on your desktop.
2. Paste this inside the Run box: "%USERPROFILE%\Saved Games\Respawn\Apex\local" (without the Quotation marks)
3. Open up the Videoconfig.txt with Notepad, VSCode, or your preferred text editor.
4. Replace everything in it with the code from [videoconfig](https://raw.githubusercontent.com/Snibaaim/Apex-config-Sniba/main/videoconfig.txt)
5. Save and make the file read-only (Right click the file, select properties, check the read only box). (also make sure your Origin Cloud Sync is disabled in the origin settings)


# Consistant frame capping
Use RTSS for framerate caping over build-in game engines caps. RTSS is the best in frametime consistancy.
Do not use a higher cap value than 190 FPS since the game will introduce stutter (its a apex bug)
You can download RTSS [here](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html)

# SUPERGLIDE FILES
1. To use my superglide superglide cfg for easier superglides, download all 3 superglide cfg's [superglide1.cfg](https://raw.githubusercontent.com/Snibaaim/Apex-config-Sniba/main/superglide1.cfg), [superglide2.cfg](https://raw.githubusercontent.com/Snibaaim/Apex-config-Sniba/main/superglide2.cfg], and [superglide3.cfg](https://github.com/Snibaaim/Apex-config-Sniba/blob/main/superglide3.cfg).
It's very important that these superglide cfg's are in different files and not in the same one, or else it won't work.

Now on to how to install them

Steam:
1. Right click the game in steam, hit properties > General > Launch options.
2. Add "+exec superglide1" (without the quotation marks or .cfg at the end).

Origin:
1. Right click on the game inside of Origin and go to "Game Properties".
2. Switch to the "Advanced Launch Options" Tab.
3. Add the Command line argument "+exec superglide1.cfg" (without the quotation marks).

