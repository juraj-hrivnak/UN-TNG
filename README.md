# Underdog2
is a Minecraft modpack with a goal to make Minecraft realistic in all ways possible. Now including evolution (aka. progression), geology and survival.

The progression part will be inspired by human evolution, going from the stone age to the modern age. Mods will be gated using `Gamestages`, and the mods order will be following: `Yanny's Stone Age`, `Charcoal Pit`, `Create` / `Immersive Engineering`. Read more about the progression [here!](Progression.md)

There will a big focus on removing all the nether and end stuff, which is considered unrealistic. Redstone will be now replaced with copper wire.

### Links:
- [CurseForge]

***

# Development
For developing Underdog, you must know [Git].  
And for installing/removing/updating mods [Pax].

## Syncing mods
To sync the mods with the ones that are written in the manifest.json, run `syncmods.bat` or `syncmods.sh` depending on your operating sistem.

## Syncing overrides
Everything that is not written in the manifest.json is an override. (For example configs, scripts, resources)
To copy the overrides you changed to the pax/modpack/overrides folder, run `sync_overrides.bat` or `sync_overrides.sh` depending on your operating sistem.



## Pax usage
Use pax using cmd or terminal.
To see how [Pax] works it's recommended to go check out its wiki: [here](https://github.com/froehlichA/pax/wiki)

### Locating pax folder
Locate the pax folder on your computer.
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
[CurseForge]: https://www.curseforge.com/minecraft/modpacks/underdog2
