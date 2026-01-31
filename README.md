THIS IS A FORK OF THE ORIGINAL LC-DOOM MOD BY [Cryptoc1](https://github.com/Cryptoc1/lc-doom).

# LC-DOOM

Play DOOM on the ship's terminal in Lethal Company.

Just open the Lethal Company's terminal and type "doom" to start playing!

# Contributing

- Fork the repository
- Create a `src\src\LethalCompany.Doom.csproj.user`
- Define required properties:
```xml
<PropertyGroup>
  <PluginStagingProfile>{PROFILE}</PluginStagingProfile>
</PropertyGroup>
```

- Run `dotnet publish`, or "Default Build Task" in VS Code
- Launch Lethal Company using the Thunderstore `{PROFILE}`

## Bug Report & Feature Request

If you've encountered an error, or have a feature request, please open an issue on [GitHub](https://github.com/olivrsec/lc-doom/issues).

When reporting an error, please include as most information as possible, such as any errorsor logs from BepInEx, or the version of the game or mod.

## Credits

- [Original Project](https://github.com/Cryptoc1/lc-doom)
- [idSoftware](https://www.idsoftware.com)
- [ManagedDoom](https://github.com/sinshu/managed-doom)
- [DoomInUnityInspector](https://github.com/xabblll/DoomInUnityInspector)

