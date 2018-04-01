smarttv-twitch-bscout9956
==============
This is an app for Samsung SmartTV's designed to watch twitch.tv broadcasts.

Edits were made as to improve the application without radically changing the base of the app.

Installation
==============
On your TV, go to Menu->Smart Features->Samsung Account and type name "develop". 

Set up an Apache server. You can easily do that with XAMPP. Google is your friend.

Place the zip and widgetlist.xml inside htdocs. Set up widgetlist.xml with your PC's Internal IP. Use ipconfig on Windows to find out your Local IP Address. E.g: 192.168.0.182

Then go to SmartHUB, click "More Apps" button, then click "Options" button and choose "IP Setting", enter your Local IP Address and finally choose "Start App Sync" option. TwitchTV app has to be installed now.

For 2014 models "More apps" button might be absent, if so try: long press the enter button on any app, then the menu will pop up, select IP Settings, put in the IP, then long press enter again and then Start User Apps Sync.

For models released before 2013 you might want to use these instructions instead:
From the SmartHUB main screen, click the "Tools" button on the remote. Only from the "Tools" menu, navigate to "Settings", and from there to "Development". (You still have to be logged in as 'develop')

Contribution
==============
If you made a fix for your TV please feel free to make a push request.
