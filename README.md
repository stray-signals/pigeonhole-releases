# pigeonhole

pigeonhole sorts school and event photos by face. during a session you take one reference photo of each person with the phone app, and the desktop app matches every other photo from the day to the right name and files it into a folder per person. it also handles the part after orders come in: combining pixieset order CSVs, pulling the ordered photos into one folder for the lab, and building an accounting report.

this repo is just where the desktop installers live. what changed in each version is in [CHANGELOG.md](CHANGELOG.md).

## installing on windows

1. go to the [latest release](https://github.com/stray-signals/pigeonhole-releases/releases/latest) and download `Pigeonhole-Setup-` followed by the version number, ending in `.exe`
2. open it. windows will probably show a blue box that says "Windows protected your PC". that's because the installer isn't signed yet, not because anything's wrong with it. click **More info**, then **Run anyway**
3. pigeonhole installs and opens on its own. there's a shortcut on your desktop and in the start menu

you only see that windows warning the first time.

## updates

you don't need to do anything. pigeonhole checks for updates while it's open. small ones download in the background and install the next time you close it. bigger ones ask before restarting, and you can pick later.

the version number is in the bottom left corner of the home screen.

## mac

each release has a mac version too (`.dmg`, pick `arm64` for newer apple silicon macs, `x64` for older intel ones). it isn't signed either, so the first time you open it, right-click the app and choose **Open** instead of double-clicking.

macs can't update pigeonhole on their own yet. when there's a new version, the home screen shows a download link.

## questions or problems

contact@straysignals.dev
