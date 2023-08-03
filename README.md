# Border-Locker

Border-Locker is a simple utility designed to maintain the cursor within the bounds of ROBLOX Corporation's game window. This tool is especially useful for gamers with multi-monitor setups or for those who prefer playing ROBLOX in windowed mode.

## Why False Virus Detection?

Border-Locker may sometimes be flagged as a false positive by certain antivirus software due to the nature of its operations. It uses Windows API functions for window and cursor management, such as `FindWindow`, `GetCursorPos`, `SetCursorPos`, `GetWindowRect`, and `ScreenToClient`, which can be perceived as suspicious behavior by some antivirus engines.

However, it's important to note that Border-Locker is not a malicious program. The operations it performs are legitimate and aimed at enhancing the ROBLOX gaming experience by restricting the cursor movement within the game window. The window and cursor management operations are standard and used for legitimate purposes.

## How to Use

1. Download the precompiled executable file from the [releases](https://github.com/Xenon-Trash/Border-Locker/releases) section.
2. Run the `BorderLocker.exe` application.
3. The application will begin monitoring the ROBLOX window and cursor position. If the cursor attempts to move outside of the game window, Border-Locker will reposition it within the window.
4. Press the 'INSERT' key to toggle the border-locking feature ON or OFF as required. The current status of the application will be displayed in the console.

**Disclaimer:** This software is provided as-is without any warranty. Use it at your own risk. The developers of this software are not responsible for any damage or unwanted results caused by its usage.

## Requirements

- Windows operating system
- ROBLOX game client

## Important Note

This software is intended for enhancing the ROBLOX gaming experience. Please respect the terms and conditions of ROBLOX Corporation when using this software. The developers of this software are not affiliated with ROBLOX Corporation and are not responsible for any violations of its terms and conditions that may occur from the use of Border-Locker.
