**HTML-Alerts-In-Text-Format-For-Streamer.bot**

Create a browser source in obs-studio and select the index.html file to show a alert on your stream

[Streamer.Bot Download](https://streamer.bot/)

** Works With Twitch, YouTube, Kick.com integration for Streamer.bot **

<ins>Features:</ins>
- HTML Format Alerts
- Information Is Grabbed From Text Files
- Alert Image Can Be Changed

<ins>Install</ins>
<ins>OBS-Studio</ins>
1) UnZip The Alerts.zip File
2) Copy The Alerts Folder To C:\Program Files\obs-studio\
3) Add Browser Source In OBS-Studio
4) Select Local File And Select The index.html File

<ins>Streamer.bot</ins>
1) Go To All Your Alerts Action
2) Under Sub_Actions, Right Click Core > File IO> Write To File **Put Checkmark On Append to file**
3) Select The topText.txt File And Under Text to write enter The Alerts Name [eg New Twitch Follow]
4) Again Add Another Write To File - Sub_Actions, Right Click Core > File IO> Write To File **Put Checkmark On Append to file**
5) Select imageText.txt And Enter In Write To File  %targetUserName%

You Can Change ALERTS.png To Your Alert Image !


