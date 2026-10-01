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
Close Bannerlord and open the launcher that matches the map you are playing. Under **Saved setup**, pick your setup. The **Campaign map** box switches to the map that setup saved. The locked Vanilla setup loads the vanilla map, and the locked More Nations setup loads the Remastered map. Then join through the host's Steam lobby, or connect directly to the host's address and UDP port.

If the game says it cannot load a DLL, click **Unblock DLLs**. When the log shows Windows blocked a DLL, that button turns red until you click it.

**Add mods** opens mods already on this PC. It does not download anything. Locked setups refuse Add mods. **Install mods** opens Steam for Workshop mods that are missing from the game's Modules folder.

**Crash logs** opens Coop_client.log and a dated client-action.log copy for Discord. **Save All Logs To One Zip** packs Coop_client.log, client-action.log, crash reports, engine logs, and hard crashes. Saves are left out. Send that zip.

Locked setups load Story Mode and Custom Battle with the game. The dedicated server leaves those off. On the Remastered map, the launcher says the host must load a single-player More Nations save.

## Host
Open `CoodszHost.exe`, pick the save the server should load, set **Region** (EU, NA, AS, OC, SA, or AF), and click **Start server**. Closing the host and opening it again still shows SERVING when the server is running.

On Start server, Host copies any missing starter files into the DedicatedServer folder from DedicatedServerRepair (`Start-ModdedServer.ps1`, `0Harmony.dll`, and the other starter files). Files you already have are left alone. Host will not start bare `BannerlordCoopServer.exe` when `Start-ModdedServer.ps1` is missing.

**Set server folder** chooses which `BannerlordCoopServer.exe` this tool starts when the dedicated server was not found, or the wrong copy was found.

The Modules tab shows how many mods are on. That start writes the locked setup's module list. Locked setups keep CoopNightly off and use stable Coop. On a normal setup, Bannerlord Coop can be Coop or CoopNightly; Host parks the extra copy so only one loads.

The host has its own **Campaign map** box on the server page, and choosing a saved setup switches it the same way. For More Nations Remastered, make the campaign in single player with that locked setup, then click **Load single-player save** and pick that .sav. The single-player file stays where it is. A campaign the server creates itself leaves the ground black.

**Load single-player MCM** copies single-player MCM settings into the selected setup. **Save settings** works on locked setups too. It writes difficulty and server options. It does not unlock the locked mod list. Restart the server after Save settings.

If Start server finds two different copies of the same DLL, the log names them and says which file to move. The server still starts. If a player is told the server does not support their modules, pick that same locked setup and press **Start server** again. If the join says the Bannerlord builds do not match, update Steam Workshop item 3770450698. Do not copy the game folder onto the dedicated server.

The server buttons are **Start server**, **Save**, **Restart**, then **Stop**. If the server cannot load a DLL, click **Unblock DLLs** in the host tool. That button turns red when the server log says Windows blocked a DLL. **Open server logs** highlights a dated `host-action-*.log` copy for Discord (not the plain `host-action.log`). Fast forward, save protection, and Cheats are covered in `README.txt`.

## Updating
Click **Install update** when the tool shows it. A progress bar shows the download, then the tool closes and opens again on the new copy. Your saved paths, cheats, and mod folders stay, and a running server stays up. The first time you move to a copy with this button, unzip the new zip over your current folder once and choose **Replace**. Do not delete the folder.

## Full instructions
The full player, host, and update steps are in `README.txt` in each release (see **PART 4**).
