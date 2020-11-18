## Introduction
Run Spotify ad-free on PC.

## Uninstallation & Cleanup
(**Note:** People who have used Spotify in the past or are still using it, must follow Uninstallation. If you've never installed Spotify on your PC before, you can go ahead and skip the Uninstallation part.)  
**1.** Install Revo Uninstaller from [here](https://94f29e82f377c2c0658d-388a64d31e58fcdf2a0581c5105c02bb.ssl.cf1.rackcdn.com/revosetup.exe), or run ``winget install revouninstaller`` from PowerShell if you use Windows Package Manager.   
<br>**2.** Open Revo Uninstaller, and uninstall Spotify from there. If you are unable to find Spotify in Revo Uninstaller, on the top bar, click on the **Windows Apps** icon and uninstall from there.  
      (If you've uninstalled it from the Windows Apps section, it might take a few seconds to unregister the app in PowerShell. You'll need to be patient here.)  
<br>**3.** After uninstallation, it will show an option to scan system for leftover registry keys, residual files, etc. that the installer might not have removed. Here, choose Advanced scanning process and proceed with the scan.  
<br>**4.** Delete every registry entry that is formatted in the bold black style, and proceed. In the next screen, it will list residual files. Select all and delete them.

## Installation 
**1.** Install this specific version of [Spotify](http://upgrade.spotify.com/upgrade/client/win32-x86/spotify_installer-1.1.4.197.g92d52c4f-13.exe).   
**2.** Launch Spotify and login to your account.    
**3.** Tap on the three dots icon on the top left corner of the app and tap on Help>About Spotify. Make sure that the about section **does not mention** that its a Microsoft Store version. (else, follow [this](https://github.com/pratyakshm/BlockTheSpot/blob/master/README.md#uninstallation--cleanup)).    
**4.** Download [Install.bat](https://raw.githubusercontent.com/pratyakshm/BlockTheSpot/master/install.bat) and [netutils.dll](https://raw.githubusercontent.com/pratyakshm/BlockTheSpot/master/netutils.dll).  
**5.** Run Install.bat as administrator.  
**6.** Done!  

### Credits  
[master131](https://github.com/master131) for BlockTheSpot.
