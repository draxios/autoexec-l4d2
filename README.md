# autoexec-l4d2
Yo, it's like a config script for l4d2

## Backing up current config
1. Go to your Left 4 Dead 2 installation directory `.../Steam/steamapps/common/Left 4 Dead 2/left4dead2/`
2. Right-click `cfg` folder and click `Send to >> Compressed (zipped) folder`
3. This will be your backup in the event that you would like to revert back to your original settings

## Instructions
 1. **Read through config file to understand what is happening**
 2. Copy the file to your game directory:
`.../Steam/steamapps/common/Left 4 Dead 2/left4dead2/cfg`
 3. Setup launch options of L4D2: `Right-click Left 4 Dead 2 >> Properties >> Set Launch Options`
  4. Add the following line into the box: `-noborder -high +precache_all_survivors 1 -novid -console -nojoy -noforcemaccel -noforcemparms -noforcemspd +mat_motion_blur_percent_of_screen_max 0 +clientport 27666`
 
 7. Launch game and open console and run the following command: `exec autoexec.cfg`

 8. Change any binding that you do manually (like binding different key to zoom, changing crouch key, etc) in the game settings
