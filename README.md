# SurfMapPics
Tandem project with my [SurfZones Project](https://github.com/Sayt123/SaytsSurfZones), both projects are to be used subtractively. Remove images for maps you don't host if you wish to debloat. I have gone through every single map I personally have, that loaded, and gathered screenshots of all maps, and every map bonus, in 3440x1440 / 21:9 JPEG. If you are a map's creator and have a better/preferred angle you would like me to use or suggest please feel free to contact me. 

## How to use:
General tutorial if you are using a timer like [Qawery-Just-Sad's timer](https://github.com/qawery-just-sad/Surftimer-Official) or [Sarrus1's SurfTimer-Discord plugin](https://github.com/Sarrus1/SurfTimer-discord). Clone this repo, and host the images somewhere you can point your timer/discord relay to pull from.


If using the timer, in your surftimer.cfg located probably around /csgo/cfg/sourcemod, you can add your copy of this directory to the following two lines, to get the discord record image showing up in either color coded example in the image. Bonus images can be enabled by setting **ck_discord_bonus_image "1"**

🟩 - **ck_discord_url_main
🟥 - ck_discord_url_thumb**

<img src="https://i.imgur.com/P0ttKJN.png">


Otherwise if you use the Discord plugin, your image url would go in **sm_surftimer_discord_main_url_root "your hosted images url"**, and set **sm_surftimer_discord_bonus_image "1"**



Example:

**sm_surftimer_discord_main_url_root "https://raw.githubusercontent.com/Sayt123/SurfMapPics/maps-only/csgo/"**


------------------------------------------------------------------------------------------------------
"But what if I want them in [a different resolution?](https://github.com/search?q=bulk+image+resize)"

"Well what if I want to [add a watermark?](https://github.com/search?q=bulk+image+watermark)"

If your timer or plugin doesn't work like this or doesn't have any of these entries I unfortunately cannot help. These images can be used for anything they aren't limited to just use for discord bots.
