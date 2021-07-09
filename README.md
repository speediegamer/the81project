# The81Project

![T81PLogo](https://user-images.githubusercontent.com/71722170/114026148-33f21c80-9876-11eb-9b9e-d1ed72fcb8bb.png)
### Running Mac OS X 10.4 Tiger on Early 2008 Leopard Macs

##### Documentation: https://github.com/speediegamer/the81project/blob/main/Documentation.pdf                           
##### Written Guide: https://github.com/speediegamer/the81project/blob/main/Installation%20Guide.pdf
##### Compatibility List for version 5.0 https://github.com/speediegamer/the81project/blob/main/Compatibility-List-T81P5.0-482021.pdf

Recommended version: https://speediegamer.github.io/the81project
Any other version is not supported.

The81Project or 81Project (because yes, people call it that) is an unofficial image of Mac OS X 10.4.10 modified to boot on Early 2008 Macs.

(Note: has been replaced by Project 081. It's the exact same except it's much more stable, faster, has better drivers, closer to vanilla and just generally much cleaner than The81Project. Only ever use The81Project if Project 081 for some reason won't boot on your machine.)
Check it out at https://p081.github.io

* Custom Bootloader with SMBIOS patches (currently Clover, switching to OC asap)
* Many different patched drivers to get more things functional
* Vanilla experience
* No bootloader needed after installation
* One disk image, works on both supported and unsupported Macs
* Package included which allows you to choose what will be installed
##### TenFourFox for Intel, Java Update, Safari Update, 10.4.11 Update and more.
MASSIVE ISSUE: Due to a modification to SystemVersion.plist, either modify it before installing or after. Change "The81Project" to "10.4.10"
Will be fixed with Project 081.

## Check if yours is compatible
On any version of Mac OS X, installed or recovery, open the terminal and run
  ```sh
  sysctl hw.model
  ```

# Tinker responsibly
By using this tool, both patcher, patches and/or images, you are 100% using them at your own risk. In case your machine fails to boot, your important data is lost and you get fired from work, you have no one to blame but yourself. Please.. whatever you do. Tinker responsibly!

## Creating the USB installer

Simply grab a simple 8GB or larger USB stick, go to https://speediegamer.github.io/the81project in any browser, select your Mac, download the disk image and
restore the disk image using Disk Utility (Built into Mac OS X), or balenaEtcher (macOS, Linux, Windows)
Download it from here: https://github.com/balena-io/etcher

## Booting

Enter the boot menu on your Early 2008 Mac (By powering on the computer and holding ⌥ until you see a while screen)
Select EFI Boot and you should see a black screen where you can choose a volume. Select The81Project for X. Once you reach the installer, install Mac OS X like you normally would.

## Fixing issues

A lot of issues cannot be fixed. If your Mac has Intel GMA X3100 graphics for example, it will not get any GPU acceleration.
Take a look at the Compatibility List and before you report an issue, make sure it's not already listed.
Most Macs will not have perfect compatibility.. yet..
If it isn't listed as an issue or your model isn't available in the list, navigate to your USB installer and launch The81Toolkit.mpkg. Select the patches you need, if they are available.
Install it and reboot. If your issue isn't listed in the Compatibility list and The81Toolkit didn't fix it, post an issue on GitHub or @ me on Twitter.

## Troubleshooting
If you can't boot, try booting the Mac OS X volume directly. It should be named Mac OS Install Disk 1
Otherwise, create an issue or @ me on Twitter.

## Please.

I need as much information as possible to make the compatibility list complete and to know what works and what doesn't. If you get a successful install, please tell me about it, your Mac, specs, what works and what doesn't, what patches were needed. If you can't boot or things don't work properly, still create an issue or @ me on Twitter. This helps me make sure The81Project is compatible with as many Macs as possible.

## Support Me

If you would like to support my work, consider simply starring my GitHub page, following me on GitHub/Twitter or simply reporting issues or sharing the project with others. Doing so will help this project out significantly

## Credit

    speedie - Creator of The81Project and the TigerALC patch
    CloverHackyColor - Created Clover EFI, making this project possible

##### PLEASE DO NOT DISTRIBUTE ANY FILES ON THIS PAGE DIRECTLY WITHOUT PERMISSION!
##### DOING SO WOULD BE DISRESPECTFUL CONSIDERING THE WORK I PUT IN!
    




