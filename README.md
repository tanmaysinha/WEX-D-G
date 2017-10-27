# Watson Explorer Community Edition

<!--
[![alt tag](https://github.com/ibm-wex/WEX-D-G/blob/master/images/Download_Wex_Mac.png)](https://github.com/ibm-wex/WEX-D-G/releases/download/1.0.0/IBM.Watson.Explorer.CE-TP-1.0.0.dmg)                                 &nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![alt tag](https://github.com/ibm-wex/WEX-D-G/blob/master/images/Download_Wex_Windows.png)](https://github.com/ibm-wex/WEX-D-G/releases/download/1.0.0/IBM.Watson.Explorer.CE-TP-1.0.0.exe)
-->
<!--
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![alt tag](https://github.com/ibm-wex/WEX-D-G/blob/master/images/FAQs.png)](https://github.com/ibm-wex/WEX-D-G/blob/master/Faq.md) 
-->

## Abstract
Before you install the IBM Watson Explorer Community Edition application, get familiar with the most important information related to the installation process.

## Feedback / Suggestions / Questions
Please post to the dWAnswers Community with `wex` tag or `watson-explorer` tag at the following URL:
* https://developer.ibm.com/answers/topics/wex/
* https://developer.ibm.com/answers/topics/watson-explorer/


## Supported versions
### Windows:
   - Windows 10 Education
   - Windows 10 Enterprise
   - Windows 10 Pro
### Mac:
   - Mac OS X 10.10.3 or later
   
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

## Known Issues / Limitations
- Multiple dictionary annotators do not work with a single collection. If you want to apply multiple dictionaries, create a dictionary annotator that includes multiple dictionaries.
- When creating a new model for a classifier and cancelling the creation during Creating datasets status in either Content Miner or Admin Console, the status may not be changed although the process has been actually cancelled in the system.
- Facet highlighting is partially supported. The text will be highlighted when the exact same facet value string is specified as the facet refinement query. For example, query _'facet:"positive expression"'_ does not highlight _'good product'_ in the document text.
- Facet counting for numeric or date facets in the custom analysis view is not supported in Content Miner.

### Browser specific issues - please use Chrome or any other tested browsers
* Safari on Mac is not a supported browser.
* Pop-up error with _"ReferenceError: 'URLSearchParms' is undefined"_ appears on Microsoft Internet Explorer 11 and Microsoft Edge when trying to create a new classifier in Admin Console.
* Some UI elements are not correctly rendered in Admin Console with Microsoft Internet Explorer 11.
