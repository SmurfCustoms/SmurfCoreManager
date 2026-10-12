# SmurfCore

A manager for **GTA V Legacy** and **LSPDFR**, by [Smurf Customs](https://smurfcustoms.co.uk).

One GTA install, three setups: **Game Build 1**, **Game Build 2**, and **Dev**. SmurfCore swaps only the folders and files you assign. Anything left in the game stays in the game.

**Version 2.0.0** · Windows 10/11 · GTA V Legacy only

---

## Features

### Profiles
- Game Build 1, Game Build 2, and Dev in one GTA folder
- Switching stays locked until you save a folder map
- Assign a whole folder, a single file, or only some files inside a folder
- **Leave in game** is the default. Those folders and files are never swapped
- Rename the three builds in Settings. The names are labels only

### Scripts and plugins
- Toggle LSPDFR plugins, Rage plugins, scripts, and ASI mods
- A toggle renames the file so the game skips it. The file stays on disk
- The page lists plugin conflicts and missing dependencies

### Launch
- **Story mode** starts GTA V
- **RagePluginHook** starts the game through RPH
- **Safe mode** turns the `mods` folder off so you can see whether a crash is coming from mods. Turn it off to put the folder back

### Key codes
Two separate lists. Click a key to copy the code for the list you are viewing.

| List | What the number is |
| --- | --- |
| Windows | Virtual-key codes for trainers and scripts. `F6` is `117`. |
| Stream Deck | Keyboard codes for a Stream Deck hotkey. `F6` is `16777269`. Letters and number keys match the Windows code. |

Groups: Function, Letters, Numbers, Modifiers, Navigation, Symbols, and Numpad. Search works for a name or a code, such as `F6`, `117`, or `16777269`.

### Backups
Core Management always includes:

- `GTA5.exe`
- `GTAVLauncher.exe`
- `GTAVLanguageSelect.exe`
- `PlayGTAV.exe`

You can add other files or folders from the GTA directory. Restore puts every file from that backup back. Paths outside the GTA folder are refused.

### Settings
- **Theme** — light, dark, or match Windows
- **Background** — wallpaper, with the grid left on so text stays readable. Clear background removes it
- **Accent** — outline, solid, or a gradient between two colours, across, down, or diagonal
- **Sound** — a short chime when SmurfCore opens
- **Notifications** — alerts for SmurfCore, ScriptHookV, ScriptHookVDotNet, RageNativeUI, LemonUI, and LSPDFR

---

## Folders

SmurfCore keeps its own folder inside the GTA V directory. Your game files stay where they are until you assign them.

```text
GTA V/
└── SmurfCore_Manager/
    ├── SmurfCore_Profiles/
    │   ├── Game Build 1/
    │   │   ├── mods/
    │   │   ├── plugins/
    │   │   ├── scripts/
    │   │   ├── ELS/
    │   │   └── lspdfr/
    │   ├── Game Build 2/
    │   │   ├── mods/
    │   │   ├── plugins/
    │   │   ├── scripts/
    │   │   ├── ELS/
    │   │   └── lspdfr/
    │   └── Game Build Dev/
    │       ├── mods/
    │       ├── plugins/
    │       ├── scripts/
    │       ├── ELS/
    │       └── lspdfr/
    └── SmurfCore_VersionBackups/
```

---

## How to use

### First launch
1. Run SmurfCore as **Administrator**. Profile switching is locked. Nothing in the GTA folder is renamed or moved.
2. Choose your GTA V folder if it is not already set.
3. Open **Folders & files**. Assign a whole folder, a file in the GTA folder, or open a folder and pick only some of the files. The other choice is **Leave in game**.
4. Review the list and save. Switching unlocks after that save.

### Switching profiles
1. Open SmurfCore.
2. Choose **Game Build 1**, **Game Build 2**, or **Dev**.
3. Only the folders and files you included are exchanged. Leave in game stays where it is.

### Plugins and scripts
Open **Manage Scripts & Plugins** and toggle an item before you launch. Enabled files load. Disabled files are renamed so the game skips them.

### Creating a backup
1. Open **Core Management**.
2. Add any extra GTA files or folders you want in the backup. The four game executables are already included.
3. Enter a name and create the backup.

### Restoring a backup
1. Select a backup.
2. Restore. Every file from that backup is put back.

---

## Notes

- Run SmurfCore as **Administrator** so it can read and swap the folders you assigned.
- SmurfCore is for **GTA V Legacy**.
- Leave in game is the safe choice. Those folders and files are never copied, moved, or swapped.
- Close GTA V before you save a profile or switch builds.
- Extra backup files have to live inside the GTA folder.

---

## Author

**Smurfy**  
[Smurf Customs](https://smurfcustoms.co.uk)  
[Discord](https://discord.smurfcustoms.co.uk)
```
