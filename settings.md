Manual Settings
===============

- [*System Preferences*](#system-preferences)
	- [*View* menu](#view-menu)
	- [*Accessibility* panel](#accessibility-panel)
	- [*Dock \& Menu Bar* panel](#dock--menu-bar-panel)
	- [*General* panel](#general-panel)
	- [*Keyboard* panel](#keyboard-panel)
	- [*Language \& Region* panel](#language--region-panel)
	- [*Mission Control* panel](#mission-control-panel)
	- [*Touch ID* panel](#touch-id-panel)
	- [*Trackpad* panel](#trackpad-panel)
- [*Dock*](#dock)
	- [Remove all stock apps](#remove-all-stock-apps)
	- [Add icons for apps](#add-icons-for-apps)
	- [Add icons for shortcuts](#add-icons-for-shortcuts)
	- [View options](#view-options)
	- [*Finder* app](#finder-app)
	- [*Preferences* panel](#preferences-panel)
- [*Raycast*](#raycast)
	- [*Preferences* panel](#preferences-panel-1)
- [*Safari*](#safari)
	- [*Preferences* panel](#preferences-panel-2)
- [*Shortcat*](#shortcat)
	- [*Prefences* panel](#prefences-panel)
- [*Zoom*](#zoom)
	- [*General* section](#general-section)
	- [*Video* section](#video-section)
	- [*Audio* section](#audio-section)
	- [*Share Screen* section](#share-screen-section)
	- [*Keyboard Shortcuts* section](#keyboard-shortcuts-section)
- [*Touch ID* in *Terminal*](#touch-id-in-terminal)

The `getup` script can take care of many things, but not everything.

Until the following settings can be set automatically, they'll have to be done manually:

## *System Preferences*

### *View* menu

- Check *Organize Alphabetically*.

### *Accessibility* panel

- *Zoom* section:
	- Check *Use keyboard shortcuts to zoom*.
	- Check *Use scroll gesture with modifier keys to zoom*:
		- Set modifier key to *Control*.
	- Check *Enable Hover Text*:
		- *Options...* button:
			- Set *Activation modifier* to *Command*.
			- Check *Activation lock*.

### *Dock & Menu Bar* panel

- *Wi-Fi* tab:
	- Uncheck *Show in Menu Bar*.
- *Focus* tab:
	- Uncheck *Show in Menu Bar*.
- *Screen Mirroring* tab:
	- Uncheck *Show in Menu Bar*.
- *Display* tab:
	- Uncheck *Show in Menu Bar*.
- *Sound* tab:
	- Uncheck *Show in Menu Bar*.
- *Now Playing* tab:
	- Uncheck *Show in Menu Bar*.
- *Accessibility Shortcuts* tab:
	- Uncheck *Show in Menu Bar*.
	- Check *Show in Control Center*.
- *Battery* tab:
	- Uncheck *Show in Menu Bar*.
	- Check *Show in Control Center*.
	- Check *Show Percentage*.
- *Clock* tab:
	- Set *Show date* to *always*.
	- Check *Show the day of the week*.
	- Check *Use a 24-hour clock*.
	- Check *Flash the time separators*.
	- Check *Display the time with seconds*.
- *Spotlight* tab:
	- Uncheck *Show in Menu Bar*.

### *General* panel

- Set *Highlight color* to *Red*.
- Set *Accent color* to *Red*.

### *Keyboard* panel

- *Keyboard* tab:
	- *Key Repeat* to fastest.
	- *Delay Until Repeat* to shortest.
	- *Modifier Keys...* panel:
		- Set *Select keyboard* to *Karabiner DriverKit*.
		- Set *Caps Lock* to *Escape*.
- *Text* tab:
	- Drag _Text Substitutions.plist_ file into this window to import.
	- Uncheck *Correct spelling automatically*.
	- Uncheck *Capitalize words automatically*.
	- Uncheck *Add period after double-space*.
- *Shortcuts* tab:
	- *Mission Control* section:
		- Check *Turn Do Not Disturb On/Off*, set to *Ctrl+Cmd+D*.
	- *Spotlight* section:
		- Set *Show Spotlight search* to *Shift+Opt+Cmd+Space*. (Use *Cmd+Space* with [Raycast](https://www.raycast.com), installed by `getup brewcask`. See [*Raycast*](#raycast).)
		- Uncheck *Show Finder search window*.
	- *App Shortcuts* section:
		- Add *Close Other Tabs* shortcut:
			- Set *Application* to *All Applications*.
			- Set *Menu Title* to *Close Other Tabs*.
			- Set *Keyboard Shortcut* to *Cmd+Ctrl+W*.
			- Click *Add*.
		- Add *Merge All Windows* shortcut:
			- Set *Application* to *All Applications*.
			- Set *Menu Title* to *Merge All Windows*.
			- Set *Keyboard Shortcut* to *Cmd+Opt+W*.
			- Click *Add*.
	- Check *Use keyboard navigation to move focus between controls*.
- *Input Sources* tab:
	- Check *Use Caps Lock key to switch to and from last used Latin input source*.

### *Language & Region* panel

- Set *Preferred languages*:
	- *English (Canada)*
	- *English*
	- *French (Canada)*
	- *French*
	- *日本語* (Japanese)
- *Translation Languages…* button:
	- Download the following:
		- *English (UK)*
		- *English (US)*
		- *French (France)*
		- *Japanese*
- *Advanced…* button:
	- *Dates* tab:
		- Set *Short* to *2022-06-01*.
		- Set *Medium* to *1 Jun 2022*.
		- Set *Long* to *1 June 2022*.
		- Set *Full* to *Wednesday 1 June 2022*.
	- *Times* tab:
		- Set *Short* to *07:08* (24 hours).
		- Set *Medium* to *07:08:09* (24 hours).
		- Set *Long* to *07:08:09 JST* (24 hours).
		- Set *Full* to *07:08:09 Japan Standard Time* (24 hours).

### *Mission Control* panel

- Top section:
	- Check *Automatically rearrange Spaces based on most recent use*.
	- Check *When switching to an application, switch to a Space with open windows for the application*.
	- Check *Group windows by application*.
	- Check *Displays have separate Spaces*.
- *Keyboard & Mouse Shortcuts* section:
	- Set *Show Desktop* to *Right Shift*.
- *Hot Corners…* button:
	- *Active Screen Corners* section:
		- Top left to *Lock Screen*.
		- Top right to *Disable Screen Saver*.
		- Bottom left to *Quick Note*.
		- Bottom right to *Desktop*.

### *Touch ID* panel

- Add fingerprints of right index, left index, and right pinky.

### *Trackpad* panel

- *More Gestures* tab:
	- Check *App Exposé*.

## *Dock*

### Remove all stock apps

- *Launch Pad*
- *Messages*
- *Mail*
- *Maps*
- *Photos*
- *FaceTime*
- *Calendar*
- *Contacts*
- *Reminders*
- *Notes*
- *Apple TV*
- *Music*
- *Podcasts*
- *App Store*

### Add icons for apps

- *Finder*
- *iTerm*
- *Safari*
- *Firefox*
- *Chrome*
- *Slack*
- *Teams*
- *Viber*
- *Zoom*
- *OneNote*
- *Visual Studio Code*
- *1Password*
- *Settings*

### Add icons for shortcuts

- *~/Downloads* (display as folder, view content as grid)
- *~/Desktop* (display as folder, view content as grid)
- *~/Box Sync/User/Screenshots* (display as stack, view content as grid)

### View options

- Open home folder in new Finder window, select *View > Show View Options* from menu
	- Set *Group By* to *none*.
	- Set *Sort By* to *name*.
	- Check *Show item info*.
	- Check *Show Library folder*.
	- Click *Use as Defaults* button.

### *Finder* app

### *Preferences* panel

- *General* tab:
	- *Show these items on the desktop* section:
		- Check *Hard disks*.
		- Check *External disks*.
		- Check *CDs, DVDs, and iPods*.
		- Check *Connected servers*.
	- Set *New Finder windows show* to home folder.
- *Sidebar* tab:
	- Check *Recents*.
	- Check *Applications*.
	- Check *Desktop*.
	- Check *Documents*.
	- Check *Desktop*.
	- Check home folder.
	- Check *iCloud Drive*.
	- Check computer.
	- Check *Hard disks*.
	- Check *External disks*.
	- Check *CDs, DVDs, and iOS Devices*.
	- Check *Cloud storage*.
	- Check *Bonjour computers*.
	- Check *Connected servers*.
	- Check *Recent tags*.
	- Other options should be left unchecked.
- *Advanced* tab:
	- Check *Show all filename extensions*.
	- Check *Remove items from the Trash after 30 days*.
	- *Keep folders on top* section:
		- Check *In windows when sorting by name*.
		- Uncheck *On Desktop*.
- Drag home folder with *Cmd+Opt* to Desktop to create alias.

## *Raycast*

### *Preferences* panel

- *General* tab:
	- Set *Raycast Hotkey* to *Cmd+Space*. (Be sure to set the keyboard shortcut for Spotlight first. See [*Keyboard* panel](#keyboard-panel).)
- *Extensions* tab:
  - Clear keyboard shortcut for *Navigation > Switch Windows*. (`Alt+Tab` should be reserved for _AltTab_.)

## *Safari*

### *Preferences* panel

- *General* tab:
	- Set *Homepage* to URL with page with quick links, if any.
	- Set *New windows open with* to *Homepage*.
	- Set *New tabs open with* to *Homepage*.
- *Tabs* tab:
	- Set *Tab layout* to *Compact*.
- *AutoFill* tab:
	- Uncheck *Using information from my contacts*.
	- Uncheck *User names and passwords*.
	- Uncheck *Credit cards*.
	- Uncheck *Other forms*.
- *Search* tab:
	- Change *Search engine* to *DuckDuckGo*.
- *Privacy* tab:
	- Uncheck *Allow privacy-preserving measurement of ad effectiveness*.
- *Advanced* tab:
	- Check *Show full website address*.
	- Check *Press Tab to highlight each item on a webpage*.


## *Shortcat*

### *Prefences* panel

- *General* tab:
	- Check *Launch at login*.
	- Set *Activation Shortcut* to *Opt+Space*.

## *Zoom*

### *General* section

- Uncheck *Use dual monitors*.
- Uncheck *Add Zoom to macOS menu bar*.

### *Video* section

- Check *Adjust for low light*, set to *Auto*.
- Check *Stop my video when joining a meeting*.
- Check *Always show video preview dialog when joining a video meeting*.
- Set *Maximum participants displayed per screen in Gallery View* to *49 participants*.

### *Audio* section

- Check *Automatically join computer audio when joining a meeting*.
- Check *Mute my mic when joining a meeting*.
- Check *Press and hold 'Space Key' to temporarily unmute*.

### *Share Screen* section

- Set *Window size when screen sharing* to *Maximize window*.

### *Keyboard Shortcuts* section

- Check *Enable Global Shortcut* for:
	- *Mute/Unmute My Audio*
	- *Start/Stop Video*

## *Touch ID* in *Terminal*

The `getup pamtouchid` part takes extra care to modify the PAM config to allow Touch ID to be used instead of a password when trying to access root, i.e. running `sudo`.

However, it may not work if the shell is running within `tmux` in iTerm. For this, `getup brewapps` will already install the necessary `pam-reattach` package. To use it, you will need to add it manually.

See [pam_reattach](https://github.com/fabianishere/pam_reattach) for details.
