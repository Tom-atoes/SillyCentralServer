# Install Guide

## Installing the Mods (Manual Method, ignore if using Modrinth launcher) (Not Recommended)
You can find the mods zip file here. Once installed extract it to a folder (I assume you know how to do this) and open it up, once inside you will see 2 folders and a list of mod files.
![image](https://github.com/user-attachments/assets/80a70eb6-ae3b-4a50-8c8b-37c4da6f5c25)

Everything **not** in a folder is required to play on the server. Everything in the `ClientOnly` folder is highly recommended (includes mods like Oculus and Radium which heavily increase performance and let you load shaders!). You can ignore the `ServerOnly` folder.

Head to `%appdata%/.minecraft` in file explorer and look for a `mods` folder (if there isn't one, just create it), if you already have mods in this folder delete them. Drag all the mods you want into this folder (make sure you don't drag the `ClientOnly` folder into here, drag the stuff inside the `ClientOnly` folder in instead).

Next up you need Forge, head to https://files.minecraftforge.net/net/minecraftforge/forge/index_1.19.2.html and under "Download Recommended" press "Installer". Run the file it downloads and select "Install Client". Once this is done open the minecraft launcher and the version of forge you just installed should be selected already.


## Installing and Setting up the Modrinth Launcher (Recommended)
I highly recommend using the [Modrinth Launcher](https://modrinth.com/app) over CurseForge's launcher.

Once installed open it up and head to the green + icon in the bottom left of the screen to create a new profile.
![image](https://github.com/user-attachments/assets/3c34d275-201b-4a73-b291-8ace62f68591)

You will get a popup that looks like this, make sure everything here matches the screenshot below (fields like Icon and Name you can set to whatever you want). You will need to press `Show Advanced` to see the hidden options.
![image](https://github.com/user-attachments/assets/daf1034e-6e7c-45c2-879b-1da75ab2369e)

Create the Profile and it will appear on your app homepage, click on it and press `Folder`. This will open the profiles file directory, now head to the `mods` folder and drag in all mods from the ZIP file you installed early. When moving the client only mods make sure you drag them directly into the `mods` folder, **do not drag the `ClientOnly` folder in, this wont work!** Video guide available [here](https://github.com/user-attachments/assets/8d8408e4-43a9-4f0c-a572-5c265a0c3be1).

Final step: allocating more RAM to minecraft. This is super simple, press `Options` and look for the `Java Memory` tab. Tick `Override Global Memory Settings` and now the slider will be unlocked. The amount of RAM you have on your computer dictates the maximum value of the slider, I would allocate at least 4000MB of RAM and if you can do more then 8000MB and 16,000MB are even better. If you do not have a lot of ram then just allocate as much as possible (ideally 75% of your maximum). 

Once this is done you are ready to play! For guides on installing shaderparks and whatnot read below.

## Adding Shaders, Resource Packs, and Client Mods via Modrinth
Super simple, open up your profile in the Modrinth app and press `Content` and then in the top right press `Add Content`
![image](https://github.com/user-attachments/assets/20a5acd3-d321-490e-8a9e-263e2acb904e)

This will open up the Modrinth content library page, to install new content select a tab at the top (ignore Data Packs) and find something you like and simply press install. 

**IMPORTANT: when installing mods ensure you are only installing client mods! Installing server mods will cause an incompatibility error when you try to join the server.**
![image](https://github.com/user-attachments/assets/fea81f75-2040-451f-89db-e6f5f6912cfa)
