# Third party notices

The Coodsz tools include code from the projects below. Each one keeps its own
license. This file ships in every release zip.

## CoopKeep

- Project: https://github.com/Aderimo/bannerlord-coopkeep
- Copyright (c) 2026 aderimo
- License: MIT

Parts of CoopKeep were ported into the Coodsz tools and changed to fit them. Every
ported file keeps the copyright line and the license notice in its header. The ported
parts are:

- `src/BannerlordCoopLauncher.Core/Server/`: the `@DS@` event parser (DsEvent,
  DsEventParser), the server phases (ServerPhase), the exit codes (ServerExit), the
  restart after a crash rules (CrashRestartPolicy), the known console lines
  (KnownLogLines), the server console allow list (ServerCommand), the SteamID64
  check with the ban list written through a temporary file (SteamBanFile), the clamped
  coop.debug command builders (AdminCommand) and the CPU and memory of the server
  process tree (ServerResourceMonitor).
- `src/BannerlordCoopLauncher.Core/Saves/`: the automatic save backups (BackupService)
  and the save name check (SaveSet).
- `src/BannerlordCoopLauncher.Core/Configuration/`: the in place JSONC editor (JsoncEditor), the
  mod-config.json settings list (ModSettingsCatalog), the mod-config.json store (ModConfigStore)
  and the settings kept per campaign save (WorldProfileStore).
- `src/BannerlordCoopLauncher.Core/Modules/ModCompatDatabase.cs`: the community mod list reader. The
  list itself (`compat-list/mods.json`) was seeded from CoopKeep's `compat/mods.json`, and the issue
  form, the tally script and its workflow in `.github/` were adapted from CoopKeep's.
- `src/BannerlordCoopLauncher.Core/Keep/`: the coodsz.* command builders (ToolsCommand), the server
  tools answer reader (ToolsParser), the item categories, search and sort (ItemCatalog), the skill
  sheet layout (SkillLayout), the save .json player list (KeepRoster), the admin log (AuditLog) and
  the Encyclopedia sections, entries, facts and links (Encyclopedia), after CoopKeep's encyclopedia,
  and the live map's layers, names by zoom, party activity and kingdom labels (LiveMap), after
  CoopKeep's map page.
- `compat/CoodszServerTools/`: the Coodsz Server Tools module (DedicatedServer.CoodszTools), whose
  command registration, item commands, hero development, equipment and roster commands come from
  CoopKeep's `src/CoopKeep.ServerTools`; its world command follows CoopKeep's encyclopedia sections
  and its map command CoopKeep's party and owner commands.
- `compat/CoodszImageExporter/`: the Coodsz Image Exporter game module (Build pictures), from
  CoopKeep's `src/CoopKeep.ImageExporter` (the thumbnail export, the PNG writer and the red/blue fix).
- The matching tests in `tests/BannerlordCoopLauncher.Tests/`.

```
MIT License

Copyright (c) 2026 aderimo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
