Configuration initally based on Scott Hanselman's [Ultimate Powershell Prompt](https://www.hanselman.com/blog/my-ultimate-powershell-prompt-with-oh-my-posh-and-the-windows-terminal). 

# Installation instructions
We need 
* winget (installed by default in Win 11, recent Win 10)
* Terminal-Icons
* PSReadLine
* [Starship prompt](https://starship.rs/)

If you have winget installed you can get everything with the following script
```
winget install --id Starship.Starship
Install-Module -Name Terminal-Icons -Repository PSGallery
Install-Module PSReadLine -AllowPrerelease -Force
```
