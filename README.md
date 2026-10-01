# Fire-TV-Stick-Sleep-Utility
A free simple software that lets you put your Fire TV Stick to sleep remotely from your computer.

FIRE TV STICK SLEEP UTILITY — QUICK START

INSTALL
1. Double-click FireTVSleepUtilitySetup-English.exe.
2. Choose whether to create a desktop shortcut, then click Install and Open.
3. The app installs for the current Windows user; administrator rights are not required.

GET ADB
The app does not download or bundle ADB. Click “Download ADB from the official Android Developers page” in the app, download the Windows Platform-Tools ZIP, and extract it. Click Browse… and select adb.exe from the extracted platform-tools folder. You may put that folder anywhere. If ADB is already on PATH or in a standard Android SDK location, the app can detect it automatically.

PREPARE YOUR FIRE TV STICK
1. Open Settings > My Fire TV > About. Select the device name and press the remote's Select button seven times to enable Developer Options.
2. Go to My Fire TV > Developer Options and enable ADB Debugging.
3. Find the TV's IPv4 address in Network settings. Keep the PC and TV on the same local network.
4. Open the utility, enter the IP address, and click Connect and put device to sleep.
5. Approve the ADB debugging prompt on the TV the first time. If the app reports that the device is not authorized, approve it and click the button again.

UNINSTALL
Use Windows Settings > Apps > Installed apps and uninstall Fire TV Stick Sleep Utility. The app and saved address are removed. ADB files you downloaded yourself are left where you put them.

REQUIREMENTS
- Windows 10 or 11, x64
- ADB Platform-Tools, downloaded directly by you from the official site
- ADB Debugging enabled on the Fire TV Stick
- PC and TV connected to the same local network

The installer is unsigned, so Windows may show an unknown publisher warning. This independent utility is not affiliated with or endorsed by Amazon.

Official Android SDK Platform-Tools information:
https://developer.android.com/tools/releases/platform-tools
