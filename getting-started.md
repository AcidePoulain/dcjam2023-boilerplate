# Welcome ! Here's how to get started

## Prior to the game jam start
### Install Godot (latest, with C# support)
#### On Linux
Use your package manager if you can. If you can't get version 4.0.1 with C# support,
you can go to [the official download page](https://godotengine.org/download/) and
pick a standalone version.

There is also an [rpm](https://src.fedoraproject.org/rpms/godot) available for fedora, 
but I do not know if C# support is included.

#### On Windows
Go to [the official download page](https://godotengine.org/download/) and get the 
most recent version with C# support.

### Check if godot works
When running godot, you get a tabbed window that allows you to choose an existing 
project. You can click on the "Asset Library Projects" tab on the to right of this window
and browse for an existing project to try out. I encourage you to do so in order to check
if everything is working right. Choose a demo in the "Demo" category, open it and try to
run it with F6. Contact AcidePoulain#1752 on Discord if you get in any trouble.

## On the first day of dcjam2023 

### Cloning the repo
Clone this repository on your work computer (use your terminal of choice on Linux or git bash
on Windows).

### Configuring the tools
Run the following commands in the directory folder
```
git config user.name "<Replace with your github username>"
git config user.email "<Replace with your github email>"
git config rerere.enabled true
```

Run this command anywhere:
```
git config --global pull.rebase true
```
