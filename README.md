Branched from https://github.com/ChrisTitusTech/win10script

# win10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. I also added Chocolatey and other tools to the script that I install on every machine.

Running using

powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/lol4291/win10script/Modified-to-use/win10debloat.ps1')"

## My Changes

```
- "SetUACHigh"				[default = "SetUACLow"]
- "EnableFirewall"			[default = "DisableFirewall"]
- "EnableDefender"			[default = "DisableDefender"]
- "EnableDefenderCloud"			[default = "DisableDefenderCloud"]
- "DisableFastStartup"			[default = commented out]
- "EnableActionCenter"			[default = "DisableActionCenter"]
- "EnableLockScreen"			[default = "DisableLockScreen"]
- "EnableLockScreenRS1"			[default = "DisableLockScreenRS1"]
- "EnableFileDeleteConfirm"		[default = "DisableFileDeleteConfirm"]
- "HideTrayIcons"			[default = "ShowTrayIcons"]
- "DisableDarkMode"			[default = "EnableDarkMode"]

```
