# OpenXTalk macOS Native App Tools

This is an Extension Builder library that uses the
Foreign Function Interface (FFI) to wrap some of the features
of Apple Cocoa API's AppKit, thereby making them accessible to 
xTalk Scripts.

The goal is to make this library is to be as useful as possible 
for making built standalone macOS apps appear and behave as 
normal native mac apps could (or should).

Feel free to modify, branch, or include any part of it in your
own Builder projects. If you do so you must publish your source .lcb
in accordance to GPLv3 license so that others can learn from it.

Handler List:
- AppHide -	Hides the app sending it in the background and activates the next active app.	
- AppUnhide -	Unhides the app revealing any document windows that were hidden.	
- FullScreenAllowed	- Sets the mac native fullscreen attribute for a windowID passed to it.	
- GetFrontmostApplication	- Returns information about the frontmost application.
- IsFullScreenAllowed -	Returns the mac native Full Screen behavior state of stack's window.
- MiniaturizeAll - Minimize all document windows (does not effect on modal dialogs or modeless palette windows)
- PostUserNotification - Creates macOS notification center notes
- RequestUserAttention - When the app is in the background, RequestUserAttention calls for user attention by bouncy the App's icon in the Dock
- setAppToDarkMode - Assign the macOS native "Vibrant Dark" appearance style to all app windows
- setAppToLightMode - Assign the macOS native "Vibrant Light Mode" appearance style to all app windows
- SetDockTileBadge - Badge the App's Dock Icon with a small string of text.
- setWindowToDarkMode - Assign the macOS native "dark mode" window style to a stack's window
- setWindowToLightMode - Assign the macOS native "light mode" window style to a stack's window
- ToggleFullScreen - Toggle the mac native Full Screen state of a stack's window
