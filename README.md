# ep_taskbar_loader
> A mod to load ep_taskbar into Explorer

*Use this mod at your own risk! Explorer may crashloop if you do not have it set up correctly.*

**WARNING: THIS IS INCOMPATIBLE WITH EXPLORERPATCHER**

## Installation

- Grab the `ep_taskbar` DLL for your Windows version from <https://github.com/ExplorerPatcher/ep_taskbar_releases/releases> and place it in `C:\Program Files\ep_taskbar`. Current releases use codename filenames: `ep_taskbar.rs2` (Win10), `ep_taskbar.ni` (Win11 22H2/23H2), `ep_taskbar.ge` (Win11 24H2+)
- Download the mod from <https://github.com/Reabstraction/ep_taskbar_loader/releases>
- Create a new mod in WindHawk, and copy over the contents of the `.wh.cpp` file into it
- Compile and enable the mod, it should automatically restart explorer. If it gets stuck restarting or pops up a messagebox, disable the mod and send the logs

## Troubleshooting

- Ensure your Windows is both activated and fully up to date
- Ensure you do not have ExplorerPatcher installed (They conflict, use ExplorerPatcher's feature to load `ep_taskbar` instead)
- Ensure WindHawk can see symbols

Before asking about issues, follow <https://github.com/ramensoftware/windhawk/wiki/Troubleshooting#some-or-all-windhawk-mods-dont-work>
