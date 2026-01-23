# MCSR-bucket

Tools for speedrunnin minecraft on **windows**.

## QuickStart

Make sure you have `scoop` installed for package management.
To install `scoop`, run the following commands in windows cmd:
```cmd
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
[!NOTE]
This command is directly copied from: https://github.com/ScoopInstaller/Scoop

To install the bucket, run:
```cmd
scoop bucket add MCSR-bucket https://github.com/ray847/MCSR-bucket.git
```

To install a specific tool (e.g. Ninjabrain Bot), run:
```cmd
scoop install MCSR-bucket/ninbot
```
