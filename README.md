![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

<h3 align="center">
    ─「 ᴅᴇᴩʟᴏʏ ᴏɴ ʜᴇʀᴏᴋᴜ 」─
</h3>

<p align="center"><a href="https://dashboard.heroku.com/new?template=https://github.com/Itzcriminal83/Spotify-Downloader"> <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

[DEMO VERSION  @Spotify_downloa_bot ](https://t.me/Spotify_downloa_bot)
### IS THIS STILL MAINTAINING?
> Yes ,this repository is still maintained and will be adding new feature's also
### WHY AUDIO FILES ARE NOT SENDING?
> Make Sure That Ffmpeg is Installed!
> If Your Vps/Local Server Location Is US Try To Change Location Or Use Cookies And Add This Line ["cookiefile":"path",](https://github.com/Masterolic/Spotify-Downloader/blob/fe859965e62a5ca8f29fc69185cd132d456e4bfd/mbot/utils/mainhelper.py#L144)
> path is defined as where is your cookie file to get cookie reffer [here](https://www.reddit.com/r/youtubedl/wiki/cookies/)
> US Region Block yt-dlp Request

### DO YOU USE HEROKU TO DEPLOY?
> Make Sure That To Change Region To Europe Else It Wont Work See Below Image
![1000003315](https://github.com/Masterolic/Spotify-Downloader/assets/93469093/2dbd5d1a-7ee6-47c5-af19-e839d30e778d)

### HOW TO ADD FFMPEG AND PYTHON IN HEROKU 
ffmpeg buildpack  url [click here](https://elements.heroku.com/buildpacks/jonathanong/heroku-buildpack-ffmpeg-latest)
![1000003319](https://github.com/Masterolic/Spotify-Downloader/assets/93469093/6a0c1c9c-4c91-4bac-b6fb-0a40d5516e3c)
![1000003317](https://github.com/Masterolic/Spotify-Downloader/assets/93469093/27b69fc4-5e50-461e-9d99-1c20b1fbc21e)

### NOTE
> This  Is  Old  repository of [@spotify_downloa_bot](https://t.me/Spotify_downloa_bot) so, this maybe buggy and lack of many features than our bot ,but still this will be maintained and updated some features when we do new updates
### WHICH  LANGUAGE AND TELEGRAM API  USED IN THIS ?
> This bot is  created using python language and python  mtproto pyrogram telegram library 

### DONATE ME PLEASE ❣️
> Please buy me a piza by using bellow link 👇👇👇
[Buy Me A Piza](https://www.buymeacoffee.com/Masterolic)

### RATE OUR BOT 
> Rate our  bot [FEEDBACK](https://t.me/dailychannelsbot?start=spotify_downloa_bot)

### ABOUT
> A Simple Open Source  Spotify Downloader Bot For Telegram 

### WHY I MADE THIS OPEN SOURCE  ?
> The answer simple I Don't own this repo this is edited version of [@NeedMusicRobot](https://t.me/NeedMusicRobot)

### IS THIS SOURCE CODE IS USED FOR [@Spotify_downloa_bot](https://t.me/Spotify_downloa_bot)
> NO, This [bot](https://github.com/rozari0/NeedMusicRobot) was the insperation to build our bot ,you can see our bot is entirely different From it some of the features will be implementing to this repoiostry 
### EASY WAY TO  DEPLOY IN  LOCAL/VPS ?
> First add variables in [config.env](https://github.com/Masterolic/Spotify-Downloader/blob/Latest/config.env)


```
apt update && apt upgrade -y 
apt install git ffmpeg python3 python3-pip -y
git clone https://github.com/Masterolic/Spotify-Downloader.git 
cd Spotify-Downloader/
pip3 install -r requirements.txt 
python3 -m mbot 
```

### DOCKER
```
  docker build . -t musicbot
  docker run musicbot  
```
### ENVIRONMENT VARIABLES
#### you need to add these variable in [config.env](https://github.com/Masterolic/Spotify-Downloader/blob/Latest/config.env)

`API_ID and API_HASH` get through [Telegram](https://my.telegram.org)

`BOT_TOKEN`get through [@BotFather](https://t.me/BotFather)

`SPOTIPY_CLIENT_ID and SPOTIPY_CLIENT_SECRET`get through [Spotify](https://developers.spotify.com)

### OPTIONAL ENVIRONMENT VARIABLES 

`LOG_GROUP`Telegram chat id of your log group to dump files

`BUG` Telegram chat Id to dump errors or bugs 

`AUTH_CHATS` Telegram chat id to ristrict other chats from using your bot

`genius_api` Get it from https://genius.com/developers

### CAN I CONTACT OWNER ?
 >  IF you need any help or need to add any features or tell feedback , don't hesitate to contact me 

[INSTAGRAM](https://instagram.com/masterolic_official)


[TELEGRAM](https://t.me/Masterolic)
