HD3_Launcher Fix for "The Succession Wars v0.8.2" mod

1. Download Lunar IPS:https://www.romhacking.net/utilities/240/
2. Backup your original "_HD3_.dll" in home Heroes 3 folder.
3. Get HD3_Fix.ips from this github repository.
4. Run "Lunar IPS.exe".
	- Press Patch File: choose HD3_Fix.ip
	- **Target File**: original `_HD3_.dll` in home Heroes 3 folder (Backup your original!).
5. Launch the game via HD_Launcher.exe — the error should disappear!

Technical details:
- Fix: Replaced JE with JMP at 0x100141CE.
- Supported versions: ["The Succession Wars v0.8.2"], ["HoMM3 HD 5.5 R59 Launcher"]
