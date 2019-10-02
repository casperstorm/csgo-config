## Personal CSGO Config

### Launch options
`-novid -tickrate 128`

**Why not:**  
-threads? [Fuck that.](https://www.reddit.com/r/GlobalOffensive/comments/5y8r7v/in_depth_discussion_of_the_threads_launch_option/)  
-nod3d9ex? [vMcJohn denies](https://www.reddit.com/r/GlobalOffensive/comments/6ndpi4/are_nod3d9ex_mat_queue_mode_2_still_good_launch/)  
-high? [Wrecks](https://www.reddit.com/r/GlobalOffensive/comments/5pxtqi/is_it_worth_using_threads_4_and_high_in_launch/dcuzf2d/) system [stability.](https://www.reddit.com/r/GlobalOffensive/comments/5bsw4m/help_with_launch_settings_needed/d9r2860/)  
-mat_queue_mode? [No.](https://www.reddit.com/r/GlobalOffensive/comments/5zkpwn/in_depth_discussion_of_mat_queue_mode_and_mat/)  
-exec autoexec? Have you tried [host_writeconfig?](https://www.reddit.com/r/GlobalOffensive/comments/8ax858/updated_csgo_tips_configs_and_more/)  
-refresh, -hz? CSGO will regardless run at your default refresh rate.  
  
*(Thanks [/u/birkir](https://www.reddit.com/user/birkir/))*

### EDPI

|     EDPI    	|  800 	|
|:-----------:	|:----:	|
| Sensitivity 	|  0.5 	|
|     DPI     	| 1600 	|
 

### Install
Put the files into the following folder if you have only one account or if you want the same autoexec to be used on multiple accounts:
```
...\SteamApps\common\Counter-Strike Global Offensive\csgo\cfg
```

Put the files into the following folder if you want separate autoexec's (and video) for each account (i.e. If you share your PC with your family/friends):
```
...\Steam\userdata\<YOURID>\730\local\cfg
```

### Radeon CSGO Profile Settings
| Mode                         | Value                            	|
|-----------------------------	|----------------------------------	|
| Anti-aliasing Mode          	| Use application settings         	|
| Morphlogical Filtering      	| Off                              	|
| Anisotropic Filtering Mode  	| Use application settings         	|
| Texture Filtering Quality   	| Performance                      	|
| Surface Format Optimization 	| Off                              	|
| Wait for Vertical Sync      	| Always Off                       	|
| OpenGL Triple Buffering     	| Off                              	|
| Shader Cache                	| On                               	|
| Tessellation Mode           	| Use application settings         	|
| Radeon FreeSync             	| On (capping FPS using RTSS)      	|
| Display Scaling             	| Off                              	|
| Radeon Anti-Lag             	| Off (enable if GPU is maxed out) 	|
| Chill (FPS)                 	| Off                              	|
