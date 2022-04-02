# Nordic Minimalist Windows 10 LTSC IoT 19044.1620

![alt text](https://i.imgur.com/fGxmBKu.png?raw=true)

# Known Issues
Microsoft Photo's app is missing from factory and I haven't been able to get the .appx Bundle to install correctly yet. This can be manually fixed by opening the Microsoft Store, and just downloading it from there, then setting it as the default application for viewing photos.

# Install Procedure
ISO will boot directly to the Drive Selection screen. Pick a drive/partition and install. Once install is complete, OOBE will load. If you don't have direct internet access, you will be asked to connect to wifi first. If you have direct access, OOBE will load directly to Local Account. Enter a username and password. Everything will finish up and you will be at the Desktop. (slower computer may see the Post-Setup screen still going, but this is normally done in the backgorund before the desktop loads on faster machines). Don't be alarmed, this is just removing Edge, installing Brave and VLC.

# Manual Procedure
Post-install instructions can be found in C:\NORD\Install Guide.txt

Additional Info:

You will need to run the font .reg file, and reapply the Nord theme with ThemeTool.exe after every major Windows Update.

# Downloads
## (Compiling not finished)
This is NOT activated. You will need to activate this with a Volume License or, for EDUCATIONAL PURPOSE use [EzHWID](https://github.com/ExeCsrss/EzHWID)

[Nord Colour 7th Anniversary Wallpapers](https://drive.google.com/drive/folders/16Dnms-cryPyQ2nF4wxSnjTW3jtO9ilMg?usp=sharing)

# Changelog

## Windows 10 LTSC IoT 21H2 19044.1620
	### Added
		- Brave Browser
		- VLC Media Player
		- Microsoft Store
		- Xbox
		- C:/NORD Directory
			- Font
				- Source Code Pro
				- Registry file to enable font as system default
			- Cursor
				- Nord/Bouquet
			- AutoDarkMode
			- OldNewExplorer
			- SecureUxTheme
		- Embedded Nord Theme to C:\Windows\Resources\Themes
		- Added more nordic wallpapers
   		- Windows 7th Anniversary wallpaper with Nord colour pallet to C:\Windows\Web\Wallpaper\Windows
 		- Blured Windows 7th Anniversary wallpaper with Nord colour pallet to C:\Windows\Web\Screen
		- Embedded Nord Light/Dark Theme to C:\Windows\Resources\Themes

	### Changed
		- Setup boots directly to Drive Selection (details under ### Removed/Setup)
		- OOBE boots directly to Local Account setup (details under ### Removed/OOBE)
		- Default UI to Full Dark Mode
		- EST Time Zone as Default
		- US English as Default
		- Taskbar set to Small
		- This PC as Default for File Explorer

	### Fixed
		- UAC can now be disabled
		- Brave Browser install is now completely silent
		- User input is no longer needed to exit CMD after Microsoft Store install
    
	### Removed
		- Setup:
			- Language Select
			- EULA
			- Product Key Input/Version Select
		- OOBE:
			- Language/Region
			- Keyboard Select
			- Online Account
			- Telemetry Switches
		- Microsoft Edge
		- Microsoft Telemetry
		- Recommended Apps & Settings
		- Quick Access from File Explorer
		- Language Packs
		- Windows Media Player
		- Internet Explorer
		- Taskbar:
			- Meet Now
			- Notification Centre
			- Search
			- People

# Contributions
	- Nord Theme by niivu
		https://www.deviantart.com/niivu/art/Nord-Windows-10-Theme-837266272
	- Bouquet Cursor by niivu
		https://www.deviantart.com/niivu/art/Bouquet-Cursors-734306936
	- Nord Cursor by Abod1960
		https://www.deviantart.com/abod1960/art/Nord-Cursor-887885140
	- Nord Oreo by Abod1960
		https://www.deviantart.com/abod1960/art/Oreo-Nord-875312546
	- Wallpapers in Nord Theme by Anonymous
		http://4chan.org/wg
	- Source Code Pro Font by Paul D. Hunt
		https://github.com/adobe-fonts/source-code-pro
	- Windows 10 by Microsoft
		(link to 21H2 LTSC IoT not available)
	- Start 11 by Stardock
		https://www.stardock.com/products/start11/
	- Auto Dark Mode by Armin2208
		https://github.com/AutoDarkMode/Windows-Auto-Night-Mode
	- OldNewExplorer by Tihiy
		https://www.majorgeeks.com/files/details/oldnewexplorer.html
	- SecureUxTheme by namazso
		https://github.com/namazso/SecureUxTheme
