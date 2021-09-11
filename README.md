# Underdog2
is a Minecraft modpack with a goal to make Minecraft realistic in all ways possible. Now including evolution (aka. progression), geology and survival.

The progression part will be inspired by the human evolution, going from the stone age to the modern age. Mods will be gated using Gamestages, and the mods order will be following: Yanny's Stone Age, Charcoal Pit, Create / Immersive Engineering. Read more about the progression [here!](Progression.md)

There will a big focus on removing all the nether and end stuff, which is considered unrealistic. Redstone will be now replaced with copper wire.

https://www.curseforge.com/minecraft/modpacks/underdog2

# Development
For developing Underdog, it's necesseary for you to know [Git] and [Pax].

## Syncing mods
To sync the mods with the ones that are writen in the manifest.json, run `syncmods.bat`.

## Syncing overides
Everyting that is not writen in the manifest.json is an overide. (For example: configs, scrips, resources)
To copy the overides you changed to the pax/modpack/overides folder, run `sync_overrides.bat`.



## Pax usage
Use pax using cmd or terminal.
To see how [Pax] works it's recommended to go checkout its wiki: [here](https://github.com/froehlichA/pax/wiki)

### Locating pax folder
Locate the pax folder in your computer.
On both Windows and Linux you can use `cd` to do that.

#### Examples:
```cmd
Windows:
$ cd .\minecraft\pax

Linux:
$ cd ./minecraft/pax
```

<!-- Links: -->
[Git]: https://git-scm.com/
[Pax]: https://github.com/froehlichA/pax
[ModPackDownloader]: https://github.com/Nincraft/ModPackDownloader
