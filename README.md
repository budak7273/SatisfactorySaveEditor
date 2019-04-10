# Satisfactory Save Editor

A work in progress save editor for Satisfactory. Consists of both a save parser and an application for viewing and editing the parsed data.

Features include:
* View all save data in a more human readable format
* Manually edit data tags
* Enable the ingame minimap
* Change your inventory size
* Unlock all milestones, including unreleased and developer tools ones
* Search your save for certain information
* Determine the location of resource nodes
* Edit the contents of containers and your inventory
* Edit your player position to teleport yourself somewhere
* More coming soon

See the [releases page](https://github.com/Goz3rr/SatisfactorySaveEditor/releases) to download a compiled release, or build your own.

Written in C# using WPF for the user interface.

Made in Visual Studio 2017. Requires .NET Framework 4.7.2 Dev Pack and .NET Core 2.2 SDK. 

# Help

Mousing over items in the left pane tree view will provide a short description of their purpose in the save. Please help us keep this list up to date by updating [`Types.xml`](https://github.com/Goz3rr/SatisfactorySaveEditor/blob/master/SatisfactorySaveEditor/Types.xml) with the tags you discover in your save editing adventures.

If you have any questions, please feel free to contact us here on Github or on Discord. 

On discord, you can request help in the `#savegame-edits` channel of the [Satisfactory Modding](https://discord.gg/rNxYXht) discord server.

# FAQ

* None of the changes I'm making are doing anything in game.

Are you sure you're using `File > Save` to save after making your changes?

* I'm trying to use the `Unlock all research cheat`, but it isn't working!

Some people have encountered issues if they don't complete HUB tier 0 before running this cheat. Try that, and contact us if the issue continues.

* I placed some buildings unlocked with the research cheat and my game crashed!

As of 4/10/2019, some unreleased tier 7 and tier 8 structures such as the Nuclear Power Plant will cause the game to crash if they are built. This is completely unrelated to the save editor, and an issue (or intentional change by the developers) with the game itself. 