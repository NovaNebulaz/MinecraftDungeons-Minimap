NYX Minimap for public use.

- Apply / Rebuild button.
- Launch Game button.
- Open Pak Folder button.
- Remove Mod button.
- Batch files so PowerShell does not need to be opened manually.

Removed:

Main files:
- Open_Minimap_Modder.bat opens the UI.
- Minimap_Modder_UI.ps1 is the launcher interface.
- Apply_Selected_Minimap_Preset.ps1 applies the selected UI settings.
- Build_And_Install_Minimap.ps1 rebuilds and installs the minimap pak.
- Remove_NYX_Minimap.ps1 removes NYX minimap paks.
- Launch_Minecraft_Dungeons.bat launches the game from the saved config.
- Apply_Last_Minimap_Preset.bat reapplies the last saved preset.

UAssetGUI requirement:
Apply / Rebuild needs UAssetGUI.exe because the modder edits cooked Unreal Engine asset data before rebuilding the minimap pak. Download or keep UAssetGUI on your PC, then select its UAssetGUI.exe path in the launcher. The modder will not rebuild without it.

How to use:
1. Extract the full zip.
2. Run Open_Minimap_Modder.bat.
3. Select or auto-find the Minecraft Dungeons executable.
4. Select UAssetGUI.exe.
5. Pick a preset or enter your own values.
6. Click Apply / Rebuild.
7. Launch Minecraft Dungeons.

To remove the mod:
Click Remove Mod in the launcher, or run Remove_NYX_Minimap.ps1.

Range note:
MapScale accepts any positive numeric value. Lower values show farther away. Higher values zoom closer.

Default game path:
C:\Games\Minecraft Dungeons\Dungeons\Binaries\Win64\Dungeons-Win64-Shipping.exe if using a repacked game

