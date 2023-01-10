#Internal App Sharing and Testing via Google Play Console
There has been the case where a group of Internal developers were complaining that the users with corporate devices are not able to receive the internal apps through link sharing.<br> 
So the case was provided to my team and I investigated.<br>The conclusion was that it was a simple case of enabling the internal app sharing on corporate phones. 

_Below are the steps that one can follow for the seamless internal app-sharing_. 

##Setup Testing Group - From Developers Side
Setup a test group in Google Developer Console for internal app sharing. If as a System admin you don't have the access to the developer consoler then ask the developers to that for you.<br>
<br>The references are as follows.
<ol>
<li><a href=https://play.google.com/console> Google Play Console</a></li>
<li>An elaborate tutorial is available under the following link. <a href= https://support.google.com/googleplay/android-developer/answer/9845334?hl=en> App Testing Google Play Help </a></li> 
</ol>

##From Testers Side
####Step i: Enable Developer Settings
<a href=https://www.samsung.com/uk/support/mobile-devices/how-do-i-turn-on-the-developer-options-menu-on-my-samsung-galaxy-device/> Enable Developer Settings on Samsung Phone</a>

####Step ii: Enable Internal App Testing on Android Phones
The next step is to inform the testers to enable internal app sharing on their Android phones<br>
The screen-shots in succession are as follows. 
_Note: They were tested on Samsung Galaxy Phone. So it may vary on other phones._

<kbd>![Figure](https://github.com/Khu99am/MDM-Learnings/blob/master/docs/Android_MDM/General/internalAppSharing/InternalAppSharing1.JPG?raw=true)</kbd>
<kbd>![Figure](https://github.com/Khu99am/MDM-Learnings/blob/master/docs/Android_MDM/General/internalAppSharing/InternalAppSharing2.JPG?raw=true)</kbd>
``` 
Kindly Note:
i) In order to update the app you have to send the link again.
ii) Testers have to pay for the paid apps.
iii) Develop a Standard Procedure that how to get proper feedback from the users. 
 ```
 