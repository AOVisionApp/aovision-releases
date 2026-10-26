# AOVision for Windows

AOVision provides a configurable radar overlay for Albion Online. This public
repository is reserved for Windows installers and update files.

## Prelaunch status

The [latest published Windows installer](https://github.com/AOVisionApp/aovision-releases/releases/latest)
is AOVision 1.2.5, an unsigned prelaunch privacy maintenance build published by
AOVision automation. It keeps build-machine account paths out of distributed catalog metadata. The original update route remains available for existing installations.
An isolated check using the preserved 1.2.3 updater successfully found and
downloaded 1.2.4 through that route with checksum verification. The branded feed
also correctly reported version 1.2.4 up to date during that check. See the
[1.2.5 release details](https://github.com/AOVisionApp/aovision-releases/releases/tag/v1.2.5).
AOVision includes independent
Radar, Players and Broad Player Detector overlays with saved layouts, per-window
Radar Mode and a shared Settings window. It adds a filtered live detector count,
brief arrival flashes, a shared electronic sound alert and the integrated Inspector.
Colored solo/group tracking marks remain available. Remembered arrival directions
and distances are uncertain guesses; they do not track player positions.
Mounted estimates remain experimental.
Discord sign-in and verified Admin access have passed online checks. New subscription purchases remain closed.

[Releases](https://github.com/AOVisionApp/aovision-releases/releases) contain
downloads and release notes. Installed users can open the launcher, stop the radar,
then choose **Check for updates → Download update → Install and restart**.
Installed upgrade and restart verification remains pending.

## Requirements

- Windows 10 or 11, 64-bit.
- Npcap with WinPcap compatibility enabled.
- Administrator permission for packet capture.
- Albion Online running in borderless windowed fullscreen.
- Internet access for Discord sign-in and verified account access.

## Account access

The launcher requires a signed-in account with verified access before starting
the radar. A download alone does not grant a license or subscription. Approved
Admin accounts can sign in during setup. Check the latest release notes for account-service availability.

Website: [AOVision](https://aovision.pages.dev).
Support: [AOVisionApp@gmail.com](mailto:AOVisionApp@gmail.com).
