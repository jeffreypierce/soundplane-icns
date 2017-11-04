# soundplane-icns
A replacement icon for [Madrona Labs](http://madronalabs.com/soundplane) Soundplane application.
![soundplane](https://raw.githubusercontent.com/jeffreypierce/soundplane-icns/master/img/soundplane.svg)

While the original icon was rendered beautifully, its skeuomorphic style did not fit in nicely with the rest of the applications on my dock. 

![soundplane-in-dock](https://raw.githubusercontent.com/jeffreypierce/soundplane-icns/master/img/soundplane-in-deck.png)


To replace:
  1. Right-click on application and select **Show Package Contents**
  2. Replace `/Contents/Resources/soundplane.icns` with the one found in this repo
  3. Open a terminal and run these two commands
    * `touch /Applications/Soundplane.app`
    * `touch /Applications/Soundplane.app/Contents/Info.plist`
  4. Replace the icon on your dock and voila!


