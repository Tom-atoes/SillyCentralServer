# Install Guide

## Modrinth App Installation (Recommended)
I highly recommend using the [Modrinth Launcher](https://modrinth.com/app) over CurseForge's launcher.

Once installed open it up and head to the green + icon in the bottom left of the screen to create a new profile.
![image](https://github.com/user-attachments/assets/3c34d275-201b-4a73-b291-8ace62f68591)

Now install the `.mrpack` file from [here](https://drive.google.com/file/d/1_F6ytxsBXMEYt8opi9yTCtrhA8HNHzM1/view?usp=sharing) (pack is in the zip file, extract it).
Select `From File` and select the `.mrpack` you downloaded earlier.

Now all that is left is to allocate more RAM to minecraft. This is super simple, open the newly created profile and press `Options` and look for the `Java Memory` tab. Tick `Override Global Memory Settings` and now the slider will be unlocked. The amount of RAM you have on your computer dictates the maximum value of the slider, I would allocate at least 4000MB of RAM; if you can do more then 8000MB or 16,000MB are even better. If you do not have a lot of ram then just allocate as much as possible (ideally 75% of your maximum). 
![Modrinth_App_66baGAXS5r](https://github.com/user-attachments/assets/799de9f3-fae4-4315-b16c-5b899b783304)


Once this is done you are ready to play! For guides on installing shaderparks and whatnot read below.

## Adding Shaders, Resource Packs, and Client Mods via Modrinth
Super simple, open up your profile in the Modrinth app and press `Content` and then in the top right press `Add Content`
![image](https://github.com/user-attachments/assets/20a5acd3-d321-490e-8a9e-263e2acb904e)

This will open up the Modrinth content library page, to install new content select a tab at the top (ignore Data Packs) and find something you like and simply press install. 

**IMPORTANT: when installing mods ensure you are only installing client mods! Installing server mods will cause an incompatibility error when you try to join the server.**
![image](https://github.com/user-attachments/assets/fea81f75-2040-451f-89db-e6f5f6912cfa)


## Manual Installation **(Not Recommended / Out of Date)**
You can find the [mods zip file here](https://drive.google.com/file/d/1438XIgYfNuml4bbD1KMyeVwgH_macWKT/view?usp=sharing). Once installed extract it to a folder (I assume you know how to do this) and open it up, once inside you will see some folders and a list of mod files.

![image](https://github.com/user-attachments/assets/d2d0a4e7-2c67-4734-a2c8-4eaf2a8e38f8)

Everything **not** in a folder is required to play on the server. Everything in the `ClientOnly` folder is highly recommended (includes mods like Oculus and Radium which heavily increase performance and let you load shaders!). You can ignore the `ServerOnly` folder.

Head to `%appdata%/.minecraft` in file explorer and look for a `mods` folder (if there isn't one, just create it), if you already have mods in this folder delete them. Drag all the mods you want into this folder (make sure you don't drag the `ClientOnly` folder into here, drag the stuff inside the `ClientOnly` folder in instead).
Look for the `resourcepacks` folder in `%appdata%/.minecraft` (if there isn't one, just create it) and drag everything from the `ResourcePacks` folder into there. These are **required** resource packs for some mods to function, you may still use your own resource packs as well as these if you wish.

Next up you need Forge, head to https://files.minecraftforge.net/net/minecraftforge/forge/index_1.19.2.html and under "Download Recommended" press "Installer". Run the file it downloads and select "Install Client". Once this is done open the minecraft launcher and the version of forge you just installed should be selected already.


