# Stardew-Vortex-Guide
A guide for setting up and using Vortex with SDV



## why use vortex 

## setting up vortex 

  -TODO initial install 
  
   -Starter toggle in INTERFACE
  
  ## Explanation of staging, deploy, and purge 
  
  ![folders](https://user-images.githubusercontent.com/10282272/103912227-9f3c1f00-50cc-11eb-8a5b-90b3ec42bea5.png)
  
  To avoid the old issues of NMM leaving files in game folders, Vortex handles mods differently. When a mod is added to Vortex, it is unzipped into your staging folder. This does not touch your game at all, this is only where Vortex holds mod files. In order to add these files to your game, Vortex deploys. This is where mod files are copied from staging to your mod folder. Vortex typically auto-deploys by default, unless this option is disabled or does not trigger for one reason or another. 
  If the Deploy button has a dark orange border around it ![needdeploy](https://user-images.githubusercontent.com/10282272/103912874-75cfc300-50cd-11eb-9b00-9bc626f12262.png), there are mods waiting to be deployed.You can click this button and Vortex will move these files. 
  
  -Finding folders with 'Open' 
  
  ## Migrating Mods 
  
   If you are installing Vortex after previously manually installing files into the /Mods folder, there is a bit of work that needs to be done. Because Vortex primarily handles .zip and other archive files, a /Mods folder full of folders isn't ideal. 
    -Adding existing zip files
   Once you have a clean /Mods folder, we can start reinstalling mods. If the .zip files are still available on your PC, these can be installed manually with ![thisbutton](https://user-images.githubusercontent.com/10282272/103912257-a7945a00-50cc-11eb-8187-ab1769d2863f.png), or dragged into the main Vortex mods window
-common issues

## mods not being installed
  ### check game path
  ![game location](https://user-images.githubusercontent.com/10282272/103911412-a0208100-50cb-11eb-801e-338748b2e7a1.png)
  ### check mod path
  ### check smapi path
  ### check deployment
 ## SMAPI can't find game
  ### multiple installs
  ### multiple steam libraries
  ### Stardew missing .exe at the end????? (maybe not)
  
