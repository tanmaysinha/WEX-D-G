# WEX-D-G

[![alt tag](https://github.com/ibm-wex/WEX-D-G/blob/master/images/TryMe_Wex_Mac.png)](https://github.com/ibm-wex/WEX-D-G/tree/master/TechPreview/V12CE/mac)                                 &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![alt tag](https://github.com/ibm-wex/WEX-D-G/blob/master/images/TryMe_Wex_Windows.png)](https://github.com/ibm-wex/WEX-D-G/tree/master/TechPreview/V12CE/windows)

## Abstract
Before you install the IBM Watson Explorer Community Edition application, get familiar with the most important information related to the installation process.

## Supported versions
 - Windows:
   - Windows 10
 - Mac:
   - OS X Yosemite 10.10.3, and later
   
## Installing the application
- If you use an older toolbox-based version of Docker, uninstall it before you install the application.
- If you have other containers that run on your computer, stop them before you start the installation process of the application because your computer might have resource constraints.
- The application pulls a Docker Image during the installation process. The installation takes about 10-15 minutes on a standard network speed of about 15-20 Mbps. A typical corporate VPN is likely to limit the download speed. Consider it while you wait for the installation to finish.
- If you already have the application installed and want to upgrade to a new version, from the 'More info' menu in the upper-right corner on the Result page select Uninstall. This will remove the older version of Docker Image and container. Finally relaunch the application to pull most recent Image.  

## Launching the application
- If you are a Mac user, the following security warning is displayed when you launch the application: "IBM Watson Explorer Community Edition can't be opened because it is from an unidentified developer"
  - In this case, from the Apply menu, choose System Preferences, click Security & Privacy, then click General. In the General pane, click Open Anyway button. For details, see https://support.apple.com/kb/PH25088?locale=en_US.

## Uninstalling the application
 - Select the menu in the upper-right corner on Result and select Uninstall to uninstall the Docker Image and container.
  - For mac users remove the IBM Watson Explorer app from the Applications folder.
  - For Windows users go to control panel and uninstall IBM Watson Explorer.

## Known Issues
 - Browser specific issues - please use FireFox or Chrome. 
   - Some icons would not appear properly on IE11 and Safari.
   - Admin Console may not appear on IE11.
 - Help menu on Admin Console and Content Miner is not ready to link to the Knowledge Center.
 - Miss spelled words may appear on the screen.
