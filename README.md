# Trick Saber
![](Resources/LogoSmall.png)

This mod allows you to perform various tricks like spinning / throwing your sabers,
hence the name "Trick Saber".
*Currently not compatible with DynamicOpenVR.BeatSaber (the base mod DynamicOpenVR is fine tho)*

[Documentation](https://tonimacaroni.github.io/TrickSaber-Docs/)

## Installation
1) Download the latest release from here (the zip file): https://github.com/ToniMacaroni/TrickSaber/releases
2) Make sure you have installed the dependencies listed in the release
3) Drop the zip contents into your Beat Saber directory

**If you use index controllers you HAVE to choose a compatible SteamVR binding**  
*Take a look [here](https://www.youtube.com/watch?v=e3NI0mjVM0s) on how to do that*

## Usage
*Buttons can be configured*

For throwing the saber:
1) Throw your controller (not literally)
2) Hold the trigger button to release the saber
3) Release the trigger button to pull the saber back to you
   (It does take a little bit of practice)

For rotating the saber in your hand:
* For left saber: move your left thumbstick to the left
* For right saber: move your right thumbstick to the right

## Configuration
You can configure most of the Plugin by going into the "Mods" tab on the left panel in Beat Saber and selecting "TrickSaber".

For more stuff and in-depth explanation see [Configuration](https://tonimacaroni.github.io/TrickSaber-Docs/Configuration.html)

**Preview: https://www.youtube.com/watch?v=6xxpupYYjoQ**

## Building
- Copy all the files in your Beat Saber install to `TrickSaber/TrickSaber/Refs`
- Install the [.NET 7.0 SDK](https://dotnet.microsoft.com/en-us/download) if you do not already have it installed
- Navigate to `TrickSaber/TrickSaber` and run `dotnet build`
- Copy TrickSaber.dll to the `Plugins` folder in your Beat Saber install
