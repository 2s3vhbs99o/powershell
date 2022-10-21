# Powershell user profile  
Before use, run command:  
```
echo $env:USERPROFILE\.config\powershell\user_profile.ps1 > $PROFILE   # add custom powershell user profile file  
mkdir ~/.config 
mkdir ~/.config/powershell
cd ~/.config/powershell
git init
git pull https://github.com/lobanov4real/pwsh-user-profile.git  
```
