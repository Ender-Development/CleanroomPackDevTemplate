# CleanroomPackDevTemplate

## What is the purpose of this template?

Be an easy solution of setting up a baseline modpack that comes with a pre configurations for the common performance mods

## How does this work?

This repo utilizes [File Director](https://www.curseforge.com/minecraft/mc-mods/filedirector). A powerful mod licensed under MIT, which allows downloading files into a modpack instance right before minecraft starts. It's license allows me to bundle the mod within this repository, so it actually gets picked up and downloads all requirements right before the instance is launched for the first time.

## Installation on Curseforge launcher

1. create a repository from this template
2. clone your repo into your Curseforge Launcher directory
3. the launcher should automatically detect an instance called "CleanroomPackDevTemplate"

## Installation on MultiMC

1. create a repository from this template
2. create a MultiMC instance for 1.12.2 and install forge
3. open up the instance folder and clone your repo **inside** the `.minecraft` directory

## Installation on PrismLauncher

1. create a repository from this template
2. create a PrismLauncher instance for 1.12.2 and install forge
3. open up the instance folder and clone your repo **inside** the `minecraft` directory

## Running your pack for the first time

1. launch the instance once to download cleanroom relauncher and a few other mods
   - you can choose, which additional mods to install
   - all mods come with a description stating if they are mandatory or optional
   - all mods come with additional information if they are a requirement for another mod
2. once all mods are downloaded, a cleanroom relauncher window will show up
3. select a cleanroom version and point it to your Java 21+ `javaw.exe`
4. click the **"Relaunch Cleanroom"** button at the bottom
