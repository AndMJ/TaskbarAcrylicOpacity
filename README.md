# TaskbarAcrylicOpacity
Windows 10 registry.

This is a way of changing Windows 10 taskbar opacity/make taskbar transparent without 3rd party software.
#### Registry path
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
#### Registry name
`TaskbarAcrylicOpacity`
#### Registry value
`0 to 255`

<br>

## Screenshots
#### Before
<img id="img1" src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/value255.png" width="800px" align="center">

#### After
<img id="img2" src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/value0.png" width="800px" align="center">




<br><br>

## Steps
1. Taskbar transparency needs to be `ON`
2. Create a new DWORD (32 bit) value named `TaskbarAcrylicOpacity`
3. Edit value from `0 to 255` (transparent to solid)

<br><br>

## To see changes:
  * Restart `Windows Explorer` through Task Manager 
#### OR 
  * Restart computer
