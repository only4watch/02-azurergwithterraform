# azurergwithterraform
1. You need to have an account in azure
Install visual Studio extension
using powershell you need to install choco package manager
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
choco install azurecli
choco install terraform
choco install git

if you have linux system
yum install 
\apt get install package name

if you use mac system
brew tap hashicorp/tap
brew install hashicorp/tap terraform
