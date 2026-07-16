<p align="center">
<img src="/assets/images/RF1_logo.png" alt="RF1_Logo" style="width:337px;"/>

# THIS IS WORK IN PROGRESS AND NOT PERFECT! PLEASE JOIN THE DISCORD IF YOU HAVE ANY QUESTIONS!

It's fair to say I love sport, but in recent years I haven't followed F1 as closely as I'd like, I dip in and out and I thought it would be cool to have a desktop companion that gives me a heads up about the next race, details, circuit etc. So I built one!

This is built with OpenF1 as well as loading some assets via github to save space on the device and hopefully reduce the RAM usage. So there can be updates over time that wont all require reflashing. Due to the web based assets it does mean sometimes it takes a second to load so I apologise for any lag.

# So What can I do with it?

Well Next Race gives you a nice overview of coincidently the Next Race, with a map and dates which are the times and dates for Practice, Qualifing and the Race itself. You can also tap the map for a slightly larger view and then tap to the right of the screen for the Lap record Holder.

Calendar is very much the same as Next Race but gives you a view of all the Races in the current season.

Standings is both Drivers and Constructor Standings.

Settings gives you a few customisation options including Team Colour based themes and Timezone Control, which will give you the Race times in your Timezone when set.

More info available here: [Initial Release Notes](https://github.com/TheRandumbHero/RandumbF1/blob/main/release-notes.md)

> [!NOTE]
> Please bear in mind this still in Beta as I get use to GitHub & PlatformIO so I currently only have the one driver version. I will be producing the second one soon! Please bare with me!

## Parts List

- 3D Printed Case - [RandumbPrints - Makerworld.com](https://makerworld.com/en/@RandumbPrints)
- Cheap Yellow Display (CYD) - [Amazon UK](https://www.amazon.co.uk/dp/B0CQX9Q68P?ref=ppx_yo2ov_dt_b_fed_asin_title) - These can be got cheaper on AliExpress I just needed one quickly for the build.
- *Optional* - 90 degree adapter for routing the USB to a more pleasing position.

# Connecting & Building:

1. Print the case whilst waiting for the parts to arrive.
2. Place the CYD into the mount to the part called "Cradle"
3. Put the 'Washers' over the pins to hold the CYD in place.
4. Slide 'Cradle' in the 'Main Body'
5. Place 'Bezel' into 'Outer Shell' This is a tight fit and should properly click.
6. The flat uprights of the 'Main Body' should be used to guide the 'Outer Shell' its been design this way to keep as little a gap as possible from the screenwithout causing accidental damage


# Webflasher

> [!CAUTION]
> By Flashing your ESP32 it will wipe any other app you currently have running - I would advice unplugging any other ESP's you may have plugged in just incase you select the wrong COM Port.

Connect the ESP32 to your PC with a USB-C cable and head to [LINK](https://therandumbhero.github.io/RandumbF1) this will open up a webflasher - Flash your ESP32 and wait for it to complete.

# Initial Setup

Once the ESP32 boots up for the first time, it will create a Wifi Access Point called RandumbF1, connect to this on your phone/laptop. Head to 192.168.77.1 on your browser and enter your home WIFI details. You'll get a confirmation page and the device will reboot.

<p align="center">
  <a href="/assets/images/Initial_Setup_Screen.png">
    <img src="/assets/images/Initial_Setup_Screen.png" width="180" alt="Initial">
  </a>

# First Setup

You should now have the home screen, tap 'Settings' and you'll see a local IP address just under your heading, this is your WebUI if you need it. In settings and the WebUI you're able to change the 'Team' to rep your team or just have it as RandumbF1 which is my original theme.


# Customisation

Now is the fun stuff. Head back to the Home Screen, Click 'Settings' and Cycle through the Team based themes!

# Screen Examples

<p align="center">
  <a href="/assets/images/Home_Screen.jpeg">
    <img src="/assets/images/Home_Screen.jpeg" width="180" alt="Initial">
  </a>
  <a href="/assets/images/Next_Race_Screen.jpeg">
    <img src="/assets/images/Next_Race_Screen.jpeg" width="180" alt="Next Race">
  </a>
  <a href="/assets/images/Calendar_Screen.jpeg">
    <img src="/assets/images/Calendar_Screen.jpeg" width="180" alt="Calendar">
  </a>
    <a href="/assets/images/Drivers_Standings.jpeg">
    <img src="/assets/images/Drivers_Standings.jpeg" width="180" alt="Drivers Standings">
  </a>
  <a href="/assets/images/Constructors_Standings.jpeg">
    <img src="/assets/images/Constructors_Standings.jpeg" width="180" alt="Constructors Standings">
  </a>
    <a href="/assets/images/Settings_Screen.jpeg">
    <img src="/assets/images/Settings_Screen.jpeg" width="180" alt="Settings">
  </a>


<p align="center">
  <a href="https://discord.gg/KhCzPJEbc2">
    <img src="https://makerworld.bblmw.com/makerworld/model/20260708/2960391924/2e40a4f5fd8edcc9.png" width="240" alt="Initial">
  </a>

# Data Sources
This a completely unofficial unaffiliated F1 Companion for all the details about where the data comes from please visit the original sources:

- [OpenF1](https://openf1.org)
- [Formula1 Official Site](https://www.formula1.com)
