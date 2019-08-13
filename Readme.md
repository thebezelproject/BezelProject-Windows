#The Bezel Project - Bezel Pack Utility for Windows

Things you should know before using
-----------------------------------

This utility will provide the ability to download bezel packs to be used for
native MAME, various systems within Retroarch, (on Android, Playstation Vita,
Switch, Wii U and Windows), and RocketLauncher.

If you have custom, existing RetroArch core cfg files, this app may not work as
written because it must assume standard cfg names. The way to enable support for
your custom names is to run the application to the initial GUI screen, then exit
the app. This will have caused the app to create its ini file in the
installation directory. Edit the 'Bezel Project.ini' file, then go to the [Maps]
section. There you will see the predefined RetroPie system names and the
associated cfg files names for that system. Either add your custom cfg name to
the list of files, or replace the existing names with your own. Make sure to
separate each cfg filename with a comma, then save any edits and exit your edit
session. Restart the app and it should pick up your edits.

These bezel packs will only work if the ROMs you are using are named according
to the No-Intro naming convention used by EmuMovies, HyperSpin, and
RocketLauncher.

This utility provides a bezel pack for various systems and includes a PNG bezel
file, and, if needed, a configuration file for every ROM for that system.

The utility will also update the required Retroarch cfg files for the emulators
located in the ...\\Retroarch\\configs directory. These changes are necessary to
show the PNG bezels with an opacity of 1.

Periodically, new bezel packs are completed and you will need to run the utility
update option to download the newest version to see these additional packs.

\*\*NOTE\*\*  
For the Retroarch MAME bezels, the pack is inclusive for any roms located in the
arcade/fba/mame-libretro rom folders.

\*\*Note for Retroarch installations\*\*  
This app only supports local relative paths for the config and overlays
directories (the default). If you use full paths for these two directories in
the Retroarch.cfg file, this application will not work with your Retroarch
installation.

Overview
--------

This app provides an interface to The Bezel Project files that reside on GitHub.
This app analyzes the code contained in the original RetroPie script and adapts
it to a Windows based native MAME, Retroarch (also on Android, Nintendo Switch,
Nintendo Wii U and Playstation Vita), and/or RocketLauncher installation.

-   Note: the app allows skipping modification of any existing customized
    Retroarch platform cfg files.

-   Note for reset of 'Bezel Project.ini' file

>   If you have need or are asked to delete your apps's ini file, be aware you
>   will lose certain settings if you have already used the app to install any
>   bezel packs. If you want to save this information so it can be inserted in a
>   new ini file, follow the following steps.

1.  Make sure the application is not running.

2.  Save all lines from the Settings, MAME_installed and
    RocketLauncher_installed sections.

3.  Delete the 'Bezel Project.ini' file.

4.  Run the application, then exit without performing any actions.

5.  Edit the ini file, then insert the lines saved from step 2 above, then
    continue as normal.

-   Note for Retroarch installations:

>   This app only supports local relative paths for the config and overlays
>   directories (the default). If you use full paths for these two directories
>   in the Retroarch.cfg file, this application will not work with your
>   Retroarch installation.

Preferences

>   The 'Manual install' option allows you to manually download a zipped
>   repository from Github and place it in your %Temp% directory. This allows
>   you to 'save' the download so you can install bezels into platforms one at a
>   time, thus saving on bandwidth. Don't forget these downloaded files are left
>   behind and extracted directories are also left in your %Temp% directory, so
>   manually delete any file(s) you don't want cluttering your hard drive after
>   running this application.

>   Lastly, note you can use the Esc key to close the About, and Help panels, in
>   addition to the standard buttons and Windows Close gadget.

Download
--------

>   Proceed to the
>   [releases](https://github.com/thebezelproject/BezelProject-Windows/releases)
>   page in order to download the latest version.
