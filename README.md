# Fake-CSM-Source-2013 Dev mapbase 7.1 branch
This branch contains some changes only for mapbase 7.1 and some test shit.

Read main branch readme to get more info

Thanks:        
-sitkinator      
-Xenthio

# Branch Features

-Somehow fixed model lighting problems.

-Changes intensity because mapbase updates.

-Added light_env changes to csm.fgd.

`ALSO NOW YOU SHOULD COPY PITCH PARAMETERS EXECLY HOW IT SHOULD BE (PITCH YAW ROLL)`

If you have `Assert server/baseentity.cpp in 7240 line` you should go to this file and comment it. Also comment Warning up there.         
If you have problems with blend materials, try to make it displacement.        
If you have problems like "Second CSM Level are white but the First CSM Level are different color" try to set blue channel to 0

`mat_depthbias_shadowmap should be 0.00001` and `mat_slopescaledepthbias_shadowmap should be 4`      
This CSM looks better when `r_flashlightdepthres is 4096` 

# How to install
Go to readme in main branch. 

# If you have some problem or question
then go to the [Discord server](https://discord.gg/DaBHDTwAU7) and describe the problem.
