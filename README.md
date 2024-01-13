### ⚠WARNING⚠
WINDOWS SUPPORT ONLY IF YOU WANNA MAKE IT ON LINUX OR MAC YOU SHOULD REWRITE NGROK LIBRARY TO YOUR PATH OR DM ME IN DISCORD TO GET HELP

# Roblox-Video-Player
Roblox video player its support website's like youtube/pornhub/xxx videos

# How to install ngrok
Create your account
```c
https://dashboard.ngrok.com/signup
```
Download ngrok
```c
https://ngrok.com/download
```
place ngrok where will be your python script
### Setup
Download All Files and put all in 1 directory
Also download [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/tag/latest)


```sh-session
pip install -r requirements.txt
```

Change inside the script this line
```py
 app.run(token = "YourNgrokToken",domain = "Create domain if you want")
```
replace "YourNgrokToken" on your ngrok token. You can get it here 
```c
https://dashboard.ngrok.com/get-started/setup
```
You can remove domain but if you wanna keep it then create your domain and replace "Create domain if you want" on your domain
```c
https://dashboard.ngrok.com/cloud-edge/domains
```

### To run you should
execute require in developer console or in serverside executor
```lua
require(15959028599)("RobloxUserName","NgrokUrl")
```
And put in given to you gui url like [this](https://www.youtube.com/watch?v=bySCouUP8AI) and wait while video is rendering
