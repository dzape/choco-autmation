# choco-autmation
Instalin apps with choco

# Install Chocolatey
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

# Essentials
choco install notepadplusplus -y
choco install firefox -y
choco install vlc -y
choco install discord

# Additional Tools
choco install 7zip -y
choco install curl -y
choco install powertoys -y

# Dev Tools
choco install visualstudio2019community
choco install git -y
choco install postman -y
choco install github-desktop

#VS Code & Extensions
choco install visualstudiocode -y
choco install vscode -y
choco install vscode-powershell -y
choco install vscode-csharp -y
choco install vscode-gitlens -y
choco install vscode-docker -y
choco install visualstudio-github

# Microsoft .NET Core 
choco install dotnetcore -y
choco install azure-data-studio -y

# You´re done. ;)
