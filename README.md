Configuration based on Scott Hanselman's [Ultimate Powershell Prompt](https://www.hanselman.com/blog/my-ultimate-powershell-prompt-with-oh-my-posh-and-the-windows-terminal).

# Installation instructions
We need 
* winget
* oh-my-posh
* Terminal-Icons
* posh-git
* PSReadLine

If you have winget installed you can get everything with the following script
```
winget install JanDeDobbeleer.OhMyPosh
Install-Module -Name Terminal-Icons -Repository PSGallery
PowerShellGet\Install-Module posh-git -Scope CurrentUser -Force
Install-Module PSReadLine -AllowPrerelease -Force
```