# Setup FabLab Mons desktops

* Rename the computer
```PowerShell
Add-Computer -Restart -WorkGroupName FabLabMons -NewName flm-pc-XX
```
* Install Chocolatey
```PowerShell
Set-ExecutionPolicy Bypass -Scope Process -Force; iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex
```
* Install packages
```PowerShell
cinst -y 7zip adobereader-update adobeshockwaveplayer adobeair git googlechrome vscode vscode-powershell vscode-icons vscode-editorconfig
```
