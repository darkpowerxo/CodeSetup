# CodeSetup
setting up a coding environment  
step 1:  
install windows terminal from the windows store.   
install powershll from the windows store  

step 2:  
download CascadiaCove nerd font from  
https://www.nerdfonts.com/font-downloads  

step 3: in vs code and in the terminal set the default font as  CascadiaCove nerd font  

step 4: copy Microsoft.PowerShell_profile.ps1 to $username/Documents/PowerShell  

step 5:  
```
winget install JanDeDobbeleer.OhMyPosh  
winget install --id Git.Git -e --source winget  
Install-Module -Name Terminal-Icons -Repository PSGallery  
Install-Module PSReadLine -RequiredVersion 2.1.0  
```

thanks to  
Scott Hanselman: https://gist.github.com/shanselman  
https://github.com/devblackops/Terminal-Icons  
https://devblogs.microsoft.com/powershell/announcing-psreadline-2-1-with-predictive-intellisense/  

