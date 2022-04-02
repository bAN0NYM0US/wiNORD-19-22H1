# Nordic Windows 10 LTSC IoT 19044.1620

![alt text](https://i.imgur.com/fGxmBKu.png?raw=true)

# Known Issues
Microsoft Photo's app is missing from factory and I haven't been able to get the .appx Bundle to install correctly yet. This can be manually fixed by opening the Microsoft Store, and just downloading it from there, then setting it as the default application for viewing photos.

# Install Procedure
ISO will boot directly to the Drive Selection screen. Pick a drive/partition and install. Once install is complete, OOBE will load. If you don't have direct internet access, you will be asked to connect to wifi first. If you have direct access, OOBE will load directly to Local Account. Enter a username and password. Everything will finish up and you will be at the Desktop. (slower computer may see the Post-Setup screen still going, but this is normally done in the backgorund before the desktop loads on faster machines). Don't be alarmed, this is just removing Edge, installing Brave and VLC.

# Manual Procedure
Font:

Navigate to C:\NORD and manually install the Source Code Pro font (select all, right-click, install). Once complete, run the .reg file to set it as the system font (reboot is required).

Theme:

Navigate to C:\NORD and Right-click ThemeTool.exe, open as administrator, Click "Yes". Click the "Install" Button and reboot. Repeat steps for opening ThemeTool.exe and now select the Nord Theme and click "Patch & Apply".

Optional:

Install AutoDarkMode and configure to automatically switch based on sunrise/sunset or at a specific time. This will work with the Nord theme.

Additional Info:

You will need to run the font .reg file, and Applying the Nord theme with ThemeTool.exe after every major Windows Update.

# Changelog

## [v0.9] - Windows 10 LTSC IoT 19044.1620
	### Added
		- C:/NORD Directory
			- AutoDarkMode
			- OldNewExplorer
			- Font
				- Source Code Pro
				- Registry file to enable font as system default
			- Cursor
				- Nord/Bouquet
			- SecureUxTheme
		- Embedded Nord Light/Dark Theme to C:\Windows\Resources\Themes
		- Added more nordic wallpapers

	### Changed
		- Setup boots directly to Drive Selection
		- OOBE boots directly to Local Account setup

	### Fixed
		- UAC always being enabled (can now be disabled)
		- Brave Browser installer is now completely silent
		- User input is no longer needed to exit CMD after Microsoft Store install

## [v0.8] - Windows 10 LTSC IoT 19044.1387
	### Added
		- Brave Browser
		- VLC Media Player
		- Microsoft Store
		- Xbox
		- 7th Anniversary Wallpaper (NORD)
		- Blured Lock Screen Wallpaper

	### Removed
		- Microsoft Edge
		- Delete Desktop Icons (borked)

## [v0.7] - Windows 10 LTSC IoT 19044.1387

	### Changed
		- Default UI to Dark Mode

	### Removed
		- Recommended Apps & Settings

## [v0.6] - Windows 10 LTSC IoT 19044.1387
	### Added
		- KB5007253 (19044.1387)
    
	### Changed
		- Taskbar set to Small
		- This PC as Default for File Explorer
		
	### Removed
		- Quick Access from File Explorer

## [v0.5] - Windows 10 LTSC IoT 19044.1288
	### Removed
		- UAC Warnings
		- Remote Desktop
		- Enterprise Settings

## [v0.4] - Windows 10 LTSC IoT 19044.1288
	### Added
		- Windows 10 LTSC 21H2 IoT Generic Key
		- Compact OS

	### Changed
		- EST Time Zone as Default
		- US English as Default

## [v0.3] - Windows 10 LTSC 19044.1288
	### Removed
		- OOBE Microsoft Account
		- OOBE Privacy Settings

## [v0.2] - Windows 10 LTSC 19044.1288
	### Removed
		- Microsoft Telemetry
		- Install Selections
		- Install EULA

## [v0.1] - Windows 10 LTSC 19044.1288
	### Removed
		- Language Packs
		- Internet Explorer
		- Windows Media Player
		
# Contributions
	- Nord Theme by niivu
		https://www.deviantart.com/niivu/art/Nord-Windows-10-Theme-837266272
	- Bouquet Cursor by niivu
		https://www.deviantart.com/niivu/art/Bouquet-Cursors-734306936
	- Nord Cursor by Abod1969
		https://www.deviantart.com/abod1960/art/Nord-Cursor-887885140
	- Wallpaper by Anonymous
		http://4chan.org/wg
	- Source Code Pro Front by Paul D. Hunt
		https://github.com/adobe-fonts/source-code-pro
	- Wiondows 10 by Microsoft
		(link to 21H2 LTSC IoT not available)
	- Start 11 by Stardock
		https://www.stardock.com/products/start11/
	- OldNewExplorer by Tihiy
		https://www.majorgeeks.com/files/details/oldnewexplorer.html
	- SecureUxTheme by namazso
		https://github.com/namazso/SecureUxTheme
