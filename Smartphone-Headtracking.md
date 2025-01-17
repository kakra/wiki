[![Headtracking](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/ht_ico.jpg)](http://youtu.be/6Pts_sotjMA)

**Smartphone requirements:**
- Android or Windows Phone. See [[Smartphone-Windows-Phone]] for the latter.
- gyroscope is highly preffered
- wifi, bluetooth(not tested but should work as well using tethering option) or USB network connection

**Mappings and accela may need individual tuning depending on smartphone or game.**

**1.**
You need to connect PC and android smartphone to the same network (via USB,  wifi or bluetooth).

~~Turn on airplane mode (turn off GPS/GSM/NFC/Wifi/Bt modules), and turn on wifi or bluetooth if you using wireless connection.~~

Note: the striked out suggestion is false. It was made with the intent of preventing health risks. However, it's physically impossible (see the [electromagnetic spectrum table](https://en.wikipedia.org/wiki/Electromagnetic_spectrum) with GSM bands contained within radio spectrum) for ionizing radiation to occur in terms of GSM/WCDMA/LTE/wifi. Also notice energy values in log<sub>10</sub> scale in the same table.

You still might want to disable the ringer sound while using the device.

**2. Install opentrack 2.3 on your PC**

You need to set up mapping in opentrack for yaw, pitch and roll to be like on images below.

![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/ht_yaw.JPG)
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/ht_pitch.JPG)
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/ht_roll.JPG)

You need to invert two axes (this option can depend on your game)

![](http://i.imgur.com/FvYCwFF.jpg)

Next you need to set up filter. I prefer to use Accela filter. 

![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/accela.JPG)

You need also set up the 'center' key in keys tab to center the view in several situations.

As 'protocol' please choose Freetrack 2.0 (compatible with most games)

Please select 'FreePIE tracker' and set there 5555 port. Remember to open this UDP port for in your firewall.
![](http://i.imgur.com/fyh8KWT.jpg)

**3) Install FreePIE android client on Your smartphone**

Freepie client (apk) is located in _your_OpenTrack_installation_directory\doc\contrib\freepie-udp

Remember to enable "allow installation from unknown sources" on your smartphone before install. You will be prompted with option to go to the settings if you haven't enabled this.

Configure it as you see on image below:

![](https://dl.dropboxusercontent.com/u/73783868/freepie/4.png)

Remember. You need to enter **local IP ADDRESS OF YOUR PC**, not IP on above image.

**4.You can mount smartphone on head to headset or use a girl headband decorations ;)** (this is red, not pink...)

You can mount smartphone to headset:
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/headset.jpg)
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/headset2.jpg)
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/headset3.jpg)

!!! Note !!!
Large magnets in the headset may interfere with magnetometer readings in smartphone.
Putting phone to each speaker for 20s should temporary recalibrate smartphone magnetometer for distorted magnetic field, but this is only workaround, not a solution and may not work in every case.
Other workaround is install phone in distance 15-20cm above headset.

Or you can mount without it:
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/opaska.jpg)
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/opaska2.jpg)
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/opaska3.jpg)

If you think, than the above looks funny, you can also hide the smartphone...
![](https://dl.dropboxusercontent.com/u/73783868/opentrack_vr_tutorial/opaska4.jpg)

**5. Engage!**

Click start in opentrack

Click start in FreePIE on the smartphone

Start the game

Use the previously defined center button.

**Here is a video:**
**http://youtu.be/6Pts_sotjMA**
