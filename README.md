# Nordic Windows 10 21H2 LTSC IoT 19044.1620

![alt text](https://i.imgur.com/fGxmBKu.png?raw=true)

# Known Issues
Microsoft Photo's app is missing from factory and I haven't been able to get the .appx Bundle to install correctly yet. This can be manually fixed by opening the Microsoft Store, and just downloading it from there, then setting it as the default application for viewing photos.

# Manual Procedure
After installation is complete, you will need to navigate to C:\NORD and manually install the Source Code Pro font, and then run the .reg file to set it as the system font (reboot is required after). Next you will have to open OldNewExplorer and install. Once installed, tick the box for "Use command bar instead of ribbon" and uncheck everything else. Now, Right-click ThemeTool.exe as administrator, Click "Yes". Click the Install Button and reboot. Repeat steps for opening ThemeTool.exe and now select the Nord Theme and click Patch & Apply.
Optional step is to install AutoDarkMode and configure to automatically switch based on sunrise/sunset or at a specific time.
Running the font .reg file, and Applying the Nord theme will need to be done again after every major Windows Update.

# Changelog

## [v0.9] - Windows 10 LTSC IoT 19044.1620
	### Added
		- C:/NORD Directory
			- AutoDarkMode
			- OldNewExplorer
			- Font
				- Source Code Pro Fonts
				- Registry file to enable font as system default
			- Cursor
				- Nord/Bouquet
			- SecureUX Patcher
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
	### Added
		- Ability to Activate with Home/Pro Embedded Key

	### Changed
		- Default UI to Dark Mode

	### Removed
		- Microsoft Monitoring Options
		- Recommended Apps & Settings

## [v0.6] - Windows 10 LTSC IoT 19044.1387
	### Added
		- KB5007253 (19044.1387)
    
	### Changed
		- Taskbar set to Small
		- Removed Quick Access from File Explorer
		- This PC as Default for File Explorer

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
		- Windows Defender
