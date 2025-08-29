# zrito

1- Executer powershell en administrateur

2- Executer: Set-ExecutionPolicy AllSigned
2.1 Ou executer: Set-ExecutionPolicy Bypass -Scope Process

3- Executer: Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

4- Télécharger le fichier: https://github.com/tkruba/zrito/releases/download/zrito/packages.config

5- Déplacer le fichier dans le disque C:

6- Executer dans powershell: choco install C:/packages.config
