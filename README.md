#Conan Exiles Mod Organizer
This application helps organize and prepare mod files for use in the Xbox PC application, specifically designed for Conan Exiles. It simplifies mod management by generating two essential lists:

Mod List: A list used for loading mods in the game, including specific paths marked with an asterisk (*).
Mod Serve: A list used for loading mods on a server, with paths separated by commas (,).

#Features
Disk Selection: Allows you to select the disk where the game is installed, whether C, F, or another. This ensures that the generated paths are correct for the specific location of the game.
Automatic List Generation: The application organizes the selected mods and automatically generates two files:
modlist.txt: Contains the paths for the mods in the proper format for the game.
modserve.txt: Contains the paths in the correct format for the server.

#Example of a Mod List

*ConanSandbox/Mods/AdvancedGliders.pak
*C:/XboxGames/Conan Exiles/Content/WindowsNoEditor/ConanSandbox/Mods/UIMod_Hosav.pak

#Example of a Mod Serve

C:/XboxGames/Conan Exiles/Content/WindowsNoEditor/ConanSandbox/Mods/StylistPlus.pak,
C:/XboxGames/Conan Exiles/Content/WindowsNoEditor/ConanSandbox/Mods/IMMERSIVE_ENTERTAINERS.pak,

#Usage
Select Mods: Drag and drop your mod files or manually select the mods you want to load.
Select Disk: Choose the disk where the game is installed (C, F, or specify another if necessary).
Automatic Generation: The application will automatically generate the modlist.txt and modserve.txt files in the appropriate locations.
Download Files: Once generated, you can download both files to use directly in the game or on the server.

#Requirements
-Operating System: Windows
-Xbox PC application installed with Conan Exiles
-Ability to access the game installation path.
