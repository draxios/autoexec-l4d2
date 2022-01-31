# autoexec-l4d2
Yo, it's like a config script for l4d2

## Backing up current config
1. Go to your Left 4 Dead 2 installation directory `.../Steam/steamapps/common/Left 4 Dead 2/left4dead2/`
2. Right-click `cfg` folder and click `Send to >> Compressed (zipped) folder`
3. This will be your backup in the event that you would like to revert back to your original settings

## Instructions
 1. **Read through each config file to understand what is happening**
 2. Copy the files and folders into your game directory:
`.../Steam/steamapps/common/Left 4 Dead 2/left4dead2/`
 3. Setup launch options of L4D2: `Right-click Left 4 Dead 2 >> Properties >> Set Launch Options`
  4. Add the following line into the box: `-lv -noborder -high +precache_all_survivors 1 -novid -console -nojoy -noforcemaccel -noforcemparms -noforcemspd +mat_motion_blur_percent_of_screen_max 0 +clientport 27666`
      - Remove `-lv` if you do not prefer to play in low violence mode
 6. Setup video settings as per given below if you have a potato computer like mine (you may use your higher settings for items in **bold** if you have a beast)

| Setting                     | Value                         | Remarks                                                      |
| --------------------------- | ----------------------------- | ------------------------------------------------------------ |
| Aspect Ratio                | As per your your screen size  |                                                              |
| Resolution                  | As per your native resolution |                                                              |
| Display Mode                | Full screen                   |                                                              |
| **Film Grain Amount**       | None                          | For screen clarity                                           |
| **Anti-Aliasing Mode**      | None                          | No reason to have this enabled. If you have a powerful system, you can set this to max. |
| **Filtering Mode**          | Trilinear                     | No reason to run higher than this                            |
| Wait For Vertical Sync      | Disabled                      | Having VSync enabled locks your FPS to your screen's refresh rate that causes input lag |
| Shader Detail               | Low                           | If you have a powerful system, you can set this to max       |
| Effect Detail               | High                          | This is to ensure that you can see Tank rocks from a distance |
| **Model/Texture Detail**    | Low                           | If you have a powerful system, you can set this to max       |
| **Multicore Rendering**     | Enabled                       | Uses all available CPU cores for the game (Disable this if you have an old computer or facing fps issues even with this config) |
| Paged Pool Memory Available | High                          | More memory is assigned to the game which results in the game loading maps slightly faster |

  7. Launch game and open console and run the following command: `unbindall; exec config_default.cfg; exec autoexec.cfg`
      - Please note that the command above **resets the game config**. **All custom binds/mappings will be removed**. You will have to manually add or change your custom binds/mappings after this command.

 8. Change any binding that you do manually (like binding different key to zoom, changing crouch key, etc) in the game settings
