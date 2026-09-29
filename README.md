# Coodsz Coop and Friends

Download and play Mount & Blade II: Bannerlord coop with friends.

Launchers and a dedicated server tool for a normal Coop game, and for a TAOM map game that is not using the dedicated TAOM server tool from [Coodsz-TAOM](https://github.com/Coodsz/Coodsz-TAOM).

## What you need
- Your own Steam copy of Bannerlord **1.4.8**
- .NET 8 Desktop Runtime, x64, if Windows asks for it: https://dotnet.microsoft.com/download/dotnet/8.0

## Download
Get `Coodsz-Coop-and-Friends-vX.Y.Z.zip` from the [latest release](https://github.com/Coodsz/Coodsz-Coop-and-Friends/releases/latest). Unzip it before you open anything. You get these program folders:

- `Coodsz Coop and Friends`: players on the vanilla map. Open `Coodsz Coop and Friends.exe`.
- `Coodsz and Friends`: players on the TAOM map. Open `Coodsz and Friends.exe`.
- `Coodsz Host`: the host. Open `CoodszHost.exe`. The window title is Coodsz and Friends Server Coop Manager Dedicated Tool.

If Windows says Unknown publisher, choose **More info**, then **Run anyway**.

## Players
Close Bannerlord and open the launcher that matches the map you are playing. Under **Saved setup**, pick your setup. The **Campaign map** box switches to the map that setup saved. The locked Vanilla setup loads the vanilla map, and the locked More Nations setup loads the Remastered map. Then join through the host's Steam lobby, or connect directly to the host's address and UDP port. If the game says it cannot load a DLL, click **Unblock DLLs**.

## Host
Open `CoodszHost.exe`, pick the save the server should load, and click **Start server**. That start writes the locked setup's module list. The host has its own **Campaign map** box on the server page, and choosing a saved setup switches it the same way. For More Nations Remastered, make the campaign in single player with that locked setup, then click **Load single-player save** and pick that .sav. The single-player file stays where it is. A campaign the server creates itself leaves the ground black. **Load single-player MCM** copies single-player MCM settings into the selected setup. If Start server finds two different copies of the same DLL, the log names them and says which file to move. The server still starts. If a player is told the server does not support their modules, pick that same locked setup and press **Start server** again. If the join says the Bannerlord builds do not match, update Steam Workshop item 3770450698. Do not copy the game folder onto the dedicated server. The server buttons are **Start server**, **Save**, **Restart**, then **Stop**. If the server cannot load a DLL, click **Unblock DLLs** in the host tool. Fast forward, save protection, and Cheats are covered in `README.txt`.

## Updating
Click **Install update** when the tool shows it. A progress bar shows the download, then the tool closes and opens again on the new copy. Your saved paths, cheats, and mod folders stay, and a running server stays up. The first time you move to a copy with this button, unzip the new zip over your current folder once and choose **Replace**. Do not delete the folder.

## Full instructions
The full player, host, and update steps are in `README.txt` in each release (see **PART 4**).
