GMAPI is a library for Game Maker DLL developers, that gives the possibility of accessing the game's resources right from the DLL! What it currently features:
  * Ability to use the GML functions within your DLL.
  * Possibility to modify or even register a new GML functions for the game (increases external calling efficiency)
  * Direct access to the game resources, such as:
    * Sprite, background and font bitmaps
    * Sound files
    * Local and global variables/arrays
    * Built-in variables/properties (e.g room\_speed, fps)
    * Internal game structures (e.g. the one that holds GM instance's data)
    * Game's Direct3D interfaces (IDirect3D8, IDirect3DDevice8, IDirect3DTexture8)

In the current version you have a possibility to access sprites, backgrounds, surfaces, sounds, scripts, particles, fonts and some other data, such as e.g. game's Direct3D interfaces, window handles, GML functions, GM version...