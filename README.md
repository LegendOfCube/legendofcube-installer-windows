# Installer for Legend of Cube

See [main repo](https://github.com/LegendOfCube/LegendOfCube-Game) for more information about the game.

## Creating the Installer

1. Install Inno Setup if not already installed
	- Download from: http://www.jrsoftware.org/isdl.php (version 5.5.5 as of writing)
2. Build project in release mode
3. Move files from `bin\x86\Release` in project folder to `install-files`
    - Only `LegendOfCube.exe` and `Content` is required as of writing
4. Open `installer-script.iss` with Inno Setup Compiler
5. Press the "Compile" option in the toolbar
6. If succesful, an installer can be found in the folder `latest-version`
