# Coop and Friends mod list

Which mods work with Bannerlord Coop. This page is made from
[compat-list/mods.json](compat-list/mods.json), the list Coodsz Coop and Friends and Coodsz Host show,
and is written again on its own whenever a player report is counted.

For Bannerlord 1.5.7, get [Coop v0.1.8](https://github.com/Bannerlord-Coop-Team/BannerlordCoop/releases/tag/v0.1.8) from GitHub. The Steam Workshop Coop build is for the older stack.
Host with the [official Bannerlord Coop Dedicated Server Manager](https://github.com/Bannerlord-Coop-Team/BannerlordCoop.DedicatedServer/releases).
CoopModPatch and PSCoopBridge are legacy patches. The Coodsz Coop compatibility pack for 0.1.8 is in development.
Older checks and player report counts do not verify 0.1.8.

## What the statuses mean

- **Works**: checked in Coop by Coodsz. The Coop version it was checked with is in the Checked with Coop column.
- **Works with issues**: checked by Coodsz, it runs with the fixes the note gives.
- **Client only**: only needs to be on the players' PCs (looks, interface). The server keeps it with its code off.
- **Reported working**: not checked by Coodsz, but at least 3 more players said it works than said it is broken.
- **Reported broken**: not checked by Coodsz, but at least 3 more players said it is broken than said it works.
- **Broken**: known to break Coop or to stop players from joining. Leave it off.
- **Not checked yet**: nobody checked it yet, or the player reports do not agree yet.

A status Coodsz set by hand never changes on its own; player reports show in the Players column.
**Players** counts the players who reported it works, is broken or is client only. **Last report** is
the day of the newest counted report.

## How to report a mod

In Coodsz Coop and Friends, click **Report** beside a mod on the Mods page, or **Report a mod** on the
Logs and help page (or **Report** on the bar after a game), and pick Works or Broken for each mod. No
GitHub account is needed. A report counts here about a day later.
With a GitHub account you can also use the [report form](https://github.com/Coodsz/Coodsz-Coop-and-Friends/issues/new?template=mod-compat.yml).

| Mod | Status | Players | Last report | Checked with Coop | Note |
| --- | --- | --- | --- | --- | --- |
| The Age of Men (TAOM) | Works |  |  | v0.1.8 | Works with the separate Coodsz TAOM Tools v1.2.18 or newer on Bannerlord 1.5.7. Use TAOM 2.0.41 or newer and its matching compatibility module. |
| [Better Exception Window](https://steamcommunity.com/sharedfiles/filedetails/?id=2875478172) | Client only |  |  |  | Worked in the Realm of Thrones test. A client crash window; Coop 0.1.8 on Bannerlord 1.5.7 still needs its own test. |
| [Xorberax's Legacy](https://steamcommunity.com/sharedfiles/filedetails/?id=2875138158) | Client only | 1 works, 1 broken | 2026-10-28 | v0.1.6 | Its code crashes a dedicated server, so the server keeps it in the list with its code off. Players keep it on. Turn off Unit Training and Scholars in MCM. Banking needs Nuggets' Bank patch; without it turn Banking off. Patch available: Nuggets' Agriculture Estate and Xorberax Bank patch. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| Artems Hunts | Broken |  |  | v0.1.6 | Broken in Coop; animal parties break. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Banner Kings](https://www.nexusmods.com/mountandblade2bannerlord/mods/3826) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Banner Kings Cultures Expanded](https://www.nexusmods.com/mountandblade2bannerlord/mods/6268) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Better Smithing Continued](https://steamcommunity.com/sharedfiles/filedetails/?id=3435494593) | Broken |  |  | v0.1.6 | Broken in Coop; crashes when entering the smithy. In the TAOM channel a player says the latest version works on Bannerlord 1.4.8 with TAOM, so retest before changing this. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| Birth and Aging Options | Broken |  |  | v0.1.6 | Optional official module. Coop refuses a player who has it turned on. Turn it off; Coop's own birthAndDeath setting in mod-config.json covers aging and births. |
| Burning Empires | Broken |  |  | v0.1.6 | Confirmed broken in Coop. It needs a major overhaul Coop compat patch before it can work. Confirmed by Coodsz, 2026-10-24. |
| [CA - Blood and Smoke - A Calradian Gunpowder Mod](https://www.nexusmods.com/mountandblade2bannerlord/mods/2742) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [CA - Eagle Rising - Rise of an Empire](https://steamcommunity.com/sharedfiles/filedetails/?id=2888487006) | Broken |  |  | v0.1.6 | Confirmed broken in Coop. It needs a major overhaul Coop compat patch before it can work. Confirmed by Coodsz, 2026-10-24. |
| [CA_EagleRising_EuropeMap](https://steamcommunity.com/sharedfiles/filedetails/?id=3154197768) | Broken |  |  | v0.1.6 | Confirmed broken in Coop. It needs a major overhaul Coop compat patch before it can work. Confirmed by Coodsz, 2026-10-24. |
| Calradia 1403 | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Calradia Awakens](https://www.nexusmods.com/mountandblade2bannerlord/mods/1169) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Calradia Expanded Kingdoms](https://www.nexusmods.com/mountandblade2bannerlord/mods/2828) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Calradia Factions Enhanced (CFE)](https://www.nexusmods.com/mountandblade2bannerlord/mods/3762) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [COOP Family](https://steamcommunity.com/sharedfiles/filedetails/?id=3797748062) | Broken |  |  | v0.1.6 | COOP Family by S1MA$H, on Steam Workshop 3797748062, made for Coop 0.1.5. Obsolete on Coop 0.1.6, which has family, birth and aging built in. Leave it and birth or aging mods off. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [Detailed Character Creation](https://steamcommunity.com/sharedfiles/filedetails/?id=2886299887) | Broken |  |  | v0.1.6 | Broken in Coop; companions are not saved and players can change their own character. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Empires of Europe 1100](https://steamcommunity.com/sharedfiles/filedetails/?id=2968204274) | Broken | 0 works, 1 broken | 2026-10-24 | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Empires of Europe 1700](https://steamcommunity.com/sharedfiles/filedetails/?id=3231544373) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Empires of Europe Americas](https://steamcommunity.com/sharedfiles/filedetails/?id=3655976656) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Europe_LemmyProject](https://steamcommunity.com/sharedfiles/filedetails/?id=2875102059) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| Fast Mode | Broken |  |  | v0.1.6 | Optional official module. Coop refuses a player who has it turned on. Turn it off on the host and every player. |
| [Make Calradia Great Again](https://steamcommunity.com/sharedfiles/filedetails/?id=2910466267) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Realistic Battle Mod (RBM)](https://steamcommunity.com/sharedfiles/filedetails/?id=2859251492) | Broken | 0 works, 1 broken | 2026-11-07 | v0.1.6 | Broken in Coop for the campaign economy; combat works. Parties auto buy worn gear, posture and stamina do not sync, and on a Coodsz Host server with only RBM (even the AI module alone) town weapon stocks drain over the first week and never refill and some workshops (Velvet) never produce. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; report by Mistaken., 2026-10-13; Lulu reported the same on 2026-10-07 (old Coop 0.1.5 thread). |
| [Realm of Thrones](https://www.nexusmods.com/mountandblade2bannerlord/mods/2907) | Broken |  |  | v0.1.6 | Use the Coodsz Realm of Thrones tools with Realm of Thrones 8.1.2, War Sails and Bannerlord 1.4.8. That stack uses its own Coop build. |
| [Realms Forgotten](https://www.nexusmods.com/mountandblade2bannerlord/mods/4455) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Scum and Villainy](https://www.nexusmods.com/mountandblade2bannerlord/mods/426) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Shokuho](https://steamcommunity.com/sharedfiles/filedetails/?id=3496296180) | Broken |  |  | v0.1.6 | Confirmed broken in Coop. It needs a major overhaul Coop compat patch before it can work. Confirmed by Coodsz, 2026-10-24. |
| [The Old Realms - Armory](https://steamcommunity.com/sharedfiles/filedetails/?id=3025575223) | Broken |  |  | v0.1.6 | Confirmed broken in Coop. It needs a major overhaul Coop compat patch before it can work. Confirmed by Coodsz, 2026-10-24. |
| [The Old Realms - Core](https://steamcommunity.com/sharedfiles/filedetails/?id=3025574678) | Broken |  |  | v0.1.6 | Confirmed broken in Coop. It needs a major overhaul Coop compat patch before it can work. Confirmed by Coodsz, 2026-10-24. |
| [The Old Realms - Environment](https://steamcommunity.com/sharedfiles/filedetails/?id=3025579210) | Broken |  |  | v0.1.6 | Confirmed broken in Coop. It needs a major overhaul Coop compat patch before it can work. Confirmed by Coodsz, 2026-10-24. |
| [TheLandOfSika](https://steamcommunity.com/sharedfiles/filedetails/?id=2875157034) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| [Unblockable Thrust](https://steamcommunity.com/sharedfiles/filedetails/?id=3614435151) | Broken |  |  | v0.1.6 | Broken in Coop; irregular crashes when a thrust hits. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| [Village Enterprise](https://steamcommunity.com/sharedfiles/filedetails/?id=3620030171) | Broken |  |  | v0.1.6 | Broken in Coop; the enterprise resets when the server restarts. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| War Sails | Broken |  |  | v0.1.6 | The old Coop 0.1.6 stack did not support War Sails. For Coop 0.1.8, use the same DLC selection as the host. |
| [Wheel of Time Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3251984526) | Broken |  |  | v0.1.6 | Overhaul. This overhaul has no verified Coop setup. Confirmed by Coodsz, 2026-10-24. |
| Achievement Enabler | Not checked yet | 1 works, 0 broken | 2026-11-05 |  |  |
| [Achievement Unblocker](https://www.nexusmods.com/mountandblade2bannerlord/mods/4587) | Not checked yet |  |  |  |  |
| [Adjustable Bandits](https://steamcommunity.com/sharedfiles/filedetails/?id=2896450980) | Not checked yet |  |  |  |  |
| [Adjustable Leveling](https://steamcommunity.com/sharedfiles/filedetails/?id=2896410558) | Not checked yet | 1 works, 0 broken | 2026-11-23 |  |  |
| [Adonnay's Exotic Weaponry](https://steamcommunity.com/sharedfiles/filedetails/?id=2875503961) | Not checked yet |  |  |  |  |
| [Adonnay's Troop Changer](https://steamcommunity.com/sharedfiles/filedetails/?id=2875508967) | Not checked yet |  |  |  |  |
| [Adoption](https://steamcommunity.com/sharedfiles/filedetails/?id=2893279424) | Not checked yet |  |  |  |  |
| [Adventurer](https://steamcommunity.com/sharedfiles/filedetails/?id=3172213744) | Not checked yet |  |  |  |  |
| [Affairs of Calradia](https://www.nexusmods.com/mountandblade2bannerlord/mods/11164) | Not checked yet |  |  |  |  |
| [Aggregated Income](https://steamcommunity.com/sharedfiles/filedetails/?id=2875113446) | Not checked yet |  |  |  |  |
| [Agriculture Estate](https://steamcommunity.com/sharedfiles/filedetails/?id=2880158010) | Not checked yet |  |  | v0.1.6 | Legacy Coop setup. Support on 0.1.8 is unverified. Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Needed by PSCoopBridge for Player Settlement in Coop. (or Nuggets' older patch, which may clash with CoopModPatch). Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [AI Banner Icons](https://steamcommunity.com/sharedfiles/filedetails/?id=3124993149) | Not checked yet |  |  |  |  |
| [AI Defend Yourself](https://www.nexusmods.com/mountandblade2bannerlord/mods/897) | Not checked yet |  |  |  |  |
| [AI Executioner](https://www.nexusmods.com/mountandblade2bannerlord/mods/3917) | Not checked yet |  |  |  |  |
| [AI Influence](https://steamcommunity.com/sharedfiles/filedetails/?id=3584621421) | Not checked yet |  |  |  |  |
| [AI Personalities](https://www.nexusmods.com/mountandblade2bannerlord/mods/6725) | Not checked yet |  |  |  |  |
| [AI Values Life](https://www.nexusmods.com/mountandblade2bannerlord/mods/481) | Not checked yet |  |  |  |  |
| AIValuesLife | Not checked yet | 1 works, 0 broken | 2026-10-28 |  |  |
| [Alive Scenes](https://www.nexusmods.com/mountandblade2bannerlord/mods/8138) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. On the Coodsz Host working list, run on Coop v0.1.6 servers. The host and every player need the same version. |
| [Allegiance Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2886206108) | Not checked yet |  |  |  |  |
| [Always Show Titles](https://steamcommunity.com/sharedfiles/filedetails/?id=2945284452) | Not checked yet |  |  |  |  |
| [Ancient Civilizationss](https://www.nexusmods.com/mountandblade2bannerlord/mods/5859) | Not checked yet |  |  |  |  |
| [Arcane Magisterium](https://steamcommunity.com/sharedfiles/filedetails/?id=3244601847) | Not checked yet |  |  |  |  |
| [Arena Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2887640995) | Not checked yet |  |  |  |  |
| ArenaRecruiters | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. By Spidey; the author says it is fully compatible with Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Arenas Extended](https://www.nexusmods.com/mountandblade2bannerlord/mods/6137) | Not checked yet |  |  |  |  |
| ArenaTroopTraining | Not checked yet |  |  | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Arena troop training with set prices and XP, server and client versions, made for Coop and posted on the Coop Discord (Sannech in the old 0.1.5 thread; the 0.1.6 thread credits Spidey, who says it is fully compatible). Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [ArmsDealer](https://steamcommunity.com/sharedfiles/filedetails/?id=2875975898) | Not checked yet |  |  |  |  |
| [ArrangeMarriageForFamily](https://steamcommunity.com/sharedfiles/filedetails/?id=2880762493) | Not checked yet |  |  |  |  |
| [Art of War](https://www.nexusmods.com/mountandblade2bannerlord/mods/3970) | Not checked yet |  |  |  |  |
| Artem's Cinematic Charges | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Not fully synced between players, and the server can take 30 minutes or more to start. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| Artem's Cinematic Combat | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Not fully synced between players, and the server can take 30 minutes or more to start. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| ArtemCore | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Library for Artem's mods. Players keep this mod's Assets folder, don't delete it. Server copy: remove the mod's Assets folder. For Coop 0.1.8 use the official Bannerlord Coop Dedicated Server Manager and apply this change only to the server copy. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| Artems Chariots | Not checked yet |  |  |  | Asked about in the thread; not tested in Coop yet. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08. |
| [Artems Nostalgic Conversations](https://www.nexusmods.com/mountandblade2bannerlord/mods/6684) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Not fully synced between players, and the server can take 30 minutes or more to start. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| ArtemsBetterUIVisuals | Not checked yet | 0 works, 1 broken | 2026-11-11 |  |  |
| Assassin's Creed Combat | Not checked yet | 1 works, 0 broken | 2026-10-30 |  |  |
| [Attack Hideouts During Daytime](https://steamcommunity.com/sharedfiles/filedetails/?id=2875752021) | Not checked yet |  |  |  |  |
| [Attribute Per Level](https://www.nexusmods.com/mountandblade2bannerlord/mods/121) | Not checked yet |  |  |  |  |
| [Auto Equip Companions](https://steamcommunity.com/sharedfiles/filedetails/?id=3457590233) | Not checked yet |  |  |  |  |
| [Auto Resolve Rebalanced](https://www.nexusmods.com/mountandblade2bannerlord/mods/3453) | Not checked yet |  |  |  |  |
| [AutoBlocker](https://www.nexusmods.com/mountandblade2bannerlord/mods/128) | Not checked yet |  |  |  |  |
| [AutoCrossbow](https://steamcommunity.com/sharedfiles/filedetails/?id=3076321142) | Not checked yet |  |  |  |  |
| AutoResolveRebalanced | Not checked yet | 1 works, 0 broken | 2026-11-25 |  |  |
| [AutoTrader](https://steamcommunity.com/sharedfiles/filedetails/?id=2875660601) | Not checked yet |  |  |  |  |
| [B.A.R.D. - Aserai Army Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2879957124) | Not checked yet |  |  |  |  |
| [B.A.R.D. - Battanian Army Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2875101301) | Not checked yet |  |  |  |  |
| [B.A.R.D. - Imperial Army Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2875103010) | Not checked yet |  |  |  |  |
| [B.A.R.D. - Khuzait Army Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2882454523) | Not checked yet |  |  |  |  |
| [B.A.R.D. - Sturgian Army Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2875089081) | Not checked yet |  |  |  |  |
| [B.A.R.D. - Vlandian Army Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2875386075) | Not checked yet |  |  |  |  |
| [Bahamut's Armory+](https://steamcommunity.com/sharedfiles/filedetails/?id=2875496157) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. If a player crashes on start, delete the mod's Shaders folder on that PC. With RBM, use the matching RBM patch. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Baijin Troops](https://steamcommunity.com/sharedfiles/filedetails/?id=2890099774) | Not checked yet |  |  |  |  |
| [Balanced Tournament Armor](https://steamcommunity.com/sharedfiles/filedetails/?id=2875978806) | Not checked yet | 1 works, 0 broken | 2026-10-28 |  |  |
| [Bandit Black Hole](https://www.nexusmods.com/mountandblade2bannerlord/mods/7433) | Not checked yet |  |  |  |  |
| [Bandit Militias](https://www.nexusmods.com/mountandblade2bannerlord/mods/1768) | Not checked yet |  |  |  |  |
| [Bandit Variety](https://www.nexusmods.com/mountandblade2bannerlord/mods/3041) | Not checked yet |  |  |  |  |
| [Banks of Calradia](https://steamcommunity.com/sharedfiles/filedetails/?id=3596556635) | Not checked yet |  |  |  |  |
| [Banner Editor](https://www.nexusmods.com/mountandblade2bannerlord/mods/4944) | Not checked yet |  |  |  |  |
| [Banner Fix](https://www.nexusmods.com/mountandblade2bannerlord/mods/4600) | Not checked yet | 2 works, 0 broken | 2026-11-25 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Comes with the Coodsz tools. Load it before Raise your Banner. For Coop 0.1.8 use the official Bannerlord Coop Dedicated Server Manager and apply this change only to the server copy. Players keep theirs, don't delete it. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [BannerColorPersistence with BannerPaste](https://steamcommunity.com/sharedfiles/filedetails/?id=2875642325) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Banner colors only last for the session. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| BannerCraft | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Fast clicks can desync materials. BannerCraft, ForgeMaster and Modular Smithing 2 work together. With all three the Smelt tab gets stuck; switch tabs with Q and E. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [BannerEditor Enhancer](https://www.nexusmods.com/mountandblade2bannerlord/mods/8) | Not checked yet |  |  |  |  |
| [BannerLib](https://www.nexusmods.com/mountandblade2bannerlord/mods/131) | Not checked yet |  |  |  |  |
| [Bannerloot](https://steamcommunity.com/sharedfiles/filedetails/?id=3615438656) | Not checked yet |  |  |  |  |
| [Bannerlord Banks](https://steamcommunity.com/sharedfiles/filedetails/?id=2875187162) | Not checked yet |  |  |  |  |
| [Bannerlord Cheats](https://steamcommunity.com/sharedfiles/filedetails/?id=2882183897) | Not checked yet |  |  |  |  |
| [Bannerlord Cheats Reload](https://www.nexusmods.com/mountandblade2bannerlord/mods/6446) | Not checked yet |  |  |  |  |
| [Bannerlord Expanded - Children Expanded](https://www.nexusmods.com/mountandblade2bannerlord/mods/6735) | Not checked yet |  |  |  |  |
| [Bannerlord Expanded - Companion Expanded](https://www.nexusmods.com/mountandblade2bannerlord/mods/6736) | Not checked yet |  |  |  |  |
| [Bannerlord Expanded - Settlement Interactions](https://www.nexusmods.com/mountandblade2bannerlord/mods/6887) | Not checked yet |  |  |  |  |
| [Bannerlord Expanded - Spouses Expanded](https://www.nexusmods.com/mountandblade2bannerlord/mods/6952) | Not checked yet |  |  |  |  |
| [Bannerlord Trainer Plus](https://www.nexusmods.com/mountandblade2bannerlord/mods/2278) | Not checked yet |  |  |  |  |
| [Bannerlord Tweaks](https://www.nexusmods.com/mountandblade2bannerlord/mods/49) | Not checked yet |  |  |  |  |
| [Bannerlord: Take All Perks](https://steamcommunity.com/sharedfiles/filedetails/?id=3617286010) | Not checked yet |  |  |  |  |
| [Bannerlord.WindsOfMagic](https://steamcommunity.com/sharedfiles/filedetails/?id=2912991581) | Not checked yet |  |  |  |  |
| [Bannerlord.XPTweaks](https://steamcommunity.com/sharedfiles/filedetails/?id=2883675274) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Works in Coop; not fully tested. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [BannerPigeon](https://steamcommunity.com/sharedfiles/filedetails/?id=3617335871) | Not checked yet |  |  |  |  |
| [Basic Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=3132182628) | Not checked yet |  |  |  |  |
| [Bastard Children](https://www.nexusmods.com/mountandblade2bannerlord/mods/3674) | Not checked yet |  |  |  |  |
| [Battle Duels](https://www.nexusmods.com/mountandblade2bannerlord/mods/6436) | Not checked yet |  |  |  |  |
| [Battle Instinct](https://www.nexusmods.com/mountandblade2bannerlord/mods/13484) | Not checked yet | 1 works, 0 broken | 2026-10-24 |  | Asked about in the thread; not tested in Coop yet. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08. |
| [Battle Mini Map](https://steamcommunity.com/sharedfiles/filedetails/?id=2876503777) | Not checked yet |  |  |  |  |
| [Battlefield Duel](https://steamcommunity.com/sharedfiles/filedetails/?id=3412388072) | Not checked yet |  |  |  |  |
| Battlefield Equipment | Not checked yet | 0 works, 1 broken | 2026-11-04 |  |  |
| [BattleSize](https://www.nexusmods.com/mountandblade2bannerlord/mods/2803) | Not checked yet |  |  |  |  |
| [BattleSize Resized](https://www.nexusmods.com/mountandblade2bannerlord/mods/8177) | Not checked yet |  |  |  |  |
| [Beards Fix](https://steamcommunity.com/sharedfiles/filedetails/?id=2933297952) | Not checked yet |  |  |  |  |
| [Bellum Civile](https://www.nexusmods.com/mountandblade2bannerlord/mods/10609) | Not checked yet |  |  |  |  |
| [Ben's Ultimate Armory](https://steamcommunity.com/sharedfiles/filedetails/?id=3769870741) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. If a player crashes on start, delete the mod's Shaders folder on that PC. With RBM, use the matching RBM patch. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Better Attribute Points](https://www.nexusmods.com/mountandblade2bannerlord/mods/6269) | Not checked yet |  |  |  |  |
| [Better Attributes](https://www.nexusmods.com/mountandblade2bannerlord/mods/3434) | Not checked yet |  |  |  |  |
| [Better Auto Calc](https://www.nexusmods.com/mountandblade2bannerlord/mods/673) | Not checked yet |  |  |  |  |
| [Better Bandages](https://www.nexusmods.com/mountandblade2bannerlord/mods/6388) | Not checked yet |  |  |  |  |
| [Better Bandit Troop Trees](https://steamcommunity.com/sharedfiles/filedetails/?id=3428491263) | Not checked yet |  |  |  |  |
| [Better Bandits Plus](https://steamcommunity.com/sharedfiles/filedetails/?id=3736768674) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Also with its Tweaks add on. Turn on Suppress Bandit Party Wanted Popups and Exclude Player Main Party From Bandit Army Size Rules. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Better Bows](https://steamcommunity.com/sharedfiles/filedetails/?id=3291480524) | Not checked yet |  |  |  |  |
| [Better Caravans](https://steamcommunity.com/sharedfiles/filedetails/?id=3720013905) | Not checked yet |  |  |  |  |
| [Better Combat](https://www.nexusmods.com/mountandblade2bannerlord/mods/3188) | Not checked yet |  |  |  |  |
| [Better Core](https://www.nexusmods.com/mountandblade2bannerlord/mods/6367) | Not checked yet |  |  |  |  |
| [Better Executions](https://www.nexusmods.com/mountandblade2bannerlord/mods/6426) | Not checked yet |  |  |  |  |
| [Better Experience](https://www.nexusmods.com/mountandblade2bannerlord/mods/6393) | Not checked yet |  |  |  |  |
| [Better Focus Points](https://www.nexusmods.com/mountandblade2bannerlord/mods/6273) | Not checked yet |  |  |  |  |
| [Better HUD](https://www.nexusmods.com/mountandblade2bannerlord/mods/3234) | Not checked yet |  |  |  |  |
| [Better Map Camera](https://steamcommunity.com/sharedfiles/filedetails/?id=3626388246) | Not checked yet |  |  |  |  |
| [Better Marriage](https://www.nexusmods.com/mountandblade2bannerlord/mods/3202) | Not checked yet |  |  |  |  |
| [Better Name Dice](https://steamcommunity.com/sharedfiles/filedetails/?id=3492680625) | Not checked yet |  |  |  |  |
| Better Party Visuals | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. By Artem. Needs ArtemCore. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Better Pikes](https://steamcommunity.com/sharedfiles/filedetails/?id=3024923158) | Not checked yet |  |  |  |  |
| [Better Save and Load](https://www.nexusmods.com/mountandblade2bannerlord/mods/3128) | Not checked yet |  |  |  |  |
| [Better Skills](https://www.nexusmods.com/mountandblade2bannerlord/mods/3433) | Not checked yet |  |  |  |  |
| [Better Time](https://steamcommunity.com/sharedfiles/filedetails/?id=2875960358) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Keep the speed up setting low. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| Better UI Visuals | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. By Artem. Needs ArtemCore. Leaves a harmless error in the log. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [BetterArenaPrize](https://steamcommunity.com/sharedfiles/filedetails/?id=3485683913) | Not checked yet |  |  |  |  |
| [BetterBandits](https://steamcommunity.com/sharedfiles/filedetails/?id=3309224450) | Not checked yet |  |  |  |  |
| [BetterPartyTooltip](https://www.nexusmods.com/mountandblade2bannerlord/mods/7643) | Not checked yet |  |  |  |  |
| [BetterTroopHUD](https://steamcommunity.com/sharedfiles/filedetails/?id=2999591774) | Not checked yet |  |  |  |  |
| [BloodMod - More Blood and Gore](https://www.nexusmods.com/mountandblade2bannerlord/mods/1591) | Not checked yet |  |  |  |  |
| [Bodyguards](https://steamcommunity.com/sharedfiles/filedetails/?id=2880365016) | Not checked yet | 1 works, 0 broken | 2026-11-01 |  |  |
| [Both Perks](https://steamcommunity.com/sharedfiles/filedetails/?id=3615340073) | Not checked yet | 1 works, 0 broken | 2026-11-23 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Breakable Polearms](https://steamcommunity.com/sharedfiles/filedetails/?id=3080363208) | Not checked yet |  |  |  |  |
| [Broken mods fixes](https://www.nexusmods.com/mountandblade2bannerlord/mods/2613) | Not checked yet |  |  |  |  |
| [Brynhild The Shieldmaiden](https://steamcommunity.com/sharedfiles/filedetails/?id=2883954746) | Not checked yet |  |  |  |  |
| [Butter Achievements](https://www.nexusmods.com/mountandblade2bannerlord/mods/4629) | Not checked yet |  |  |  |  |
| [ButterLib](https://steamcommunity.com/sharedfiles/filedetails/?id=2859232415) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Library other mods need. It stays on the list; its menus do not run on the dedicated server. |
| [BuyPatrols](https://www.nexusmods.com/mountandblade2bannerlord/mods/343) | Not checked yet |  |  |  |  |
| [Calradia At War](https://steamcommunity.com/sharedfiles/filedetails/?id=2878689343) | Not checked yet |  |  |  |  |
| [Calradia Expanded](https://www.nexusmods.com/mountandblade2bannerlord/mods/1389) | Not checked yet |  |  |  |  |
| [Calradia Rising Armory](https://steamcommunity.com/sharedfiles/filedetails/?id=3469351983) | Not checked yet | 1 works, 0 broken | 2026-11-01 |  |  |
| [Calradian Patrols V2](https://steamcommunity.com/sharedfiles/filedetails/?id=2859407083) | Not checked yet |  |  |  |  |
| [Calradic Campaign](https://steamcommunity.com/sharedfiles/filedetails/?id=2933062399) | Not checked yet |  |  |  |  |
| [Camel Troops and Aserai Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=2887096699) | Not checked yet | 1 works, 0 broken | 2026-11-01 |  |  |
| [Camp Menu](https://steamcommunity.com/sharedfiles/filedetails/?id=3627110143) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Runs in Coop; not fully tested. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Caravans Give Trade XP](https://www.nexusmods.com/mountandblade2bannerlord/mods/907) | Not checked yet |  |  |  |  |
| [Carrier - Banners and Torches](https://www.nexusmods.com/mountandblade2bannerlord/mods/3354) | Not checked yet |  |  |  |  |
| [CC's Banners](https://steamcommunity.com/sharedfiles/filedetails/?id=2877445271) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Change Settlement Culture](https://www.nexusmods.com/mountandblade2bannerlord/mods/510) | Not checked yet |  |  |  |  |
| [Changing Culture](https://www.nexusmods.com/mountandblade2bannerlord/mods/2453) | Not checked yet |  |  |  |  |
| [Character Development Editor](https://steamcommunity.com/sharedfiles/filedetails/?id=3658499134) | Not checked yet |  |  |  |  |
| [Character Export Import](https://www.nexusmods.com/mountandblade2bannerlord/mods/16) | Not checked yet |  |  |  |  |
| [Character Manager](https://steamcommunity.com/sharedfiles/filedetails/?id=2879953123) | Not checked yet |  |  |  |  |
| [Character Reload](https://www.nexusmods.com/mountandblade2bannerlord/mods/2134) | Not checked yet |  |  |  |  |
| [Character Reload Fix](https://www.nexusmods.com/mountandblade2bannerlord/mods/3700) | Not checked yet |  |  |  |  |
| [ChatAi Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3403120292) | Not checked yet |  |  |  |  |
| [Cheer Mod](https://www.nexusmods.com/mountandblade2bannerlord/mods/238) | Not checked yet |  |  |  |  |
| [Children Grow Faster](https://www.nexusmods.com/mountandblade2bannerlord/mods/5495) | Not checked yet |  |  |  |  |
| [Chinese Legendary Weapons](https://steamcommunity.com/sharedfiles/filedetails/?id=3659907178) | Not checked yet |  |  |  |  |
| [Chinese Weapon](https://steamcommunity.com/sharedfiles/filedetails/?id=3291515587) | Not checked yet |  |  |  |  |
| [Choose Your Troops](https://steamcommunity.com/sharedfiles/filedetails/?id=2957211804) | Not checked yet |  |  |  |  |
| [CI Modpack](https://steamcommunity.com/sharedfiles/filedetails/?id=3245522442) | Not checked yet |  |  |  |  |
| [Cinematic Combat](https://www.nexusmods.com/mountandblade2bannerlord/mods/5819) | Not checked yet |  |  |  |  |
| [CITEditor](https://www.nexusmods.com/mountandblade2bannerlord/mods/141) | Not checked yet |  |  |  |  |
| [Civilian Mounts](https://steamcommunity.com/sharedfiles/filedetails/?id=3623922895) | Not checked yet |  |  |  |  |
| [Civilized](https://steamcommunity.com/sharedfiles/filedetails/?id=2883761031) | Not checked yet |  |  |  |  |
| [CJ's - Overhaul - Starting Gear](https://steamcommunity.com/sharedfiles/filedetails/?id=3625253563) | Not checked yet |  |  |  |  |
| [CJ's Empire Troops](https://steamcommunity.com/sharedfiles/filedetails/?id=2885799582) | Not checked yet |  |  |  |  |
| [CJ's Empire Troops - B.A.R.D](https://steamcommunity.com/sharedfiles/filedetails/?id=2885799952) | Not checked yet |  |  |  |  |
| [CJ's Empire Troops - Overhaul](https://steamcommunity.com/sharedfiles/filedetails/?id=3617725143) | Not checked yet |  |  |  |  |
| [CJ's Lord Equipment Tweaks](https://steamcommunity.com/sharedfiles/filedetails/?id=2885430860) | Not checked yet |  |  |  |  |
| [CJ's Starting Gear](https://steamcommunity.com/sharedfiles/filedetails/?id=2884793525) | Not checked yet |  |  |  |  |
| [CJ's Vanilla Items](https://steamcommunity.com/sharedfiles/filedetails/?id=2885428909) | Not checked yet |  |  |  |  |
| [Clan Armies](https://steamcommunity.com/sharedfiles/filedetails/?id=3618752412) | Not checked yet |  |  |  |  |
| [Commander](https://steamcommunity.com/sharedfiles/filedetails/?id=3670027574) | Not checked yet |  |  |  |  |
| [Community Patch](https://www.nexusmods.com/mountandblade2bannerlord/mods/186) | Not checked yet |  |  |  |  |
| [Companions Limit UnLock](https://steamcommunity.com/sharedfiles/filedetails/?id=3310745531) | Not checked yet |  |  |  |  |
| [Complex Characters](https://www.nexusmods.com/mountandblade2bannerlord/mods/7565) | Not checked yet |  |  |  |  |
| [Control Your Allies After Death](https://www.nexusmods.com/mountandblade2bannerlord/mods/407) | Not checked yet |  |  |  |  |
| [COOP Server Settings Lock](https://steamcommunity.com/sharedfiles/filedetails/?id=3794802607) | Not checked yet | 1 works, 0 broken | 2026-10-29 | v0.1.6 | Retired and not needed. By S1MA$H. It is gone from the Workshop, Nexus and ModDB and is no longer part of the Coodsz setup. Coop checks that the host and the players load the same mods, so the host and every player turn it off together. For Coop 0.1.8 use the official Bannerlord Coop Dedicated Server Manager. Source: Coodsz, 2026-10-29. |
| [CoopModPatch](https://steamcommunity.com/sharedfiles/filedetails/?id=3786391685) | Not checked yet | 3 works, 2 broken | 2026-11-24 | v0.1.6 | Legacy patch for Improved Garrisons, Settlement Culture Drift and My Little Warband. Used on Coop 0.1.5 and 0.1.6. The Coodsz Coop compatibility pack for 0.1.8 is in development. |
| [Courier](https://www.nexusmods.com/mountandblade2bannerlord/mods/9048) | Not checked yet |  |  |  |  |
| CourierMessenger | Not checked yet | 1 works, 0 broken | 2026-11-25 |  |  |
| Crafting Order Indicator | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Crafting Piece Sorter](https://www.nexusmods.com/mountandblade2bannerlord/mods/6961) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| Crafting Tier Indicator | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Crash Doctor](https://steamcommunity.com/sharedfiles/filedetails/?id=3717685432) | Not checked yet |  |  |  |  |
| [Crusaders](https://steamcommunity.com/sharedfiles/filedetails/?id=2927895725) | Not checked yet | 1 works, 0 broken | 2026-11-01 |  |  |
| [Cultural Kingdoms](https://steamcommunity.com/sharedfiles/filedetails/?id=3647153514) | Not checked yet |  |  |  |  |
| [Culture Switch - Companions](https://steamcommunity.com/sharedfiles/filedetails/?id=2905239873) | Not checked yet |  |  |  |  |
| [Culture Switch - Vassals](https://steamcommunity.com/sharedfiles/filedetails/?id=2905660587) | Not checked yet |  |  |  |  |
| [Cultured Start](https://www.nexusmods.com/mountandblade2bannerlord/mods/212) | Not checked yet |  |  |  |  |
| [Custom Spawns API](https://steamcommunity.com/sharedfiles/filedetails/?id=2878685456) | Not checked yet |  |  |  |  |
| [Custom Troop](https://www.nexusmods.com/mountandblade2bannerlord/mods/2482) | Not checked yet |  |  |  |  |
| [Death for All](https://steamcommunity.com/sharedfiles/filedetails/?id=2920524845) | Not checked yet |  |  |  |  |
| [Declare War Together](https://www.nexusmods.com/mountandblade2bannerlord/mods/5031) | Not checked yet |  |  |  |  |
| [DeReMilitari](https://steamcommunity.com/sharedfiles/filedetails/?id=2875168687) | Not checked yet |  |  |  |  |
| [Detailed Character Creation - Additional Sliders](https://steamcommunity.com/sharedfiles/filedetails/?id=3072569986) | Not checked yet |  |  |  |  |
| [Developer Console](https://www.nexusmods.com/mountandblade2bannerlord/mods/4) | Not checked yet |  |  |  |  |
| [Diplomacy](https://steamcommunity.com/sharedfiles/filedetails/?id=2881380744) | Not checked yet | 1 works, 0 broken | 2026-10-26 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Known issues, the fork too. Use Coodsz's Diplomacy.CoopCompat right after it on the server and every player. One player saw the vanilla launcher crash with Diplomacy and the patch; mod launchers are fine. Patch available: Diplomacy.CoopCompat. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| Diplomacy Coop Compat | Not checked yet | 1 works, 0 broken | 2026-10-26 | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Coodsz patch for Diplomacy, comes with the Coodsz tools. Made for Coop 0.1.6. Turns off war exhaustion and messengers in Coop and sends its buttons through the server. Load it right after Diplomacy, on the server and every player. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08. |
| [Dismemberment](https://www.nexusmods.com/mountandblade2bannerlord/mods/400) | Not checked yet |  |  |  |  |
| [Dismemberment (Plus)](https://steamcommunity.com/sharedfiles/filedetails/?id=2875093027) | Not checked yet | 3 works, 0 broken | 2026-11-13 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Works in Coop. The host and every player need the same version. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Distinguished Service](https://steamcommunity.com/sharedfiles/filedetails/?id=2891413076) | Not checked yet |  |  |  |  |
| [Donate Food To Settlement](https://steamcommunity.com/sharedfiles/filedetails/?id=3669537268) | Not checked yet |  |  |  |  |
| [Dro's Lighting Improvements](https://www.nexusmods.com/mountandblade2bannerlord/mods/6) | Not checked yet |  |  |  |  |
| [DynaCulture](https://steamcommunity.com/sharedfiles/filedetails/?id=2880997722) | Not checked yet |  |  |  |  |
| [DynamicTroopReupload](https://steamcommunity.com/sharedfiles/filedetails/?id=3119116807) | Not checked yet |  |  |  |  |
| [Earn Your Banner](https://www.nexusmods.com/mountandblade2bannerlord/mods/3965) | Not checked yet |  |  |  |  |
| [East_Asia_Map](https://steamcommunity.com/sharedfiles/filedetails/?id=3303418136) | Not checked yet |  |  |  |  |
| [Eastern Europe 1259](https://www.nexusmods.com/mountandblade2bannerlord/mods/6724) | Not checked yet |  |  |  |  |
| [Easy Respec](https://steamcommunity.com/sharedfiles/filedetails/?id=3472042786) | Not checked yet |  |  |  |  |
| [Easy Weapon Pickup](https://steamcommunity.com/sharedfiles/filedetails/?id=3277864687) | Not checked yet |  |  |  |  |
| [EditLord Troops Inventory Settlement Character Editor](https://www.nexusmods.com/mountandblade2bannerlord/mods/1246) | Not checked yet |  |  |  |  |
| [Education](https://www.nexusmods.com/mountandblade2bannerlord/mods/5157) | Not checked yet |  |  |  |  |
| [Elite Mercenaries](https://steamcommunity.com/sharedfiles/filedetails/?id=2883108405) | Not checked yet |  |  |  |  |
| [Elite Mercenaries Expanded](https://steamcommunity.com/sharedfiles/filedetails/?id=2928812888) | Not checked yet |  |  |  |  |
| [Elite trooper expand](https://steamcommunity.com/sharedfiles/filedetails/?id=2875307298) | Not checked yet |  |  |  |  |
| [Enable Achievement](https://steamcommunity.com/sharedfiles/filedetails/?id=2880190747) | Not checked yet | 1 works, 0 broken | 2026-11-01 |  |  |
| [Encyclopedia Extender](https://steamcommunity.com/sharedfiles/filedetails/?id=2875180306) | Not checked yet |  |  |  |  |
| [Encyclopedia Extender Reforged](https://steamcommunity.com/sharedfiles/filedetails/?id=2953564744) | Not checked yet | 1 works, 0 broken | 2026-10-24 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Encyclopedia Filters Extended](https://steamcommunity.com/sharedfiles/filedetails/?id=2916000111) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Enlisted](https://www.nexusmods.com/mountandblade2bannerlord/mods/9193) | Not checked yet |  |  |  |  |
| [Enter Castle/Town With Horse](https://steamcommunity.com/sharedfiles/filedetails/?id=2883598274) | Not checked yet |  |  |  |  |
| [EOE Horse Armoury](https://steamcommunity.com/sharedfiles/filedetails/?id=3381125189) | Not checked yet |  |  |  |  |
| [EOE Weaponry](https://steamcommunity.com/sharedfiles/filedetails/?id=3381128526) | Not checked yet |  |  |  |  |
| [EOE_Armoury](https://steamcommunity.com/sharedfiles/filedetails/?id=3372040868) | Not checked yet |  |  |  |  |
| [Equip Best Item](https://www.nexusmods.com/mountandblade2bannerlord/mods/369) | Not checked yet |  |  |  |  |
| [Europe Campaign Map](https://www.nexusmods.com/mountandblade2bannerlord/mods/3758) | Not checked yet |  |  |  |  |
| [Execution Adjuster](https://steamcommunity.com/sharedfiles/filedetails/?id=3268203914) | Not checked yet |  |  |  |  |
| [Expanded Bannerlord Armoury RBM](https://www.nexusmods.com/mountandblade2bannerlord/mods/5327) | Not checked yet |  |  |  |  |
| [Expanded Elite Troops](https://steamcommunity.com/sharedfiles/filedetails/?id=2993061377) | Not checked yet |  |  |  |  |
| [Extra Banners](https://steamcommunity.com/sharedfiles/filedetails/?id=3251872472) | Not checked yet |  |  |  |  |
| [Family Control](https://www.nexusmods.com/mountandblade2bannerlord/mods/2813) | Not checked yet |  |  |  |  |
| [Family Tree](https://steamcommunity.com/sharedfiles/filedetails/?id=2959469806) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Fast Dialogue](https://steamcommunity.com/sharedfiles/filedetails/?id=3034083929) | Not checked yet |  |  |  |  |
| [Fast UI - Inventory and Party](https://www.nexusmods.com/mountandblade2bannerlord/mods/9582) | Not checked yet |  |  |  | Updated for Bannerlord 1.4.8 and 1.5.3; the author asks for Coop testing. Not tested in Coop yet. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [Faster Child Growth](https://steamcommunity.com/sharedfiles/filedetails/?id=3618489007) | Not checked yet |  |  |  |  |
| Faster Construction | Not checked yet | 0 works, 1 broken | 2026-11-16 |  |  |
| [Fate Jeanne d'Arc](https://steamcommunity.com/sharedfiles/filedetails/?id=3251246582) | Not checked yet |  |  |  |  |
| [Female Troops Simplified](https://steamcommunity.com/sharedfiles/filedetails/?id=2945030198) | Not checked yet |  |  |  |  |
| [Fighting Together Relationship](https://www.nexusmods.com/mountandblade2bannerlord/mods/463) | Not checked yet |  |  |  |  |
| [Finer Party Controls (FPC)](https://steamcommunity.com/sharedfiles/filedetails/?id=3685593525) | Not checked yet |  |  |  |  |
| [Fire Arrow Enabler](https://www.nexusmods.com/mountandblade2bannerlord/mods/472) | Not checked yet |  |  |  |  |
| [Fire Arrows - Arrow Volley](https://steamcommunity.com/sharedfiles/filedetails/?id=3542272439) | Not checked yet |  |  |  |  |
| [Fire Lord](https://www.nexusmods.com/mountandblade2bannerlord/mods/795) | Not checked yet |  |  |  |  |
| ForgeMaster | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. BannerCraft, ForgeMaster and Modular Smithing 2 work together. With all three the Smelt tab gets stuck; switch tabs with Q and E. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Fourberie](https://steamcommunity.com/sharedfiles/filedetails/?id=2875710877) | Not checked yet |  |  |  |  |
| [Frugal Cavalry](https://www.nexusmods.com/mountandblade2bannerlord/mods/196) | Not checked yet |  |  |  |  |
| [Game Crash Skipper](https://steamcommunity.com/sharedfiles/filedetails/?id=3642009240) | Not checked yet |  |  |  |  |
| [GameMaster](https://steamcommunity.com/sharedfiles/filedetails/?id=3624152079) | Not checked yet |  |  |  |  |
| [Garrison Do Something](https://www.nexusmods.com/mountandblade2bannerlord/mods/3338) | Not checked yet |  |  |  |  |
| [Gay Marriage](https://www.nexusmods.com/mountandblade2bannerlord/mods/14) | Not checked yet |  |  |  |  |
| [Give Troops To Notables](https://steamcommunity.com/sharedfiles/filedetails/?id=3152935214) | Not checked yet |  |  |  |  |
| [GoT Westeros Armory](https://www.nexusmods.com/mountandblade2bannerlord/mods/3469) | Not checked yet |  |  |  |  |
| [Governors Handle Issues](https://steamcommunity.com/sharedfiles/filedetails/?id=2875226388) | Not checked yet |  |  |  |  |
| [Grow Up And Work](https://www.nexusmods.com/mountandblade2bannerlord/mods/544) | Not checked yet |  |  |  |  |
| [Hairstyles dlx](https://www.nexusmods.com/mountandblade2bannerlord/mods/4762) | Not checked yet |  |  |  |  |
| [Harmony](https://steamcommunity.com/sharedfiles/filedetails/?id=2859188632) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Library other mods need. It stays on the list; its menus do not run on the dedicated server. |
| Harvest And Production | Not checked yet |  |  |  | Asked about in the thread; not tested in Coop yet. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08. |
| [Hats and Stuff](https://www.nexusmods.com/mountandblade2bannerlord/mods/4065) | Not checked yet |  |  |  |  |
| [Heal on Kill](https://steamcommunity.com/sharedfiles/filedetails/?id=2875223027) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Turn off AI heal on kill in its settings; it can desync battles. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Heal on Still](https://steamcommunity.com/sharedfiles/filedetails/?id=3495544611) | Not checked yet |  |  |  |  |
| [Helmet Hair Cover Continued Base](https://steamcommunity.com/sharedfiles/filedetails/?id=2875645009) | Not checked yet |  |  |  |  |
| [Helmet Hair Cover Continued Plus](https://steamcommunity.com/sharedfiles/filedetails/?id=2875645408) | Not checked yet |  |  |  |  |
| [Helmet Hair Cover Tweaks Expanded](https://steamcommunity.com/sharedfiles/filedetails/?id=3482852301) | Not checked yet |  |  |  |  |
| [Hideout Player Party Limit Removed](https://www.nexusmods.com/mountandblade2bannerlord/mods/35) | Not checked yet |  |  |  |  |
| [Hideout Plus](https://steamcommunity.com/sharedfiles/filedetails/?id=2879876957) | Not checked yet |  |  |  |  |
| [High Middle Ages Calradia](https://steamcommunity.com/sharedfiles/filedetails/?id=2917750875) | Not checked yet |  |  |  |  |
| [Historical Banner Icons](https://steamcommunity.com/sharedfiles/filedetails/?id=2990327671) | Not checked yet | 1 works, 0 broken | 2026-10-25 |  |  |
| [Historical Name Expansion](https://steamcommunity.com/sharedfiles/filedetails/?id=3115155002) | Not checked yet |  |  |  |  |
| [Hold Court](https://www.nexusmods.com/mountandblade2bannerlord/mods/5522) | Not checked yet |  |  |  |  |
| [Homesteads](https://www.nexusmods.com/mountandblade2bannerlord/mods/5627) | Not checked yet |  |  |  |  |
| [Horde Kingdom](https://steamcommunity.com/sharedfiles/filedetails/?id=3676690880) | Not checked yet |  |  |  |  |
| [Horse Caparisons](https://www.nexusmods.com/mountandblade2bannerlord/mods/2653) | Not checked yet |  |  |  |  |
| [Horses](https://www.nexusmods.com/mountandblade2bannerlord/mods/6230) | Not checked yet |  |  |  |  |
| [Hot Butter](https://www.nexusmods.com/mountandblade2bannerlord/mods/4276) | Not checked yet |  |  |  |  |
| [HotScenes](https://www.nexusmods.com/mountandblade2bannerlord/mods/10103) | Not checked yet |  |  |  |  |
| [Houses of Calradia](https://www.nexusmods.com/mountandblade2bannerlord/mods/2174) | Not checked yet |  |  |  |  |
| [I Don't Care - Campaign Log Filter](https://steamcommunity.com/sharedfiles/filedetails/?id=2875076661) | Not checked yet |  |  |  |  |
| [Immersive Battlefields](https://www.nexusmods.com/mountandblade2bannerlord/mods/4633) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Comes with the Coodsz tools. Battle looks only. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Immersive Storms](https://steamcommunity.com/sharedfiles/filedetails/?id=3626222686) | Not checked yet |  |  |  |  |
| [Improve the Economy](https://steamcommunity.com/sharedfiles/filedetails/?id=3457854001) | Not checked yet |  |  |  |  |
| [Improved Camels](https://steamcommunity.com/sharedfiles/filedetails/?id=2883767340) | Not checked yet |  |  |  |  |
| [Improved Camels and Larger Camels](https://steamcommunity.com/sharedfiles/filedetails/?id=2883626855) | Not checked yet |  |  |  |  |
| [Improved Economy For AI Lords](https://www.nexusmods.com/mountandblade2bannerlord/mods/8698) | Not checked yet |  |  |  |  |
| [Improved Garrisons](https://steamcommunity.com/sharedfiles/filedetails/?id=2859265386) | Not checked yet | 2 works, 0 broken | 2026-11-13 | v0.1.5 | Improved Garrisons 4.3.1.0 has a Bannerlord 1.5.7 build. Coop 0.1.8 compatibility is unverified. Older CoopModPatch tests found map desync and repeated garrison wage changes. |
| [InstantDeath](https://steamcommunity.com/sharedfiles/filedetails/?id=2968906225) | Not checked yet |  |  |  |  |
| [Internal Diplomacy](https://steamcommunity.com/sharedfiles/filedetails/?id=3413784587) | Not checked yet |  |  |  |  |
| Inventory Search Enabler | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Item Fixer](https://www.nexusmods.com/mountandblade2bannerlord/mods/40) | Not checked yet |  |  |  |  |
| [Item Quality Indicator](https://steamcommunity.com/sharedfiles/filedetails/?id=3674878917) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| ItemQualityVisuals | Not checked yet | 1 works, 0 broken | 2026-10-24 |  |  |
| [Kaoses Parties Sizes](https://www.nexusmods.com/mountandblade2bannerlord/mods/684) | Not checked yet |  |  |  |  |
| [Kaoses Tweaks](https://www.nexusmods.com/mountandblade2bannerlord/mods/3503) | Not checked yet |  |  |  |  |
| [Keep Your Clan Members After Marriage](https://steamcommunity.com/sharedfiles/filedetails/?id=3620861063) | Not checked yet |  |  |  |  |
| [Keep Your Daughters](https://steamcommunity.com/sharedfiles/filedetails/?id=2945303045) | Not checked yet |  |  |  |  |
| [Kenshi Armours](https://steamcommunity.com/sharedfiles/filedetails/?id=3257438841) | Not checked yet |  |  |  |  |
| [Kenshi Weapons](https://steamcommunity.com/sharedfiles/filedetails/?id=3234253089) | Not checked yet |  |  |  |  |
| [Kill Bandits Raise Relations](https://www.nexusmods.com/mountandblade2bannerlord/mods/500) | Not checked yet |  |  |  |  |
| [Kill Counters](https://steamcommunity.com/sharedfiles/filedetails/?id=2875190917) | Not checked yet |  |  |  |  |
| [Kingdom Annexation](https://steamcommunity.com/sharedfiles/filedetails/?id=2890216380) | Not checked yet |  |  |  |  |
| [Kingdom Politics Expanded](https://steamcommunity.com/sharedfiles/filedetails/?id=2910947065) | Not checked yet |  |  |  |  |
| [Kingdom Strategies Command](https://steamcommunity.com/sharedfiles/filedetails/?id=3296120093) | Not checked yet |  |  |  |  |
| [KingdomDecay](https://steamcommunity.com/sharedfiles/filedetails/?id=2888285980) | Not checked yet |  |  |  |  |
| [Knight Rising](https://steamcommunity.com/sharedfiles/filedetails/?id=3472927396) | Not checked yet |  |  |  |  |
| [Knights of Vlandia](https://steamcommunity.com/sharedfiles/filedetails/?id=2892362757) | Not checked yet |  |  |  |  |
| [Knocked Down Heroes Influences Troops](https://www.nexusmods.com/mountandblade2bannerlord/mods/7955) | Not checked yet |  |  |  |  |
| [Larger Horses](https://steamcommunity.com/sharedfiles/filedetails/?id=2884218327) | Not checked yet |  |  |  |  |
| [Larger Horses for RBM](https://steamcommunity.com/sharedfiles/filedetails/?id=2888533161) | Not checked yet |  |  |  |  |
| [Leave on Click](https://steamcommunity.com/sharedfiles/filedetails/?id=2875194175) | Not checked yet |  |  |  |  |
| Legend Training Arena | Not checked yet |  |  | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. By Sannech, made for Bannerlord 1.4.8 and Coop 0.1.6. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08. |
| [Legionaires Throw Pila](https://steamcommunity.com/sharedfiles/filedetails/?id=2888899050) | Not checked yet |  |  |  |  |
| [LimitlessMarket](https://steamcommunity.com/sharedfiles/filedetails/?id=3031250038) | Not checked yet |  |  |  |  |
| Lively Animations | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Not fully synced between players, and the server can take 30 minutes or more to start. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| [LogRaam's Full Body Sliders](https://www.nexusmods.com/mountandblade2bannerlord/mods/2045) | Not checked yet |  |  |  |  |
| [Longer and Bigger Crafting Parts with Uniform Scaling](https://steamcommunity.com/sharedfiles/filedetails/?id=2887434433) | Not checked yet |  |  |  |  |
| [LootEveryone](https://www.nexusmods.com/mountandblade2bannerlord/mods/535) | Not checked yet |  |  |  |  |
| [Lowborn](https://steamcommunity.com/sharedfiles/filedetails/?id=3653125474) | Not checked yet |  |  |  |  |
| [Machination](https://steamcommunity.com/sharedfiles/filedetails/?id=3644127631) | Not checked yet |  |  |  |  |
| [Malfoy Collection](https://www.nexusmods.com/mountandblade2bannerlord/mods/5356) | Not checked yet |  |  |  |  |
| [Marriage and Fertility](https://steamcommunity.com/sharedfiles/filedetails/?id=3177450219) | Not checked yet |  |  |  |  |
| [Marriage Offers For Player](https://steamcommunity.com/sharedfiles/filedetails/?id=3620695688) | Not checked yet |  |  |  |  |
| [Marry Anyone](https://steamcommunity.com/sharedfiles/filedetails/?id=3035615782) | Not checked yet |  |  |  |  |
| [Mav's Expand Your Clan](https://www.nexusmods.com/mountandblade2bannerlord/mods/6256) | Not checked yet |  |  |  |  |
| [Max Attribute](https://steamcommunity.com/sharedfiles/filedetails/?id=2883725695) | Not checked yet |  |  |  |  |
| [MeetingEveryone](https://steamcommunity.com/sharedfiles/filedetails/?id=3029015334) | Not checked yet |  |  |  |  |
| [Megacles The Sultans Wonderkid](https://steamcommunity.com/sharedfiles/filedetails/?id=2885413419) | Not checked yet |  |  |  |  |
| [Mercenary Counter-Offers](https://steamcommunity.com/sharedfiles/filedetails/?id=3634850795) | Not checked yet |  |  |  |  |
| [Minor Faction Recruits](https://steamcommunity.com/sharedfiles/filedetails/?id=3031750545) | Not checked yet |  |  |  |  |
| [Missing Hair Fix](https://www.nexusmods.com/mountandblade2bannerlord/mods/6307) | Not checked yet |  |  |  |  |
| [Mix and Match Weapon Pack](https://www.nexusmods.com/mountandblade2bannerlord/mods/3780) | Not checked yet |  |  |  |  |
| [Mixed Gender Troops](https://www.nexusmods.com/mountandblade2bannerlord/mods/12) | Not checked yet |  |  |  |  |
| [MixMashChineseFantasyArmorPack](https://steamcommunity.com/sharedfiles/filedetails/?id=3167500438) | Not checked yet |  |  |  |  |
| [Mod Configuration Menu (MCM)](https://www.nexusmods.com/mountandblade2bannerlord/mods/612) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.6 | MCM 5.13.1 has a Bannerlord 1.5.7 build. Host settings sync with Coop 0.1.8 is unverified. |
| [ModLib](https://www.nexusmods.com/mountandblade2bannerlord/mods/592) | Not checked yet |  |  |  |  |
| Modular Smithing 2 | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. BannerCraft, ForgeMaster and Modular Smithing 2 work together. With all three the Smelt tab gets stuck; switch tabs with Q and E. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [MolochsDuels](https://steamcommunity.com/sharedfiles/filedetails/?id=2880161030) | Not checked yet |  |  |  |  |
| [Mordhau Voices in battle](https://www.nexusmods.com/mountandblade2bannerlord/mods/5925) | Not checked yet |  |  |  |  |
| [More Battle Shouts](https://steamcommunity.com/sharedfiles/filedetails/?id=3622146187) | Not checked yet |  |  |  |  |
| [More Countries](https://steamcommunity.com/sharedfiles/filedetails/?id=2885064873) | Not checked yet |  |  |  |  |
| [More Hero Interactions](https://www.nexusmods.com/mountandblade2bannerlord/mods/5002) | Not checked yet |  |  |  |  |
| [More Income and More Production](https://www.nexusmods.com/mountandblade2bannerlord/mods/2597) | Not checked yet |  |  |  |  |
| More Nations Remastered | Not checked yet |  |  | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Map mod on the Coodsz Host working list. Use it with MoreNationsRemastered COOP Fix. |
| [More Prisoner Interactions](https://www.nexusmods.com/mountandblade2bannerlord/mods/5076) | Not checked yet |  |  |  |  |
| [More Raiding - A Raiding and Mayhem Mod](https://www.nexusmods.com/mountandblade2bannerlord/mods/389) | Not checked yet |  |  |  |  |
| [More Tavern Companions](https://steamcommunity.com/sharedfiles/filedetails/?id=3647615254) | Not checked yet |  |  |  |  |
| [More Trait Info](https://steamcommunity.com/sharedfiles/filedetails/?id=2961485825) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [More Troops Mod](https://www.nexusmods.com/mountandblade2bannerlord/mods/2121) | Not checked yet |  |  |  |  |
| [MoreArenas](https://steamcommunity.com/sharedfiles/filedetails/?id=2875080792) | Not checked yet |  |  |  |  |
| [MoreCompanionFresh](https://steamcommunity.com/sharedfiles/filedetails/?id=3025870331) | Not checked yet |  |  |  |  |
| MoreNationsRemastered COOP Fix | Not checked yet |  |  | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. The Coop fix for More Nations Remastered. Use both together. |
| [Morgana The Chosen One](https://steamcommunity.com/sharedfiles/filedetails/?id=2885179107) | Not checked yet |  |  |  |  |
| [My Little Warband](https://steamcommunity.com/sharedfiles/filedetails/?id=3627538517) | Not checked yet |  |  | v0.1.7 | Tested on 0.1.7 / 1.4.8, not yet on 0.1.8. The older setup used My Little Warband v1.2.6/1.4.6 and CoopModPatch. Two players verified troop editing and custom recruiting with the former Coop and Friends Server Tool v1.3.13. Actual recruit prices could exceed the price shown. |
| [Native Female Troops](https://steamcommunity.com/sharedfiles/filedetails/?id=2884724013) | Not checked yet |  |  |  |  |
| [Nicanor The Steppe Nomad](https://steamcommunity.com/sharedfiles/filedetails/?id=2887553628) | Not checked yet |  |  |  |  |
| [No Companion Limit](https://steamcommunity.com/sharedfiles/filedetails/?id=3645166294) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [No Smithing Stamina Cost](https://steamcommunity.com/sharedfiles/filedetails/?id=3582354036) | Not checked yet |  |  |  |  |
| [No Time Limit](https://steamcommunity.com/sharedfiles/filedetails/?id=2882021409) | Not checked yet |  |  |  |  |
| [NoArmyRestriction](https://www.nexusmods.com/mountandblade2bannerlord/mods/3537) | Not checked yet |  |  |  |  |
| [Noble Nobles - Total Npc Makeover](https://www.nexusmods.com/mountandblade2bannerlord/mods/194) | Not checked yet |  |  |  |  |
| [Noble Titles](https://www.nexusmods.com/mountandblade2bannerlord/mods/2089) | Not checked yet |  |  |  |  |
| [Noble Troops](https://www.nexusmods.com/mountandblade2bannerlord/mods/202) | Not checked yet |  |  |  |  |
| Noble Troops Fix | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Seems to work; troop stats can look odd. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Noble Village Icons](https://www.nexusmods.com/mountandblade2bannerlord/mods/7957) | Not checked yet |  |  |  |  |
| [Nords of Sturgia](https://steamcommunity.com/sharedfiles/filedetails/?id=2880215030) | Not checked yet |  |  |  |  |
| [NPC Fixes Collection - formerly No More Clones](https://www.nexusmods.com/mountandblade2bannerlord/mods/6204) | Not checked yet |  |  |  |  |
| [NPC Revamp](https://www.nexusmods.com/mountandblade2bannerlord/mods/21) | Not checked yet |  |  |  |  |
| Nuggets' Agriculture Estate and Xorberax Bank patch | Not checked yet |  |  |  | Legacy Coop setup. Support on 0.1.8 is unverified. Alternative Coop patch by Nuggets for Agriculture Estate and the Bank module of Xorberax's Legacy, posted on the Coop Discord (old 0.1.5 thread, #other-mods). Made for Coop 0.1.5 and not updated since; may clash with Zexui's CoopModPatch. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [Open Source Armory](https://steamcommunity.com/sharedfiles/filedetails/?id=3011479883) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Load Open Source Armory, then Saddlery, then Weaponry. If a player crashes on start, delete the mod's Shaders folder on that PC. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Open Source Saddlery](https://steamcommunity.com/sharedfiles/filedetails/?id=3010990914) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Load it after Open Source Armory and before Open Source Weaponry. If a player crashes on start, delete the mod's Shaders folder on that PC. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Open Source Weaponry](https://steamcommunity.com/sharedfiles/filedetails/?id=3010984416) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Load it after Open Source Armory and Saddlery. If a player crashes on start, delete the mod's Shaders folder on that PC. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Party AI Controls](https://steamcommunity.com/sharedfiles/filedetails/?id=3117962790) | Not checked yet |  |  |  |  |
| Party AI Controls Reforged | Not checked yet | 1 works, 0 broken | 2026-11-07 |  |  |
| [Party AI Overhaul and Commands](https://www.nexusmods.com/mountandblade2bannerlord/mods/493) | Not checked yet |  |  |  |  |
| [Party And Clan Limit Extender Shokuho](https://steamcommunity.com/sharedfiles/filedetails/?id=3514722516) | Not checked yet |  |  |  |  |
| [Party Screen Enhancements](https://steamcommunity.com/sharedfiles/filedetails/?id=2888739624) | Not checked yet |  |  |  |  |
| [Party Size Increase](https://steamcommunity.com/sharedfiles/filedetails/?id=2882678098) | Not checked yet |  |  |  |  |
| [PartyAndClanLimitExtender](https://steamcommunity.com/sharedfiles/filedetails/?id=3508555611) | Not checked yet |  |  |  |  |
| [PartySizeReunited](https://steamcommunity.com/sharedfiles/filedetails/?id=3372837208) | Not checked yet |  |  |  |  |
| [PeasantRevenge](https://steamcommunity.com/sharedfiles/filedetails/?id=2949132830) | Not checked yet |  |  |  |  |
| [Perfect Executioner](https://www.nexusmods.com/mountandblade2bannerlord/mods/3260) | Not checked yet |  |  |  |  |
| [Perfect Fire Arrows](https://www.nexusmods.com/mountandblade2bannerlord/mods/3303) | Not checked yet | 2 works, 0 broken | 2026-11-25 | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. On the Coodsz Host working list, run on Coop v0.1.6 servers. The host and every player need the same version. |
| [Performance Optimizer](https://steamcommunity.com/sharedfiles/filedetails/?id=3719370392) | Not checked yet |  |  |  |  |
| [Player Execution](https://www.nexusmods.com/mountandblade2bannerlord/mods/1210) | Not checked yet |  |  |  |  |
| [Player Governor](https://steamcommunity.com/sharedfiles/filedetails/?id=2945241650) | Not checked yet |  |  |  |  |
| [Player Selection Switch](https://www.nexusmods.com/mountandblade2bannerlord/mods/6522) | Not checked yet |  |  |  |  |
| [Player Settlement](https://steamcommunity.com/sharedfiles/filedetails/?id=3720376888) | Not checked yet | 1 works, 1 broken | 2026-11-01 | v0.1.6 | Legacy Coop setup. Support on 0.1.8 is unverified. Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Works in Coop with PSCoopBridge and Agriculture Estate on the server and every player. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [POC color randomizer mod](https://www.nexusmods.com/mountandblade2bannerlord/mods/792) | Not checked yet |  |  |  |  |
| [Pregnancy Control Continued](https://www.nexusmods.com/mountandblade2bannerlord/mods/5478) | Not checked yet |  |  |  |  |
| Procedural Scenes | Not checked yet | 0 works, 1 broken | 2026-11-08 |  |  |
| [Project Korea](https://steamcommunity.com/sharedfiles/filedetails/?id=2980304763) | Not checked yet |  |  |  |  |
| [Proven Steel](https://steamcommunity.com/sharedfiles/filedetails/?id=3691572079) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Works in Coop. Patch available: Proven Steel patch by mushymushymosh, load it below Proven Steel. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| Proven Steel patch | Not checked yet |  |  |  | Coop patch by mushymushymosh for Proven Steel, posted on the Coop Discord (Coop 0.1.6 thread). Load it below Proven Steel. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08. |
| [PSCoopBridge](https://steamcommunity.com/sharedfiles/filedetails/?id=3806860145) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.6 | Legacy bridge for Player Settlement and Agriculture Estate, made for older Coop releases. Support for Coop 0.1.8 is unverified. |
| [Quick Nearby Tournaments](https://steamcommunity.com/sharedfiles/filedetails/?id=2910268800) | Not checked yet | 1 works, 0 broken | 2026-10-25 |  |  |
| [Raise your Banner](https://www.nexusmods.com/mountandblade2bannerlord/mods/3253) | Not checked yet | 2 works, 0 broken | 2026-11-25 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Comes with the Coodsz tools. Load Banner Fix before it. For Coop 0.1.8 use the official Bannerlord Coop Dedicated Server Manager and apply this change only to the server copy. Players keep theirs, don't delete it. Might crash when another party joins a battle in progress (not confirmed). Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| [Raise your Torch](https://www.nexusmods.com/mountandblade2bannerlord/mods/3289) | Not checked yet | 2 works, 0 broken | 2026-11-25 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Comes with the Coodsz tools. Battle looks only. For Coop 0.1.8 use the official Bannerlord Coop Dedicated Server Manager and apply this change only to the server copy. Players keep theirs, don't delete it. Might crash when another party joins a battle in progress (not confirmed). Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| [Ralf's Recruiter](https://www.nexusmods.com/mountandblade2bannerlord/mods/575) | Not checked yet |  |  |  |  |
| [Ramsay's Stuff](https://www.nexusmods.com/mountandblade2bannerlord/mods/3494) | Not checked yet |  |  |  |  |
| [Random Bodies](https://www.nexusmods.com/mountandblade2bannerlord/mods/5168) | Not checked yet |  |  |  |  |
| [Random Events](https://steamcommunity.com/sharedfiles/filedetails/?id=2880127748) | Not checked yet |  |  |  |  |
| [RealBattleSize](https://steamcommunity.com/sharedfiles/filedetails/?id=2879343374) | Not checked yet |  |  |  |  |
| [Realistic Battle Mod War Sails Submod](https://steamcommunity.com/sharedfiles/filedetails/?id=3635788184) | Not checked yet |  |  |  |  |
| [Realistic Battle Sounds](https://steamcommunity.com/sharedfiles/filedetails/?id=2877035441) | Not checked yet |  |  |  |  |
| [Realistic Blood](https://www.nexusmods.com/mountandblade2bannerlord/mods/8328) | Not checked yet |  |  |  |  |
| [Realistic Combat Adjustments](https://www.nexusmods.com/mountandblade2bannerlord/mods/7116) | Not checked yet |  |  |  |  |
| [Realistic Combat Sounds](https://www.nexusmods.com/mountandblade2bannerlord/mods/3765) | Not checked yet |  |  |  |  |
| [Realistic Practical Holsters](https://www.nexusmods.com/mountandblade2bannerlord/mods/5935) | Not checked yet |  |  |  |  |
| [Realistic Weather](https://steamcommunity.com/sharedfiles/filedetails/?id=2862531759) | Not checked yet | 1 works, 0 broken | 2026-11-01 |  |  |
| [Rebuild Looted Villages Redux](https://www.nexusmods.com/mountandblade2bannerlord/mods/6304) | Not checked yet |  |  |  |  |
| [Recruit Everyone](https://steamcommunity.com/sharedfiles/filedetails/?id=2875837088) | Not checked yet |  |  |  |  |
| [Recruit Exiled Clans](https://steamcommunity.com/sharedfiles/filedetails/?id=3618730894) | Not checked yet |  |  |  |  |
| [Recruitable](https://www.nexusmods.com/mountandblade2bannerlord/mods/112) | Not checked yet |  |  |  |  |
| [Reign of Sword](https://www.nexusmods.com/mountandblade2bannerlord/mods/2221) | Not checked yet |  |  |  |  |
| [Reinforcement System](https://www.nexusmods.com/mountandblade2bannerlord/mods/6501) | Not checked yet |  |  |  |  |
| [Relentless Smith](https://steamcommunity.com/sharedfiles/filedetails/?id=2882064139) | Not checked yet |  |  |  |  |
| [Remove Fog of War](https://steamcommunity.com/sharedfiles/filedetails/?id=2956986632) | Not checked yet |  |  |  |  |
| [Rename Companions](https://steamcommunity.com/sharedfiles/filedetails/?id=2875725090) | Not checked yet |  |  |  |  |
| [Responsive Soldiers](https://www.nexusmods.com/mountandblade2bannerlord/mods/1136) | Not checked yet |  |  |  |  |
| [Retinues - Custom Clan and Kingdom Troops](https://steamcommunity.com/sharedfiles/filedetails/?id=3599557394) | Not checked yet |  |  |  | Not tested in Coop beyond the patch. Patch available: Retinues.CoopCompat by antezorica88, load it after Retinues. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| Retinues.CoopCompat | Not checked yet |  |  |  | Coop patch by antezorica88 for Retinues (v0.1.0, server and client zips), posted on the Coop Discord (old 0.1.5 thread, 2026-09-22). Made for Coop 0.1.5. Stops the player showing as a recruiter. Load it after Retinues. Not tested by others yet. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [Revolutions](https://www.nexusmods.com/mountandblade2bannerlord/mods/266) | Not checked yet |  |  |  |  |
| [Righteous Executions](https://www.nexusmods.com/mountandblade2bannerlord/mods/559) | Not checked yet |  |  |  |  |
| [Rii Mountain Blade - It's Sword of Long](https://steamcommunity.com/sharedfiles/filedetails/?id=3443071108) | Not checked yet |  |  |  |  |
| [Royal Privilege Extended](https://steamcommunity.com/sharedfiles/filedetails/?id=2888346548) | Not checked yet |  |  |  |  |
| [RTS Camera](https://steamcommunity.com/sharedfiles/filedetails/?id=3747725551) | Not checked yet | 1 works, 0 broken | 2026-11-24 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Opening its settings in a battle crashes the other player, and tournaments crash. Patch available: RTSCamera_Coop_Fixed for battle rewards, outdated. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| [RTS Camera Command System](https://steamcommunity.com/sharedfiles/filedetails/?id=3747771970) | Not checked yet | 1 works, 0 broken | 2026-11-24 | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Needs RTS Camera. On the Coodsz Host working list, run on Coop v0.1.6 servers. The host and every player need the same version. |
| [RTS Camera Universal - Community Edition](https://steamcommunity.com/sharedfiles/filedetails/?id=3743392231) | Not checked yet |  |  |  |  |
| RTSCamera_Coop_Fixed | Not checked yet |  |  |  | Fix by Sannech for RTS Camera rewards after battles, posted on the Coop Discord (old 0.1.5 thread, 2026-10-04). Made for Coop 0.1.5. Outdated: on 2026-10-17 Sannech said a new fix is needed. It never fixed the tournament crash. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [Ruler Always In Vote](https://steamcommunity.com/sharedfiles/filedetails/?id=3613539279) | Not checked yet |  |  |  |  |
| [Ruler Army Requisition](https://steamcommunity.com/sharedfiles/filedetails/?id=3617568764) | Not checked yet |  |  |  |  |
| [Rulership](https://www.nexusmods.com/mountandblade2bannerlord/mods/380) | Not checked yet |  |  |  |  |
| [Sarranid Armory](https://steamcommunity.com/sharedfiles/filedetails/?id=2875825696) | Not checked yet |  |  |  |  |
| [Scaling HP](https://steamcommunity.com/sharedfiles/filedetails/?id=3315562976) | Not checked yet |  |  |  |  |
| [ScatterAroundExpanded](https://steamcommunity.com/sharedfiles/filedetails/?id=2878964722) | Not checked yet |  |  |  |  |
| [Scipio The Centurion](https://steamcommunity.com/sharedfiles/filedetails/?id=2893589193) | Not checked yet |  |  |  |  |
| [Sell all but stop at zero](https://steamcommunity.com/sharedfiles/filedetails/?id=2907309923) | Not checked yet |  |  |  |  |
| [Separatism](https://steamcommunity.com/sharedfiles/filedetails/?id=2890977393) | Not checked yet |  |  |  |  |
| [Serve as Soldier](https://www.nexusmods.com/mountandblade2bannerlord/mods/3242) | Not checked yet |  |  |  |  |
| [Settlement Culture Changer](https://www.nexusmods.com/mountandblade2bannerlord/mods/2768) | Not checked yet |  |  |  |  |
| [Settlement Culture Drift](https://steamcommunity.com/sharedfiles/filedetails/?id=3777470096) | Not checked yet | 1 works, 0 broken | 2026-10-26 | v0.1.6 | Legacy Coop setup. Support on 0.1.8 is unverified. Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. On the Coodsz Host working list, run on Coop v0.1.6 servers. The host and every player need the same version. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [Settlement Icons](https://www.nexusmods.com/mountandblade2bannerlord/mods/429) | Not checked yet |  |  |  |  |
| [Settlement Icons - Redesign](https://www.nexusmods.com/mountandblade2bannerlord/mods/2717) | Not checked yet |  |  |  |  |
| Settlement Map | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Shadow Tweaks](https://www.nexusmods.com/mountandblade2bannerlord/mods/7259) | Not checked yet |  |  |  |  |
| [Shields - They Block Things](https://www.nexusmods.com/mountandblade2bannerlord/mods/3729) | Not checked yet |  |  |  |  |
| [Shokuho - Dreams of Legends](https://steamcommunity.com/sharedfiles/filedetails/?id=3648244233) | Not checked yet |  |  |  |  |
| [Shokuho - Text Patch](https://steamcommunity.com/sharedfiles/filedetails/?id=3530170831) | Not checked yet |  |  |  |  |
| [Show Skill Limit](https://www.nexusmods.com/mountandblade2bannerlord/mods/9209) | Not checked yet |  |  |  |  |
| [Simple Bank](https://steamcommunity.com/sharedfiles/filedetails/?id=2886479768) | Not checked yet |  |  |  |  |
| [Simple RTS Camera](https://steamcommunity.com/sharedfiles/filedetails/?id=2875187184) | Not checked yet |  |  |  |  |
| [SimpleRegen](https://steamcommunity.com/sharedfiles/filedetails/?id=3162631292) | Not checked yet |  |  |  |  |
| [SimpleSiegeAmmo](https://steamcommunity.com/sharedfiles/filedetails/?id=3167409012) | Not checked yet |  |  |  |  |
| [Smith Forever](https://www.nexusmods.com/mountandblade2bannerlord/mods/41) | Not checked yet |  |  |  |  |
| [Smith Stamina Regen Anywhere](https://steamcommunity.com/sharedfiles/filedetails/?id=2886361563) | Not checked yet |  |  |  |  |
| [Smithy Workshop Tweak](https://steamcommunity.com/sharedfiles/filedetails/?id=2880604887) | Not checked yet |  |  |  |  |
| [Snowballing Kingdoms - EOE 1100](https://steamcommunity.com/sharedfiles/filedetails/?id=3413432422) | Not checked yet |  |  |  |  |
| [Special Troops Plus](https://steamcommunity.com/sharedfiles/filedetails/?id=2875905594) | Not checked yet |  |  |  |  |
| [Star-Sucking Skill](https://steamcommunity.com/sharedfiles/filedetails/?id=3274384214) | Not checked yet |  |  |  |  |
| [Stop Starving Yourselves](https://steamcommunity.com/sharedfiles/filedetails/?id=2920954993) | Not checked yet |  |  |  |  |
| [Super Speed](https://steamcommunity.com/sharedfiles/filedetails/?id=2875225186) | Not checked yet |  |  |  |  |
| [Supply Lines](https://www.nexusmods.com/mountandblade2bannerlord/mods/2266) | Not checked yet |  |  |  |  |
| [Surrender Tweaks](https://steamcommunity.com/sharedfiles/filedetails/?id=2859900052) | Not checked yet |  |  |  |  |
| [Swadian Armoury](https://steamcommunity.com/sharedfiles/filedetails/?id=2875090166) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. If a player crashes on start, delete the mod's Shaders folder on that PC. With RBM, use the matching RBM patch. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Swadian Armoury RBM](https://steamcommunity.com/sharedfiles/filedetails/?id=2883563167) | Not checked yet |  |  |  |  |
| [Tales from the Age of Men](https://www.nexusmods.com/mountandblade2bannerlord/mods/7748) | Not checked yet |  |  |  |  |
| Tavern Recruiters | Not checked yet |  |  | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. By Sannech, made for Coop (Bannerlord 1.4.8 and Coop 0.1.6). Hire troops through the tavern; the server sets it up in its .json config. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [Taverns Extended](https://www.nexusmods.com/mountandblade2bannerlord/mods/6109) | Not checked yet |  |  |  |  |
| [Telepathy](https://steamcommunity.com/sharedfiles/filedetails/?id=2890978557) | Not checked yet |  |  |  |  |
| [Templar Armor](https://www.nexusmods.com/mountandblade2bannerlord/mods/4736) | Not checked yet |  |  |  |  |
| [Tetsojin](https://steamcommunity.com/sharedfiles/filedetails/?id=3032471634) | Not checked yet |  |  |  |  |
| [The Conjunction of Spheres Armory](https://www.nexusmods.com/mountandblade2bannerlord/mods/6159) | Not checked yet |  |  |  |  |
| [The Old Realms - Armory Hair Submod](https://steamcommunity.com/sharedfiles/filedetails/?id=3356390449) | Not checked yet |  |  |  |  |
| [The Old Realms - Career Quests](https://steamcommunity.com/sharedfiles/filedetails/?id=3733626140) | Not checked yet |  |  |  |  |
| [The Sacred Goddesses - Guardians of the Nile](https://www.nexusmods.com/mountandblade2bannerlord/mods/6523) | Not checked yet |  |  |  |  |
| [TheCulturePolice](https://steamcommunity.com/sharedfiles/filedetails/?id=3039533535) | Not checked yet |  |  |  |  |
| [Thinks](https://steamcommunity.com/sharedfiles/filedetails/?id=3685592966) | Not checked yet |  |  |  |  |
| [Thusnelda The Barbarian](https://steamcommunity.com/sharedfiles/filedetails/?id=2893681873) | Not checked yet |  |  |  |  |
| [Tier 7 Troop Unlocker](https://www.nexusmods.com/mountandblade2bannerlord/mods/4205) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Seems to work; troop stats can look odd. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [TodayWeFeast](https://steamcommunity.com/sharedfiles/filedetails/?id=2880159950) | Not checked yet |  |  |  |  |
| [TOR Artillery Patcher](https://steamcommunity.com/sharedfiles/filedetails/?id=3723975221) | Not checked yet |  |  |  |  |
| [Total War Music](https://steamcommunity.com/sharedfiles/filedetails/?id=3404180590) | Not checked yet |  |  |  |  |
| [Tournament Prize Scaling](https://steamcommunity.com/sharedfiles/filedetails/?id=3695836576) | Not checked yet |  |  |  |  |
| [Tournaments Give Full XP](https://steamcommunity.com/sharedfiles/filedetails/?id=2875313806) | Not checked yet |  |  |  |  |
| [Tournaments XPanded](https://steamcommunity.com/sharedfiles/filedetails/?id=2892151112) | Not checked yet | 0 works, 1 broken | 2026-10-25 |  |  |
| TournamentTracker | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Traders' Infinite Wealth](https://steamcommunity.com/sharedfiles/filedetails/?id=3000052862) | Not checked yet |  |  |  |  |
| [Train Troops with Leadership and Level](https://steamcommunity.com/sharedfiles/filedetails/?id=2881012899) | Not checked yet |  |  |  |  |
| [Troop Collision and siege tower and castle stairs fix](https://www.nexusmods.com/mountandblade2bannerlord/mods/495) | Not checked yet |  |  |  |  |
| [Troop Designer](https://steamcommunity.com/sharedfiles/filedetails/?id=3618618171) | Not checked yet |  |  |  |  |
| [Troop Editor](https://steamcommunity.com/sharedfiles/filedetails/?id=3448788740) | Not checked yet |  |  |  |  |
| [Troop Sorting](https://steamcommunity.com/sharedfiles/filedetails/?id=2886676221) | Not checked yet |  |  |  |  |
| [Troops Prefer Spears](https://steamcommunity.com/sharedfiles/filedetails/?id=3320802782) | Not checked yet |  |  |  |  |
| [True Army Costs](https://www.nexusmods.com/mountandblade2bannerlord/mods/3384) | Not checked yet |  |  |  |  |
| [True Battle Loot](https://www.nexusmods.com/mountandblade2bannerlord/mods/3365) | Not checked yet |  |  |  |  |
| [True Controller](https://www.nexusmods.com/mountandblade2bannerlord/mods/3543) | Not checked yet |  |  |  |  |
| [True Limits](https://www.nexusmods.com/mountandblade2bannerlord/mods/2091) | Not checked yet |  |  |  |  |
| [True Relations](https://www.nexusmods.com/mountandblade2bannerlord/mods/2000) | Not checked yet |  |  |  |  |
| [True Town Gold](https://www.nexusmods.com/mountandblade2bannerlord/mods/3544) | Not checked yet |  |  |  |  |
| [Tutelage](https://steamcommunity.com/sharedfiles/filedetails/?id=2897212014) | Not checked yet |  |  |  |  |
| [Twins](https://steamcommunity.com/sharedfiles/filedetails/?id=2887740268) | Not checked yet |  |  |  |  |
| [UFO's Cheat Mods Bundle](https://steamcommunity.com/sharedfiles/filedetails/?id=3583201039) | Not checked yet |  |  |  |  |
| UI Mount Types Summary | Not checked yet | 1 works, 0 broken | 2026-11-18 | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Interface mod; works in Coop. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [UIExtenderEx](https://steamcommunity.com/sharedfiles/filedetails/?id=2859222409) | Not checked yet | 1 works, 0 broken | 2026-11-13 | v0.1.6 | Older Coop evidence (v0.1.6). Not yet tested on 0.1.8. Library other mods need. It stays on the list; its menus do not run on the dedicated server. |
| [Ultimate Mounts - REFORGED](https://www.nexusmods.com/mountandblade2bannerlord/mods/2906) | Not checked yet |  |  |  |  |
| [Universal Auto Equipment](https://steamcommunity.com/sharedfiles/filedetails/?id=3528052188) | Not checked yet |  |  |  |  |
| [Unlanded Clans](https://www.nexusmods.com/mountandblade2bannerlord/mods/5197) | Not checked yet |  |  |  |  |
| [Unlimited Max Attribute](https://steamcommunity.com/sharedfiles/filedetails/?id=2884623310) | Not checked yet |  |  |  |  |
| [Unlimited Party Size](https://steamcommunity.com/sharedfiles/filedetails/?id=2884742048) | Not checked yet |  |  |  |  |
| [Unlimited Skill Growth](https://steamcommunity.com/sharedfiles/filedetails/?id=3629637305) | Not checked yet |  |  |  |  |
| [Unlimited Smithing Stamina](https://steamcommunity.com/sharedfiles/filedetails/?id=3728678212) | Not checked yet |  |  |  |  |
| [UnlimitedCAP](https://steamcommunity.com/sharedfiles/filedetails/?id=2885762785) | Not checked yet |  |  |  |  |
| [UnlimitedPS](https://steamcommunity.com/sharedfiles/filedetails/?id=2885902416) | Not checked yet |  |  |  |  |
| [Upgradable Militia and Merchants](https://steamcommunity.com/sharedfiles/filedetails/?id=3559038567) | Not checked yet |  |  |  |  |
| [Upgrade Your Equipment](https://steamcommunity.com/sharedfiles/filedetails/?id=2955909085) | Not checked yet |  |  |  |  |
| [Useful Companions](https://steamcommunity.com/sharedfiles/filedetails/?id=2902899268) | Not checked yet |  |  |  |  |
| [Useful Skips](https://www.nexusmods.com/mountandblade2bannerlord/mods/4896) | Not checked yet |  |  |  |  |
| [V's No Player Army Size Limit](https://www.nexusmods.com/mountandblade2bannerlord/mods/124) | Not checked yet |  |  |  |  |
| [V's No Player Clan Party Limit](https://www.nexusmods.com/mountandblade2bannerlord/mods/125) | Not checked yet |  |  |  |  |
| [V's No Workshop Limit](https://www.nexusmods.com/mountandblade2bannerlord/mods/84) | Not checked yet |  |  |  |  |
| [Vaegir Armoury](https://www.nexusmods.com/mountandblade2bannerlord/mods/2698) | Not checked yet |  |  |  |  |
| [Vanilla AI Sieges for RBM](https://steamcommunity.com/sharedfiles/filedetails/?id=3332054135) | Not checked yet |  |  |  |  |
| VanillaNaval.CoopCompatfix | Not checked yet |  |  |  | Patch by antezorica88 for War Sails, posted on the Coop Discord (old 0.1.5 thread, 2026-09-22). Made for Coop 0.1.5. Turns off the naval part and keeps the Nords and the map. Not confirmed on 0.1.6. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08; old Coop 0.1.5 compatibility thread. |
| [Vexillum](https://www.nexusmods.com/mountandblade2bannerlord/mods/3716) | Not checked yet |  |  |  |  |
| [Village Docks](https://steamcommunity.com/sharedfiles/filedetails/?id=3620576662) | Not checked yet |  |  |  |  |
| [Vlandian Armoury](https://www.nexusmods.com/mountandblade2bannerlord/mods/2585) | Not checked yet |  |  |  |  |
| [Vlandian Steel Items](https://steamcommunity.com/sharedfiles/filedetails/?id=2925617885) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. If a player crashes on start, delete the mod's Shaders folder on that PC. With RBM, use the matching RBM patch. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [Vlandian Steel Reforged](https://steamcommunity.com/sharedfiles/filedetails/?id=2925571754) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. If a player crashes on start, delete the mod's Shaders folder on that PC. With RBM, use the matching RBM patch. Source: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest). |
| [War Cry War Horn Order Horns](https://steamcommunity.com/sharedfiles/filedetails/?id=2875897269) | Not checked yet |  |  |  |  |
| [Warband Music](https://steamcommunity.com/sharedfiles/filedetails/?id=3620409764) | Not checked yet |  |  |  |  |
| [Warbandlord](https://steamcommunity.com/sharedfiles/filedetails/?id=2882370524) | Not checked yet |  |  |  |  |
| [Warlord Pack](https://www.nexusmods.com/mountandblade2bannerlord/mods/5655) | Not checked yet |  |  |  |  |
| Warlords Battlefield | Not checked yet | 1 works, 0 broken | 2026-10-24 |  |  |
| [Warlords Battlefield - Bannerlord Branches Troop Overhaul](https://www.nexusmods.com/mountandblade2bannerlord/mods/4277) | Not checked yet |  |  | v0.1.5 | Older Coop evidence (v0.1.5). Not yet tested on 0.1.8. Change ModuleType in its SubModule.xml from OfficialOptional to Community (that also gets it past the War Sails check), and start the save in single player. Recruiting new units works; new faction banners, bandits and minor clans do not spawn; may hurt performance. Sources: Coodsz Coop 0.1.6 compatibility thread, 2026-10-08 (tested on Coop 0.1.5, retest); old Coop 0.1.5 compatibility thread. |
| [Wealthy Workshops](https://steamcommunity.com/sharedfiles/filedetails/?id=2999124969) | Not checked yet |  |  |  |  |
| [Wealthy Workshops - Fixed](https://steamcommunity.com/sharedfiles/filedetails/?id=3154041095) | Not checked yet |  |  |  |  |
| [Weapon Part Workshop](https://www.nexusmods.com/mountandblade2bannerlord/mods/393) | Not checked yet |  |  |  |  |
| [WeaponGapFix](https://steamcommunity.com/sharedfiles/filedetails/?id=2889662431) | Not checked yet |  |  |  |  |
| [Weather Indicator](https://www.nexusmods.com/mountandblade2bannerlord/mods/6561) | Not checked yet |  |  |  |  |
| [Wide Town City - Player and AI Settlement Modifiers](https://steamcommunity.com/sharedfiles/filedetails/?id=2908940787) | Not checked yet |  |  |  |  |
| [William a Knights Tale](https://steamcommunity.com/sharedfiles/filedetails/?id=2887550719) | Not checked yet |  |  |  |  |
| [Windwhistle's Collection](https://www.nexusmods.com/mountandblade2bannerlord/mods/6389) | Not checked yet |  |  |  |  |
| [Women in Calradia](https://www.nexusmods.com/mountandblade2bannerlord/mods/1578) | Not checked yet |  |  |  |  |
| [Workshop Licenses](https://steamcommunity.com/sharedfiles/filedetails/?id=3470343848) | Not checked yet |  |  |  |  |
| [Workshops Advanced](https://www.nexusmods.com/mountandblade2bannerlord/mods/4256) | Not checked yet |  |  |  |  |
| [Workshops Completed](https://steamcommunity.com/sharedfiles/filedetails/?id=2948863126) | Not checked yet |  |  |  |  |
| [WutheringWavesMod](https://steamcommunity.com/sharedfiles/filedetails/?id=3435761060) | Not checked yet |  |  |  |  |
| [Xingchen Warring States Weapon](https://steamcommunity.com/sharedfiles/filedetails/?id=3415841732) | Not checked yet |  |  |  |  |
| [Xorberax's Cut Through Everyone](https://www.nexusmods.com/mountandblade2bannerlord/mods/344) | Not checked yet |  |  |  |  |
| Xorberax's Cut Through Everyone by Lovetskyi | Not checked yet | 1 works, 0 broken | 2026-10-30 |  |  |
| [Xorberax's Training Field](https://www.nexusmods.com/mountandblade2bannerlord/mods/258) | Not checked yet |  |  |  |  |
| [Yari and Blackpowder](https://steamcommunity.com/sharedfiles/filedetails/?id=3556585206) | Not checked yet |  |  |  |  |
| [Yigu ThreeKingdoms](https://steamcommunity.com/sharedfiles/filedetails/?id=3555363340) | Not checked yet |  |  |  |  |
| [You Keep What You Kill](https://steamcommunity.com/sharedfiles/filedetails/?id=2903901025) | Not checked yet |  |  |  |  |
| [Zweihander and Claymore](https://steamcommunity.com/sharedfiles/filedetails/?id=2913601276) | Not checked yet | 1 works, 0 broken | 2026-11-01 |  |  |
| [zzy.ExtraLevelUp](https://steamcommunity.com/sharedfiles/filedetails/?id=2875931856) | Not checked yet |  |  |  |  |

582 mods.
