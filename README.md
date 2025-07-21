<p align="center">
<img src="https://r47dev.github.io/wh-rat-v4/res/ratlogo.png" height="170"><br>
  
<h1 align="center">  Wh -Rat V4 (Remote Administration framework )</h1> 

wh-rat-v4 Released

site is live at https://r47dev.github.io/wh-rat-v4/ 

# WH-RAT V4.2 - Complete Description and Version Comparison

## Overview of WH-RAT V4.2

WH-RAT V4.2 is the latest iteration of a remote access tool (RAT) designed for both Windows and Android platforms, offering advanced surveillance, system management, and client control capabilities. It builds upon the features of its predecessors (V2.6.0.3 and V3) with enhanced connection stability, new surveillance features like Hidden Virtual Network Computing (HVNC), and expanded stealing capabilities for cryptocurrencies and application data. The version introduces a comprehensive set of tools for remote administration, including a Service Manager, UAC bypass options, and a "ToolBox" for manipulating system UI elements. For Android, it retains robust features from V3 while improving socket connections and adding theme enhancements.

Below is a detailed description of WH-RAT V4.2's features, followed by a comparison with V2.6.0.3 and V3 to highlight key differences and improvements.

---

## WH-RAT V4.2 Features

### Windows Features

- **Fun**:
  - Chat: Real-time communication with the target system.
  - Bluescreen (BSOD): Trigger a simulated Blue Screen of Death.
  - Message Box: Display custom messages on the target system.
  - Fun Menu: Includes actions like monitor on/off, CD tray open/close, and other system manipulations.
- **Surveillance**:
  - Hidden Virtual Network Computing (HVNC): Stealthy remote desktop access.
  - Webcam: Capture live video from the target’s webcam.
  - Live Microphone: Record audio in real-time.
  - Keylogger (Live/Offline): Capture keystrokes with both live and offline modes.
  - Screen Control: Monitor and control the target’s screen.
  - Stealer: Extract browser data (history, cookies, passwords, cards) and application data (FileZilla, Discord, Telegram).
  - Crypto Stealer: Target cryptocurrencies including BTC, ETH, TRC20, XRP, BNB, SOL, USDC, TRX.
- **System**:
  - Reverse Proxy (Socks5): Bypass network restrictions for enhanced connectivity.
  - Process Manager: View, kill, and manage running processes.
  - File Manager: Browse, upload, download, encrypt, and decrypt files.
  - Registry Manager: Edit and manage the Windows registry.
  - Shell: Execute commands via cmd or PowerShell.
  - Startup: Add or remove the client from system startup.
  - Clipboard: Get or set clipboard content.
  - Service Manager: List, start, stop, pause, or refresh system services.
- **UAC Bypass**:
  - Methods: Cmstp, Windir + Disk Cleanup, Fodhelper.
  - Options: Request admin privileges or de-escalate to user level.
- **Client**:
  - Actions: Close, relaunch, or uninstall the client.
  - Anti-Kill: Start/stop protection to prevent client termination (configurable via Builder checkbox).
- **Power**:
  - Shutdown or restart the target system.
- **Extra**:
  - CrashSystem: Force a system crash.
  - Block Screen (Blackout): Enable/disable a full-screen blackout.
  - ToolBox: Toggle Explorer, Desktop, Clock, Start Button, Taskbar, and Notifications (show/hide).

### Android Features

- **Manager**:
  - Files: Browse, delete, download, and launch files.
  - SMS: Read or send messages.
  - Calls: Manage call logs and initiate calls.
  - Contacts: Read or save contacts.
  - Account: Access account information.
- **Streaming**:
  - Live Screen: Real-time screen monitoring with control or block options.
  - Live Camera: Stream video from the device’s camera.
  - Microphone: Record audio in real-time.
  - Keylogger: Capture keystrokes (live or offline).
  - Location: Track device location.
  - Call Recorder: Record phone calls.
  - Notification: Monitor device notifications.
- **Admin**:
  - Request Admin Rights: Gain elevated privileges.
  - Lock Screen: Lock the device screen.
  - Wipe Data: Erase device data.
  - Device Info: Retrieve detailed device information.
- **More**:
  - Call Number: Initiate phone calls.
  - APK Download: Download applications remotely.
  - Show Message: Display custom messages on the device.
  - Clipboard: Get or set clipboard content.
  - Open Link: Open URLs on the device.
  - Shell CMD: Execute shell commands.
- **Client**:
  - Restart Connection: Re-establish client connection.
  - Stop Anti-Uninstall: Disable anti-uninstall protection.
  - Self-Uninstall: Remove the client from the device.
  - Edit Connection: Modify connection settings.
- **Additional**:
  - Injection into Real APK: Embed the client into legitimate APKs.
  - Encryption/Protection: Secure the client with encryption.
  - Accessibility Bypass: Circumvent accessibility restrictions.
  - Fully Custom APK Build: Create tailored APKs with specific configurations.

### Application Information

- **Framework Version**: Not specified in V4.2 (V3 was 3.0.1.0).
- **Release Date**: Not specified in V4.2 (V3 was June 2, 2024).
- **Powered By**: WH-Cyberspace.

---

## Version Comparison: WH-RAT V2.6.0.3, V3, and V4.2

Below is a table summarizing the main differences between WH-RAT V2.6.0.3, V3, and V4.2 for both Windows and Android platforms.

| **Feature/Aspect** | **WH-RAT V2.6.0.3** | **WH-RAT V3** | **WH-RAT V4.2** |
| --- | --- | --- | --- |
| **Release Date** | Not specified | June 2, 2024 | Not specified |
| **Framework Version** | Not specified | 3.0.1.0 | Not specified |
| **Windows Features** |  |  |  |
| \- **Connection Enhancements** | Basic connection setup | Improved Windows socket connection | Enhanced Windows socket, Port On/Off toggle on dashboard |
| \- **Surveillance** | Keylogger, Screen Monitor, Remote Desktop (optional), Password Recovery (Chromium) | Live Keylogger, Remote Desktop, Live Chat, Clipboard Access | HVNC, Webcam, Live Microphone, Keylogger (Live/Offline), Screen Control, Stealer (Browser, Crypto, Apps) |
| \- **System Management** | File Manager, Task Manager, Encryption (AES, RC6, etc.), Startup, Empty Bin | File Browser, Process Manager, Shell, Startup, Clipboard | File Manager (Encrypt/Decrypt), Process Manager, Registry Manager, Shell (cmd/ps), Service Manager, Startup, Clipboard |
| \- **Stealer** | Password recovery (Chromium browsers) | Not explicitly mentioned | History, Cookies, Passwords, Cards, Crypto (BTC, ETH, TRC20, XRP, BNB, SOL, USDC, TRX), FileZilla, Discord, Telegram |
| \- **Fun Features** | Change Wallpaper, BSOD, Fork Bomb, Red Virus, Mouse/Keyboard Lock | Not explicitly mentioned | Chat, Bluescreen, Message Box, Fun Menu (Monitor On/Off, CD Tray Open/Close) |
| \- **UAC Bypass/Options** | Not mentioned | Raise Permission Level | Cmstp, Windir + Disk Cleanup, Fodhelper; Request Admin, De-escalate to User |
| \- **Power Options** | Log Out, Reboot, Shutdown, Hibernate, Suspend | Not explicitly mentioned | Shutdown, Restart |
| \- **Client Management** | Close, Close and Delete, Rename Client | Reconnect, Update Client, Kill Process | Close, Relaunch, Uninstall, Anti-Kill (Start/Stop) |
| \- **Extra Features** | Monitor Rotation, Auto Recovery, Desktop/Taskbar Icon Show/Hide | Not explicitly mentioned | CrashSystem, Block Screen (Blackout), ToolBox (Explorer/Clock/StartButton/Taskbar/Notification Show/Hide) |
| \- **Reverse Proxy** | Not mentioned | Not mentioned | Socks5 Reverse Proxy for bypassing network restrictions |
| **Android Features** |  |  |  |
| \- **Connection Enhancements** | Optimized APK, Add/Remove Permission in Injection | Not explicitly mentioned | Enhanced Android socket connection, Theme improvements |
| \- **Manager** | File Manager (Delete, Download, Launch, etc.) | Files, SMS (Read/Send), Calls, Contacts (Read/Save), Account | Files, SMS (Read/Send), Calls, Contacts (Read/Save), Account |
| \- **Streaming/Surveillance** | Keylogger, Screen Monitor | Live Screen (Control/Block), Camera, Microphone, Keylog, Location, Call Recorder, Notification | Live Screen (Control/Block), Camera, Microphone, Keylog (Live/Offline), Location, Call Recorder, Notification |
| \- **Admin** | Not mentioned | Request Admin Rights, Lock Screen, Wipe Data, Device Info | Request Admin Rights, Lock Screen, Wipe Data, Device Info |
| \- **Additional Features** | Not mentioned | Call Number, APK Download, Show Message, Clipboard, Open Link, Shell CMD | Call Number, APK Download, Show Message, Clipboard, Open Link, Shell CMD |
| \- **Client Management** | Fix for APK not opening on some MIUI phones | Restart Connection, Stop Anti-Uninstall, Self-Uninstall, Edit Connection | Restart Connection, Stop Anti-Uninstall, Self-Uninstall, Edit Connection |
| \- **Injection/Customization** | Not mentioned | Injection into Real APK, Encrypt, Protect, Accessibility Bypass, Custom APK Build | Injection into Real APK, Encrypt, Protect, Accessibility Bypass, Custom APK Build |
| **Application Updates** | Security update, GUI improvements, Auto Application Update | Security update, GUI improvements, Optimization | Not explicitly mentioned |
| **Notable Additions** | Permission Manager on Builder, Pest Text in Phone, Background Music Change | Live Chat, Accessibility Bypass, Custom APK Build | Crypto Stealer, Service Manager, Anti-Kill, ToolBox, CrashSystem, Blackout Screen |
| **Unsupported Features** | Does not support DNS | Not mentioned | Not mentioned |

---

## Key Differences and Evolution

1. **WH-RAT V2.6.0.3**:

   - Focused on foundational remote access capabilities, such as File Manager, Keylogger, and Screen Monitor.
   - Introduced file encryption (AES, RC6, BlowFish, Salsa20, Cast6, TwoFish) and password recovery for Chromium browsers.
   - Android updates included keylogger and screen monitor optimizations, with a fix for MIUI phone compatibility.
   - Notable for its lightweight client size (20KB minimum) and features like Red Virus and Fork Bomb.

2. **WH-RAT V3**:

   - Significantly expanded Android capabilities with SMS, calls, contacts, live camera, microphone, location tracking, and notifications.
   - Introduced Live Chat for Windows and more robust client management (reconnect, update, kill process).
   - Added Accessibility Bypass and Custom APK Build for Android, enhancing stealth and deployment options.
   - Improved GUI and security updates for the application.

3. **WH-RAT V4.2**:

   - Major leap in Windows features with HVNC, Crypto Stealer, and Socks5 Reverse Proxy for bypassing network restrictions.
   - Enhanced system management with Service Manager, Registry Manager, and advanced UAC bypass methods.
   - Introduced ToolBox for UI manipulation (Explorer, Desktop, Clock, etc.) and CrashSystem/Blackout features.
   - Android features remained consistent with V3 but added socket and theme enhancements for better performance and usability.
   - Anti-Kill protection and Service Manager added for improved persistence and control.

---

## Conclusion

WH-RAT V4.2 represents a significant evolution from V2.6.0.3 and V3, offering a more robust and versatile set of tools for remote administration, surveillance, and data extraction. Its Windows features have expanded dramatically with HVNC, crypto stealing, and advanced system management, while Android capabilities remain strong with consistent features from V3 and minor connection improvements. The addition of the ToolBox, Anti-Kill, and Service Manager in V4.2 makes it the most feature-rich version, catering to users seeking comprehensive control over target systems.

For more information or updates, refer to the official WH-Cyberspace resources.
