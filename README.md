![Alt text](https://raw.githubusercontent.com/ExploiTR/HackBright/master/app/src/main/res/drawable/ic_launcher.png)
# HackBright
Override factory brigtness settings with ROOT Access [Android]

### NOT WORKS WITH EVERY ANDROID DEVICES !! [Rarely]

# How to add support for your device

1.Explore system files in your phone using [ROOT Browser(s)](https://play.google.com/store/search?q=root%20browser&c=apps&hl=en) or [Droid-Explorer](http://de.bit13.com/) like softwares  

2.Find the file that your system uses to store brightness settings  

3.Open [MainActivity.java](https://github.com/ExploiTR/HackBright/blob/master/app/src/main/java/app/exploitr/hackbright/MainActivity.java) and edit the `XPATH` String to the path containing information about your device's current `BRIGHTNESS` and `XMPATH` for `MAX BRIGHTNESS`

4.Compile & Run.
