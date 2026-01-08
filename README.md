# NazoMacrosRecord

**NazoMacrosRecord** is a utility mod for Geometry Dash (Geode) developed by **NazoElectric**.  
It allows you to record, edit, save, and replay player inputs for practice and testing purposes.

> ⚠️ This mod is NOT intended for leaderboard runs or automatic gameplay.

## Features
- Record player inputs (press/release)
- Replay recorded macros
- Save and load macros from files
- Built-in macro editor (edit timing, actions, buttons)
- In-game ImGui interface
- Toggle UI with a hotkey (default F6)

## Usage
1. Start a level
2. Open the UI (F6)
3. Click **Record** and play
4. Click **Stop** when finished
5. Use **Play** to replay
6. Save or edit macros

## Macro Files
Stored as `.gdm` files:
```
time pressed button
0.132 1 1
0.200 0 1
```
Saved in platform-independent folder via `geode::get_mod_folder()`

## Macro Editor
- View, edit, delete events  
- Adjust timing precisely  
- Change press/release and button type  

## Notes
- Macros are FPS-dependent  
- Best with fixed FPS (e.g., 240)  
- Recording while playing back is not recommended  

## Requirements
- Geometry Dash 2.2  
- Geode 4.0+  
- Platforms: Windows & Android

## Credits
Developed by **NazoElectric**  
Powered by the Geode modding framework
