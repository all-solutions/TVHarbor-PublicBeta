# TVHarbor Public Beta

TVHarbor is a desktop client for **TVHeadend** with an integrated VLC-based player.

> [!IMPORTANT]
> TVHarbor is currently in **public beta**. The application is already stable in daily testing, but features and behavior may still change before the first final release.

At the moment, the public beta is available for **Windows x64 only**. Linux and macOS versions are planned after the Windows beta phase.

## Features

### Live TV

- Browse all channels provided by TVHeadend
- Search and filter channels by name
- Display channel logos, including cached and SVG logos
- Show the currently running programme below each channel
- Start playback from the channel list or via double-click
- Stop and resume playback
- Switch channels directly in the main window
- Fullscreen playback
- Integrated VLC-based playback
- Bundled VLC runtime libraries — no separate VLC installation required
- Volume control with persistent startup volume
- Mute / unmute control
- Automatic EPG refresh while watching
- Current and next programme information
- Cinema Mode for a larger, distraction-free viewing area

### Programme guide

- View current and upcoming programmes for all channels
- Channel logos directly in the guide
- Local programme times
- Start live playback by double-clicking a programme
- Manual EPG refresh

### Recordings

- Schedule recordings for the selected channel and programme
- Schedule recordings directly from the programme guide
- Stop active recordings
- View scheduled, active, completed and failed recordings
- Search and filter recordings
- Play completed recordings in the integrated player
- Delete recordings from TVHeadend

### TVHeadend server profiles

- Configure multiple TVHeadend server profiles
- Store server name, URL, username and password
- Test a connection before saving
- Switch between configured servers directly from TVHarbor
- Add, rename and delete profiles
- Persist the active server between application starts

### Appearance and layout

- Dark and light themes
- Collapsible navigation sidebar
- Persistent sidebar state
- Persistent window size and position
- Responsive layout with priority on the video area
- Cinema Mode for an expanded playback view

### Settings

- Startup volume
- EPG refresh interval
- Recording padding before and after programmes
- Clear cached channel logos
- Application appearance
- Open the TVHeadend web interface directly from TVHarbor

## Screenshots

### Main window

![TVHarbor Main Window](https://raw.githubusercontent.com/all-solutions/TVHarbor/main/doc/Main-Windows.jpg)

### Programme guide

![TVHarbor EPG](https://raw.githubusercontent.com/all-solutions/TVHarbor/main/doc/EPG.jpg)

### Recordings

![TVHarbor Recordings](https://raw.githubusercontent.com/all-solutions/TVHarbor/main/doc/Recordings.jpg)

### Cinema Mode

![TVHarbor Cinema Mode](https://raw.githubusercontent.com/all-solutions/TVHarbor/main/doc/Cinema-Mode.jpg)

### Light Theme

![TVHarbor Light Theme](https://raw.githubusercontent.com/all-solutions/TVHarbor/main/doc/Light-Thema.jpg)

## Requirements

- Windows x64
- A reachable TVHeadend server
- TVHeadend user credentials with access to the required channels, EPG and recording functions

A separate VLC installation is **not required**. The necessary VLC runtime libraries are bundled with TVHarbor.

## Public Beta

This repository is used for the **public beta distribution and feedback** of TVHarbor.

The application itself is still under active development. During the beta phase you may encounter bugs, UI changes or incomplete functionality.

If you find a problem, please open an **Issue** in this repository and include as much information as possible, for example:

- TVHarbor version
- Windows version
- TVHeadend version
- A short description of what happened
- Steps to reproduce the problem
- Screenshots or logs, if available

Feature requests and general feedback are also very welcome.

## Planned

Among the features currently being considered for future versions are:

- Linux support
- macOS support
- Subtitle / closed-caption track selection
- Audio track selection
- Additional playback and usability improvements

## Source code

TVHarbor is currently distributed as a **public beta build**, while the main development repository remains private.

A final decision on whether the complete TVHarbor source code will be published as open source has not yet been made.

## Disclaimer

TVHarbor is an independent project and is not affiliated with or endorsed by the TVHeadend project or VideoLAN.

TVHeadend is a separate open-source project. VLC and libVLC are trademarks and technologies of the VideoLAN project.
