# Timklock Admin

The desktop app for running Timklock: see who's on site, decide exceptions, corrections and time off, approve
timesheets and export payroll. It's the Timklock admin dashboard in a native window, with a tray, notifications and
a badge for what needs a decision.

This repository only holds the installers. Get the latest from **[Releases](../../releases/latest)**.

| System | Download |
| --- | --- |
| macOS, Apple Silicon (M1 and later) | `Timklock-Admin-<version>-arm64.dmg` |
| macOS, Intel | `Timklock-Admin-<version>-x64.dmg` |
| Windows 10 and 11 | `Timklock-Admin-Setup-<version>.exe` |
| Linux, Debian and Ubuntu | `Timklock-Admin-<version>-amd64.deb` |
| Linux, any distribution | `Timklock-Admin-<version>.AppImage` |

## First launch

The builds aren't code-signed yet, so each system asks once:

- **macOS:** open the dmg and drag Timklock Admin into Applications. The first time, right-click the app and
  choose **Open**, then **Open** again. If macOS says the app "is damaged", run
  `xattr -cr "/Applications/Timklock Admin.app"` in Terminal and open it again.
- **Windows:** if SmartScreen says it protected your PC, choose **More info**, then **Run anyway**.
- **Linux:** install the deb with `sudo apt install ./Timklock-Admin-*-amd64.deb`, or make the AppImage executable
  (`chmod +x Timklock-Admin-*.AppImage`) and run it.

## Updates

Windows and Linux download new versions in the background and install them when you restart the app (it offers
"Restart now"). On macOS the app tells you when a new version is out and opens this page to download it.
