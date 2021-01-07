# Stardew-Vortex-Guide
A guide for setting up and using Vortex with SDV



-why use vortex 

-setting up vortex 

  -TODO initial install 
  
  -Explanation of staging, deploy, and purge 
  
  ![folders](https://user-images.githubusercontent.com/10282272/103912227-9f3c1f00-50cc-11eb-8a5b-90b3ec42bea5.png)
  
  To avoid the old issues of NMM leaving files in game folders, Vortex handles mods differently. When a mod is added to Vortex, it is unzipped into your staging folder. This does not touch your game at all, this is only where Vortex holds mod files. In order to add these files to your game, Vortex deploys. This is where mod files are copied from staging to your mod folder. Vortex typically auto-deploys by default, unless this option is disabled or does not trigger for one reason or another. 
  ![purgedeploy](https://user-images.githubusercontent.com/10282272/103912285-b2e78580-50cc-11eb-8025-fcc07559e89d.png)
  If the Deploy button has a dark orange border around it ![needdeploy](https://user-images.githubusercontent.com/10282272/103912874-75cfc300-50cd-11eb-9b00-9bc626f12262.png), there are mods waiting to be deployed.You can click this button and Vortex will move these files. 
  
  -Finding folders with 'Open' 
  
  -Migrating Mods 
  
    -Adding existing zip files
   
-common issues

-mods not being installed
  -check game path
  ![game location](https://user-images.githubusercontent.com/10282272/103911412-a0208100-50cb-11eb-801e-338748b2e7a1.png)
  -check mod path
  -check smapi path
  -check deployment
  
