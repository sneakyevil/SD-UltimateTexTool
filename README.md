[![Current Release](https://img.shields.io/github/v/release/sneakyevil/SD-UltimateTexTool?label=Current%20Release&color=red)](https://github.com/sneakyevil/SD-UltimateTexTool/releases/latest/download/Release.zip)
![Downloads](https://img.shields.io/github/downloads/sneakyevil/SD-UltimateTexTool/total?label=Total%20Downloads&color=red)
![Latest Downloads](https://img.shields.io/github/downloads/sneakyevil/SD-UltimateTexTool/latest/total?color=red&label=Latest%20Downloads)

## Preview
![image](https://github.com/sneakyevil/SD-UltimateTexTool/assets/29150970/1bdfd347-a556-419f-a46d-6dc2c2dbfc34)

> [!CAUTION]
> This tool uses TextureScriber that was shipped with **Triad Wars**, as that tool is closed-source this GUI Tool generates XML that pass it to that tool to generate new perm.bin/temp.bin based on loaded file.
> 
> Modifying textures that contain other data then textures will not exist in new export files, so use it with caution!
> 
> This could be solved in future by me or someone else by writing tool that modifies original perm.bin file texture information based on new perm.bin

## Instructions for usage
- Note: This is just tool for import pre-existing exported (Perm.bin) files or importing (Perm.bin) files not for extracting them directly from .big files.
1. Under Project you select Import (Perm.bin) and select the one which has also matching (Temp.bin) file.
2. After everything was correctly imported you should see all textures under Resources and their sizes.
3. You can now right click any resource to replace it for another .png file (The size must be exactly the same).
4. If needed you can also drag the resources around to sort them out differently in exported (Perm.bin) if needed!
5. I highly recommend selecting `Use Resource UID`, because when exporting texture the UID will be based on original (Perm.bin) file which is required otherwise the game will not load it.
6. Under Texture you select Export, when everything was successfully exported you should be able to select Open Folder to browse the exported (Perm.bin & Temp.bin) files.
7. Now if you want to use the modified textures you need: https://github.com/SDmodding/FileRedirector (Read installation process).
8. After installing the FileRedirector you now have folder inside game called `RedirectorData` that is important where you place those files! Placing those exported textures files are not straight forward just placing them in that folder, you need to place them in same path format as they were exported ie. `Vehicles\Data\Vehicles_New` -> `RedirectorData\Vehicles_New`.
9. If you done everything correctly, the textures should be replaced after booting up game.
