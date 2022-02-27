# KMforWin2K
Install the unofficial port of K-Meleon 74 (with Goanna 2.2) for Windows 2000. 

**[Download the Installer](https://github.com/rjjiii/KMforWin2K/releases/download/v74.G.22.1/KM74-g22.1.exe)**

For information check out the K-Meleon website:

http://kmeleonbrowser.org/

http://kmeleonbrowser.org/wiki/InstallerForWindows2000

---
### Notes
This is a self-extracting archive built from Roytam's 7z archives here: http://o.rthost.win/gpc/files1.rt/KM74-g22-20210814.win2000.7z
Source for Goanna 2.2 in Palemoon version 26.5 is here: https://github.com/roytam1/palemoon26
Source code for K-Meleon 74 is here: https://sourceforge.net/projects/kmeleon/files/k-meleon/74.0/

Changes from Roytam's archive were mostly to avoid bugs. They include:

Removed: K-Meleon\Extensions\
* all files and folders
(due to bugs)

Removed K-Meleon\macros:
* adblockplus.kmm
* cookiesmanager.kmm
* ExExPermissions.kmm
* ImageSearch.kmm
* mail.kmm
* newsfox.kmm
* PoliciesManager.kmm
* reload.kmm
* ReloadImages.kmm
* tuxhelper.kmm
(due to bugs)

Added Kmext NT to root directory
(extension manager)

Added
* root\browser\chrome\browser\content\browser\abouthome\bg.jpg
* root\browser\chrome\kmeleon\content\kmeleon\aboutHome\aboutHome.xhtml
(lightweight and more stable home page)

Changes to build the installer itself include:
Added toroot/
* installer.nsi
* License.txt
* ReadMe.txt
