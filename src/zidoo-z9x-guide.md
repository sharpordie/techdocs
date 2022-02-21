## ZIDOO Z9X GUIDE

<p>
  <img alt="z9x zidoo" width="100%" src="assets/zidoo-z9x-guide.png">
</p>

Aenean non euismod odio. Suspendisse mollis tincidunt mattis.

<!-- ----------------------------------------------------------------------------------------------------- -->

## CHANGE DEFAULT SETTINGS

Launch **quick settings** from home screen and adjust configs as follows.

#### CHANGE AUTO FRAME RATE

1. Reveal the **playback/auto frame rate** submenu
1. Change the **frame rate mode** option to **match frame rate only**
1. Change the **frame rate pause** option to **no pause**

#### CHANGE DEFAULT LANGUAGE

1. Reveal the **playback/default language** submenu
1. Change the **default subtitles** option to **off**

#### CHANGE FORCED SUBTITLE

1. Reveal the **playback/forced subtitle** submenu
1. Select the **auto** value

#### CHANGE COLORS

1. Reveal the **display/color settings** submenu
1. Change the **4k 50~60hz** option to **priority yuv420 10bit**
1. Change the **4k 23~30hz** option to **priority yuv444 10bit**
1. Change the **non-4k** option to **priority yuv444 8bit**
1. Change the **hdmi color range** option to **16-235**

#### CHANGE HDR

1. Reveal the **display/hdr** submenu
1. Select the **auto** value

#### CHANGE DOLBY VISION COMPATIBILITY

1. Reveal the **display/dolby vision compatibility** submenu
1. Select the **priority standard dv (tv led)** value.

#### CHANGE RESOLUTION

1. Reveal the **display/resolution** submenu
1. Select the **3840x2160 23hz** value
1. Ensure the **lock resolution** option is checked

#### CHANGE HDMI AUDIO

1. Reveal the **audio/hdmi audio** submenu
2. Select the **auto** value

#### CHANGE SAMBA SERVER

1. Reveal the **network/samba server** submenu
1. Ensure the **samba server** option is checked
1. Ensure the **allow data to be written** option is checked
1. Ensure the **enable passsword** option is checked
1. Change the **username** and **password** values

#### REMOVE HDMI CEC

1. Reveal the **other/hdmi cec** submenu
1. Ensure the **hdmi cec** option is unchecked

#### REMOVE WEATHER WIDGET

1. Reveal the **other/weather widget** submenu
1. Ensure the **show weather widget** option is unchecked

<!-- ----------------------------------------------------------------------------------------------------- -->

## UPDATE THE FIRMWARE

#### GATHER LATEST RELEASE

1. Launch the [mcbluna](https://www.mcbluna.net/wp/zidoo-model-overview/zidoo-z9x-firmware-download/) website
1. Scroll the website to the very bottom
1. Select the version without Google Apps preinstalled

#### UPDATE DEVICE FIRMWARE

1. Tap on the **about** from the home screen
1. Tap on the **update** button
1. Tap on the **usb update** button
1. Select the previously downloaded archive
1. Ensure the device has rebooted

#### UNPLUG DEVICE FOR FEW MINUTES

1. Unplug the device from the power outlet
1. Ensure to wait for 4-5 minutes
1. Replug the device from the power outlet

<!-- ----------------------------------------------------------------------------------------------------- -->

## ENABLE REMOTE CONTROL

#### ENSURE ADB IS INSTALLED

##### ON MACOS

1. Ensure you have [homebrew](https://brew.sh/) installed on your computer
1. Launch the `brew install android-platform-tools` command 

##### ON WINDOWS

1. Ensure you have [scoop](https://scoop.sh/) installed on your computer
1. Launch the `scoop install adb git` command

#### ENABLE USB DEBBUGING

1. Launch the **quick settings** application from home screen
1. Reveal the **others/about** submenu and tap **advanced settings**
1. Reveal the **system/about tablet** submenu
1. Ensure the **build number** has been tapped 7-8 times
1. Tap on the **remote back button**
1. Reveal the **advanced/developer option** submenu
1. Ensure the **usb debbuging** option is checked
1. Tap on the **remote back button**

#### ENSURE COMPUTER IS ALLOWED

1. Tap on the **about tablet** link
1. Remind the **two last digits** under **ip address**
1. Launch the `adb connect 192.168.xx.xx` command
1. Ensure the **allow usb debbugging** message has appeared
1. Ensure the **always allow from this computer** option is checked
1. Tap on the **ok button**

<!-- ----------------------------------------------------------------------------------------------------- -->

## USEFUL RESOURCES

- [Official Zidoo forum](http://forum.zidoo.tv/index.php?forums/hdd-media-player-rtd-1619dr.54/)
- [OlivierQC's YouTube channel](https://www.youtube.com/channel/UCwz_OZWlielee6EoX_IFBgg)