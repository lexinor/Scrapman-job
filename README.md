# Scrapman-job
OverTrue RolePlay scrapman-job

[![Scrapman-job](https://img.shields.io/badge/Lua-Fivem-orange)](https://img.shields.io/badge/Lua-Fivem-orange)
# Note:
Hi there, Thank you for download my cool job here you can get all the information about the job.

About the job: I posted this job a long time ago -> https://forum.cfx.re/t/esx-scrapman-job/3807213/42 
But unfortunately i had some problems there, and after a while i decided to post the job again with fixes for all the problems that i had there.
If you find new problems or old ones keep in touch with me in the fivem forums or take my discord name from my github profile link -> https://github.com/ArielZ123
I will be happy to help or get from you tips to fix things or change.

Settings in the script: There are 3 things you can add or remove from the client side in lines -> 15, 21, 25, all of them are coords for add or remove positions of markers to search or sell and also add the npc Character
that using as a 'dealer'.

Server side change: In Line 17 you can change the price of the scrap sell -> local addmoney = math.random(20, 50) -> please pay attention to change the numbers to (High or low amount) as your choice.

DO NOT FORGET TO CONNECT THE SQL FILE TO YOUR DB!!!

To sum up things: I recommend you to give it a try and read about me in my github profile -> https://github.com/ArielZ123

If you need anything feel free to ask me.

Fivem Forum Link: https://forum.cfx.re/t/esx-scrapman-job-fixed-version-last-update/4841799

-------- Update - > 21/1/2023 --------
Welcome legacy version :wave:.
here is what you need to do if you use this version:
Config.Lua - > will give you the option to switch between the old esx to the new one (esx legacy).
If you are using the esx legacy version please set the config to false and do the following thing:
Go to → fxmanifest.lua - > then go to → shared_scripts and then add this line → ‘@es_extended/imports.lua’ under → ‘main/config.lua’.
