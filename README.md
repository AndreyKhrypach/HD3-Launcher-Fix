# HD3-Launcher-Fix
HD3_Launcher Fix for "The Succession Wars v0.8.2" mod
This patch remove error after using Hd_Launcher to run "The Succession Wars v0.8.2" mod. Message Error: "You should run HD_luncher.exe first after HoMM3 HD+ installation. If you ran HD_Launcher.exe with no effect try to run it as administrator".
Instructions to use this patch: 
Download Lunar IPS:https://www.romhacking.net/utilities/240/
Backup your original "_HD3_.dll" in home Heroes 3 folder.
Get HD3_Fix.ips from this repository.
Run "Lunar IPS.exe".
Press **Patch File**: choose `HD3_Fix.ips`
**Target File**: original `_HD3_.dll` in home Heroes 3 folder (Backup your original!).
Launch the game via HD_Launcher.exe — the error should disappear!
Technical details:
- Fix: Replaced JE with JMP at 0x100141CE.
- Supported versions: ["The Succession Wars v0.8.2"], ["HoMM3 HD 5.5 R59 Launcher"]
