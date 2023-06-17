# Just Shapes Beats Level Loader Mod

## Requirements

#### Unity 2019.4.28f1 (the only version of Unity supported, others won't work).
#### Just Shapes and Beats (1.6.31 or lower).
#### [BepInEx](https://builds.bepinex.dev/projects/bepinex_be) installed.

## Mod Installation 

1. Download [`BepInEx`](https://builds.bepinex.dev/projects/bepinex_be) Unity (IL2CPP) for Windows.
2. Unpack everything to the game folder, you can open it via steam. 
<sub> 
Don't close the folder, you will need it soon <br />
Go to Steam => Library => Right click on the game => Manage => Browse local files
</sub>
3. Launch the game and wait for the intro. Close the game.
4. Download the mod files.
> You can find them in the releases tab
5. Import the `Level Loader.dll` into the plugins folder.
> Open your game folder and go to BepInEx folder => plugins
6. Launch the game again and wait for the intro. Close the game.

## Level conversion
1. Open Unity and drag `Level Bundler.unitypackage` into the inspector window.
2. A window will open, click `Import`.
3. Import your level file and the music file you used in the editor.
> json and mp3 files
4. The Xoggas field on the toolbar will appear, click it and select a Level Parser option.
5. Click `Choose JSB directory` and find your game folder.
6. Click `Create Folders` button.
7. Select the `Song Name` field and write a level name here. 
> Use only capital letters
8. Select the `Artist Name` and write an artist name here.
9. Drag your level file into the `Normal Level` and `Hardcore Level` fields. 
> If you want to make different levels for normal and hardcore you will need to create two separate files
10. Drag the song file into the `Song` field.
11. Press the `Export` button.
12. Wait until processing is complete.
13. Click `Laucnh JSB` button.
14. Now you can open the `Playlist` and find your level in the end.
