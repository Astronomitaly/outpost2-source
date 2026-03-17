# Outpost 2 OPU Unofficial Update 1.4.x Patch Notes

The OPU Update 1.4.x is an unofficial mod loader and collection of patches for Outpost 2 that improves compatibility with modern systems (especially with regards to multiplayer), fixes numerous bugs in the base game, and makes various gameplay quality-of-life improvements.

In addition, several custom missions are included (both single-player colony games as well as new multiplayer maps).  The update also improves support for modding the game as well as custom mission creation.

Note that unlike previous updates, in order to comply with specific requirements set forth in the EULA for the GOG Outpost 2 release, this version *does not* require permanent modifications to the existing files in the base game folder, allowing the unmodded game to be run at any time by simply double-clicking the `Outpost2.exe` file.

The OPU modded game may be run by double-clicking the `OPULauncher.exe` file in the `OPU` subfolder under the game folder, or by running `Outpost2.exe /OPU`.

## Disclaimer / License

**THIS MATERIAL IS NOT MADE OR SUPPORTED BY ACTIVISION.**

This mod is distributed by Outpost Universe at https://outpost2.net.  If you downloaded this from somewhere else, we recommend downloading it from our website as we can't vouch for the safety of other copies of it on the internet.

Outpost 2 is (C) Activision Publishing, Inc. and its affiliates ("Activision").

This mod ("OPU Update") is a community-supported update to Outpost 2, intended only to be used with a properly licensed copy of the game.

By using this mod, you acknowledge the following:

* All Outpost 2 original game content is property of Activision and may not be redistributed except as authorized by Activision.
* While we will do our best to provide support for OPU Update, you understand that this is solely on a volunteer basis, this mod was not created by Activision and we are not Activision employees, and that Activision cannot and will not provide support for this mod, only the base unmodified Outpost 2 game.
* You use this mod at your own risk; while we have tried our best to ensure it is reasonably bug-free, it is offered WITHOUT ANY WARRANTY or guarantee of any kind, and you assume all risk if your Outpost 2 installation, save files, operating system, PC, etc get corrupted/damaged as a result of using this mod.
* You agree to comply with the terms as already provided by the Activision EULA.  This means you may not redistribute Outpost 2, or make this mod or any other Outpost 2 content available for sale.
* This installer package and mod as a whole are licensed under the following license:
  `This work is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-nd/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.`
* Some software components have different licenses (see `LICENSE.txt` in the `OPU` subfolder for a full list).

**Please do not ask us how to get Outpost 2 for free, or otherwise illegally pirate a copy of the game, as we cannot and will not provide that.  If you don't already own a copy of Outpost 2, we recommend either purchasing the GOG version, or an original CD from a seller such as eBay or similar.**

In the same vein, please **do not** contact Activision or GOG for support with this modded version.  As described in the GOG EULA for Outpost 2, Activision/GOG can only support the base, unmodified copy of Outpost 2.  If you run into issues with the modded game, please reach out to us on Discord or the OPU forums, and we'd be happy to take a look.

## Requirements

* A copy of Outpost 2, either the original English CD version or the GOG version.
  * For the CD based version, the installer will copy files from the CD that don't normally get installed (such as music and cutscenes) so that you'll no longer need the CD to play.  If you don't have access to your CD, things should still work, but music and cutscenes won't play in game.
  * For non-English versions of Outpost 2, we do support copying localized assets like the language-specific cutscenes and Savant voices from the non-English disc (but you still need to run the installer on the English version of OP2).
* Windows XP or higher, or an environment that can emulate it well enough on non-Windows platforms such as Wine.
  * We've tested this update on both Windows XP SP3 and 10 and can vouch for it working properly (albeit with some minor features disabled on XP, due to lack of OS support) on those platforms.
  * Despite the fact that OP2 was originally released for Windows 95, this update *will very likely not work* on any version of Windows prior to XP and we have no plans to ever support this (if you're trying to play OP2 on an old computer, for example).
  * On Mac and Linux, your best bet is to install Windows in a virtual machine such as VirtualBox or VMware.  That said, if you don't want to use or pay for Windows, we have tested that the game works on Wine, albeit with a few issues:
    * On Linux, you need to install the 32-bit version of Wine (since OP2 was originally made for 32-bit Windows).
    * On macOS Catalina and higher, due to the fact that Apple removed support for running 32-bit programs, the only version of Wine that supports 32-bit programs such as OP2 is the (commercial, with a free 30 day trial) CrossOver Wine; however in the testing we've done, the game runs almost unplayably slow in this version of Wine, so we can't really recommend this right now.
    * Note that ARM-based Macs will not work; Wine and Windows programs such as OP2 will only run on an Intel-compatible CPU.
    * There are a few other (minor) bugs mentioned below in the Known Issues section.

## Installing

Simply download the installer and run it.  It should work equally well on both CD and GOG versions, and will attempt to move any pre-existing mods from a CD install to a backup folder.

It will attempt to autodetect your OP2 installation, but you can specify the path to your installation directly (or copy the installer to your OP2 folder and launch from there).

As mentioned above, for CD installs, we recommend inserting the CD if you have it available, as the installer can copy music, cutscenes, and (if you have a non-English CD) localized content from the disc.

Note that there are options in the installer to extract the music to .wav files, as well as extracting from a localized CD if using the GOG version.

## New and updated missions, changes, etc.

Please see the CHANGES.md file in this directory for a full list of changes and newly added maps.

## FAQ / Known Issues

**Important:** Before reporting bugs, please first try reinstalling the original game from either CD or the GOG version and try again with this "pristine" copy of OP2, especially if you previously had modified your game files or installed older mods.

If you continue to have problems, please reach out to us directly via Discord or the forums rather than reporting this to Activision or GOG (they did not make this mod, are not responsible for support for our mod or any other custom mods).  In doing so, please include as much detail as possible (such as your Windows version, whether you're using the CD or GOG version of the game, which previous mods were installed (if any) where the problem occurred, etc.)

> Windows Defender, my virus scanner, etc. thinks this is malicious/a virus!  Is this legit?
* Unfortunately, various parts of the update show up as a false positive on some virus scanners due to the fact that we load patches into a running program, which is a technique that a lot of malware also use to accomplish their nefarious goals.
* While we can vouch for the fact that the version of the update found on the OPU website is safe and doesn't contain any actual malware or attempt to do anything besides patch `Outpost2.exe` in memory, if you happened to find this update someplace else, we recommend re-downloading it from OPU to be safe in case others have attempted to modify it to add anything questionable.
* We cannot vouch for any custom maps or mods you may have installed that aren't included with this update, using these is at your own risk.
* We recommend adding an exception to Windows Defender or other antivirus software you may have for the entire `Outpost 2` directory to avoid any issues caused by antivirus blocking access to or deleting files used by the mod.

> The update won't install, fails with errors, etc.
* For best results, we recommend copying the installer to the game directory and running it as an admin (you should be prompted by Windows for this).
* If you are using Windows XP, ensure that you've updated to Service Pack 3.
* If you originally installed using the CD installer and the game is in the Program Files or Sierra folders, there could be permissions issues due to these being installed as an administrator.  Re-launch the installer by right clicking its icon and choosing `Run as administrator`.
* If the game is installed on a network share or some other location that doesn't have a drive letter mapped, you're likely to run into issues.  Either copy the game to a local drive or map it to a drive letter (and use this drive letter when running the installer).
* As described above, please try reinstalling the game from CD or GOG if nothing else is working, and reach out to us if you continue to have issues.

> The game won't run after installing the update, displays a black screen on launch, prompts to insert the CD, or some other error message appears on launch.
* Please ensure that your installation is not corrupted or missing files in some way (as above, you should try reinstalling the game before applying the update).
* Double-check that you are launching the loader in the `OPU` subfolder rather than `Outpost2.exe` directly (the latter will just run the unmodified game).
* If you continue to receive an error, please reach out to us and we'll do our best to provide support.

> I don't agree with gameplay change X, or it's breaking the campaign/custom missions, can I turn it off?
* At some point, we'd like to implement support for mod options to disable tweaks.  In the meantime, you can run `Outpost2.exe` directly to play the unmodified, "vanilla" version of the game (we'd appreciate your feedback as well).

> Mission X doesn't work, crashes, etc and I want to report a bug!
* If the mission is an official mission supplied with OP2, please check whether the crash is reproducible in the unmodded version of the game (by double-clicking `Outpost2.exe`).
* If the crash only happens with the OPU update, or in a custom mission, please let us know and we'll try to investigate.  **Please do not report these kind of crashes to Activision or GOG unless you're sure that the issue also exists in the unmodified game.**

> I can't host a multiplayer game, or others' multiplayer games don't appear in the "Find session" dialog.
* Please ensure that Outpost 2 is allowed through the Windows Firewall or any other firewall, if applicable.  You may want to consider creating exceptions for `Outpost2.exe` and/or `UDP` ports `47776-47807`.
* Check that UPnP or NAT-PMP are supported on your router, and ensure they're enabled if so.  This will provide the most "seamless" experience with network play by allowing the game to automatically forward ports.
  * Information about how to do this should be readily available online or in your router's user manual; there are many makes and models of routers and we can't really provide much useful support for this.
* If UPnP/NAT-PMP are not supported, assuming your router allows it, manually add port forwarding entries for `UDP` ports `47776-47807` to the computer running OP2.
  * If port forwarding is not an option (uncommon) you could also try configuring your computer as a DMZ in your router if supported, or if you have a separate modem, directly connecting your computer to that temporarily (note that neither of these options are ideal long-term for security reasons).
* Failing the above, Hamachi is one free option to allow creating a VPN with other players for multiplayer (albeit limited to 5 players at a time in the free version).
* Please report your issues (including info such as make/model of router/access point) to us so we can investigate further as ensuring working multiplayer is a high priority to us.

> When starting a multiplayer game, it fails with errors such as "remote load failed," "host and client checksums don't match," or a similar error.
* If you are playing a custom map (not included in this update), please first ensure that everyone has the same version of the map files; the game does not automatically download maps from the host as in many other RTSes.
* For other maps (including stock maps) this may indicate that your OP2 install has gotten corrupted somehow.  The easiest solution would be to try reinstalling OP2 and this update again.
* If you continue to have issues, please let us know.

> I tried to create / join multiplayer over IPX as described in the GOG release and the IPX option under Multiplayer is grayed out!
* You must use the TCP/IP mode.  The other modes are not well supported in recent versions of Windows due to their reliance on obsolete Windows features such as the IPX network driver and DirectPlay, so we have disabled them.  IPX is only (barely) supported in the unmodded GOG version via a provided wrapper that does not work over the Internet.

> The "Outpost 2" text on the top-left of the game window frame is blacked out and the game isn't responding to some keyboard/mouse input!
* This issue may be worked around by alt+tabbing back and forth to the game window.  This sometimes occurs when the game is launched from Windows Explorer/a debugger/etc. when its window and the game window are on the same display.

> OPULauncher appears to hang/do nothing for a long time before launching the game!
* If you chose to enable update checks and have an unstable internet connection, it might take a long time for the check to timeout, before the game starts.  You could try tweaking the `Game.UpdateCheckTimeoutMs` value in `outpost2.ini` or just disable it entirely by setting `CheckForUpdates=0` in the INI.

> (Win8/10) In the CD version, pressing F1 or clicking Help in the main menu leads to an error or opens a webpage about help not being supported anymore.
* You're probably running a version of Windows that no longer supports legacy Windows Help (what OP2 uses).  Since MS doesn't support it anymore, [download winhlp32.msi](https://www.majorgeeks.com/files/details/winhlp32_for_windows_10.html) and manually open `Outpost2.hlp` with it.

> (Win8/10) Cursors are partially transparent or only show a black outline and are hard to see.
* This issue seems to occur when playing the game on a monitor with HDR enabled and as far as we can tell, appears to be a Windows bug.  One potential fix (that seems to work in some cases) is to select the `Enable pointer shadows` setting in the `Pointers` tab of the `Mouse` control panel (in Win10, you can get to this by clicking "Additional mouse options" in Settings > Devices > Mouse), and then reboot your computer.  Failing this, disabling HDR (either in Windows display settings or your monitor's built in settings) should solve the problem.

> (Wine-specific) The game window can't be resized, and buttons in the title bar don't work.
* Unfortunately we don't have a fix for this at this moment. The game install defaults to maximized mode however to try to minimize the effects of this problem. Going to Game Settings (the rightmost Sierra icon on the report buttons just below the minimap in the upper-right) allows you to exit the current mission or the entire game.

> (Wine-specific) The lists of missions (under Tutorials, Colony Games, etc) are illegible due to having a white background.
* We don't yet have a fix for this either.  For now it may be possible to read the mission lists by clicking on each entry.

## Credits

This wouldn't have been possible without the help and support of various OPU community members, of which there are too many to really list.  We did want to call out a few folks for specific things:

* Arklon and BlackBox for the overall runtime patching logic and installer that make this release possible.
* Hooman and BlackBox for much of the older OPU patches and original game reverse engineering notes.
* Hooman and Vagabond for large portions of op2ext, OP2Utility (e.g. the VOL extraction logic).
* Sirbomber, Mcshay, Arklon, Vagabond, and others for contributing many of the custom missions, as well as playtesting, AI and balance changes, etc.
* Fenrisul for the redesigned icon used by the installer, launcher, and game windows.
* Monarky for the updated background graphic in the menus.
* Probably many others we've forgotten (please let us know if you're missing!)

Not to mention a few open source projects:

* [bsdiff](https://github.com/mendsley/bsdiff)
* [Capstone](http://www.capstone-engine.org/)
* Google Fonts [Open Sans](https://fonts.google.com/specimen/Open+Sans) and [Roboto](https://fonts.google.com/specimen/Roboto)
* [libnatpmp](https://github.com/miniupnp/libnatpmp)
* [miniupnp](https://github.com/miniupnp/miniupnp)
* [zlib](https://zlib.net/)
