# Skivi
My method to completely unblocking everything on school Chrome accounts.



--------



# WARNING!
Skivi is currently patched as of ChromeOS 132.0!
This will work bad in ChromeOS 100-ish and above, so if you want to check just open Settings, About ChromeOS, and it will say. If you are below 100-ish, you SHOULD be fine. We are currently working on a fix for ChromeOS 100 and above.
If you are using ChromeOS above 100-ish, proceed with caution.





# HOW TO SET SKIVI UP
This guide will show you how to completely set Skivi up.

REQUIREMENTS:
1 chromebook of any kind that isn't your schools (can be a cheap dumb one off of ebay for 20 bucks, doesnt matter)
An SD card



## Step 1: Enabling Dev Mode
Press and hold the ESC key + Refresh key, then press the Power button to turn it back on.
When the recovery screen appears, press Ctrl + D to enable Developer Mode.
Confirm the prompt and allow your device to reset and enter Developer Mode.
After this, log back into your chromebook.


## Step 2: Installing APKs
Just logging back in won't do anything. We will need a couple necessary files to actually "unblock" everything.
Go to https://drive.google.com/file/d/1UCd3KQbBpyIoaXSGar6OAGff2u8bPm_4/view?usp=sharing and download the file.
If Google Drive is for some reason blocked, search for "Cx File Explorer APK" and start clicking around links until you find a download.

Once the APK is downloaded you need to open your files, go to downloads, and double click the Cx File Explorer APK.
If everything is done correctly it should open a window asking to install the app, just click install. If it says it's not supported, Skivi will not work on your device.

WARNING: On ChromeOS 100ish and above, the following list will delete all APKs:

Restarting the device,
Clearing the notifications (?),
Cancelling an APK install


## Step 3: VPN Time Baby
Cx File Explorer is your new file manager, so get used to it. Go back to chrome and go to https://1.1.1.1 and download Cloudflare.
If Cloudflare is blocked (which it probably is), I somehow managed to find a copy of the Cloudflare APK on my Oculus, so I backed it up for y'all. The link is https://drive.google.com/file/d/1kwM5D0RfJr-xUp_mbeWg8T5ET6KUCxno/view?usp=sharing
To install APKs now, open Cx File Explorer and go to the downloads tab. From there, click on the .apk file ONCE to open the installer. This is our new way of installing APKs. Install Cloudflare.
Once it's installed, open it and turn the switch on. It should say that your internet is secured or private or whatever. FOR CLOUDFLARE PEOPLE: If it's stuck on "checking connection", turn the switch OFF.
Then, it'll pop up with something. Click the 2nd lowest option "Use DNS Only Mode" and then it will work.


## Step 4: More APKs!!! Yay...
SKIP THIS STEP IF YOU ARE PLANNING ON SAVING STORAGE. THIS STEP IS NOT REQUIRED!!!!
This step is only if you want more advanced apps, like DuckDuckGo in step 5.1. Go to the https://f-droid.org/en/ to install F-Droid.
If it's blocked, go to my reupload: https://drive.google.com/file/d/1i7z3rU4JQyMsk-TYE7KsbvIetDaL145B/view?usp=sharing and install F-Droid. If you are using the reupload, it will be an older version that doesn't really work well. To actually get a working version, just update it when it pops up that there is a new update.
Bam, you have F-Droid installed.



# Step 5: Linux! Woah!
SKIP THIS STEP IF YOU ARE PLANNING ON SAVING STORAGE. THIS STEP IS NOT REQUIRED AND I DONT RECCOMEND IT UNLESS NEEDED!!!
Basically, you'll need to set up Linux on your Chromebook. This step is necessary to run apps and others on chromebooks.
Open the Settings menu on your Chromebook.
Scroll down to the Developers section and turn on Linux Environment.
Follow the on-screen prompts to set up Linux. This will install a Linux container on your Chromebook, allowing you to run Linux applications.
Once Linux is installed, you'll want to make sure your system is up to date. Open the Terminal app and paste the following commands to update your system:
```sudo apt update```
After you pasted, click enter. Then, paste the following command:
```sudo apt upgrade```
After you pasted, click enter. If a popup asks if you want to continue, type `y` and press Enter to confirm.
When using Linux applications I reccomend you use low power mode as it helps with lag issues kind of, so open settings, go to system preferences, then power, then turn on battery saver. You can put your brightness back up as it doesn't change anything.



## Step 6: Unblocking Websites
This one took me a while, since if you want a somewhat decent browser it's not just installing an APK.
If you want a not really good browser, install DuckDuckGo by following Step 5.1.
if you want a better browser, install FireFox by following Step 5.2.

## Step 6.1: Installing DuckDuckGo
This is the only one I actually tested and worked on older devices. To install DuckDuckGo, you must follow Step 4 if not already.
Go to the F-Droid app and search for "DuckDuckGo". Install it. That's literally it.

## Step 6.2: Installing FireFox
This is a really good browser for chromebooks but it does take up some space. Free up space if necessary before doing this!
Once you have around 3-4 gigabytes of storage avaiable, follow Step 5. After Linux is installed, open the Terminal app and paste the following command:
```sudo apt install firefox-esr```
After you pasted, click enter. This will install FireFox. After it's installed, open the FireFox app.

## Step 6.3: Experimental Browsers
Installing the following is not reccomended. It most likely won't work, either.
The links to all experimental browsers are https://drive.google.com/drive/folders/1B2LkuzjAlDVMjQXQieflf85PmZIZWZ7V?usp=sharing



## Step 7: Uhm, other apps?
This is not needed! You can basically do anything you want right now. BUT, if you want, there are some other apps you can install.
1. Discord: https://drive.google.com/file/d/1LvMHOidiUqb3DxBhcVs_CAtLatmgxOBo/view?usp=sharing
2. Minecraft Pocket Edition: https://drive.google.com/file/d/1UR1yBEooO51AG1odLs5onLKp7KUXAdUT/view?usp=sharing




## Step 8: Installing Google Play Games
Go to the [Google Play Store]("https://play.google.com/store/games") to find the game you want, or search for it. Once you found it, copy the link. Then, open a new tab and go to https://apps.evozi.com/apk-downloader/
Once on the downloader, paste in the link to the game you copied. Then click "generate download link". Once it's done and didn't give an error, click the "Click here to download com.BLAHBLAH.BLAHBLAH now".
Open Cx File Explorer and open the .apk file once it downloaded. Install it and like yeah!!!



## Step 9: PROXY SERVER OMG ITS HAPPENING
If some sites such as Xbox Cloud Gaming doesn't work, connect to one of the best proxies. I used Python and a list of over 10 thousand proxies, and it found THIS.

The Most GOD-TIER Proxy for Gaming
IP: 188.114.99.171
Port: 80
Location: Amsterdam, Netherlands
Protocol: SOCKS4 (Fast)
Anonymity: Elite (Maximum privacy)
Latency: 2.824ms (Absolutely insane)
Response Time: 72ms (Basically instant)
Uptime: 99.97% (Basically never dies)
ISP: Cloudflare, Inc. (Highly trusted)


To connect, open your settings on your chromebook. Then go to network, then Wi-Fi, and click on the one that says "Connected". Scroll down to Proxy. Toggle on "Allow proxies for shared networks".
Then, click confirm. Before you type anything, toggle on "Use the same proxy for all protocols". Change connection type to "Manual proxy configuration" or the bottom-most one. Now, in the text
box next to "Proxy" type in the IP above. Type in the box nex to "Port" the port above. then, just click save.
