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
<img id="img1" src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/transparency.png" width="600px" align="center">

3. Create a new DWORD (32 bit) value named `TaskbarAcrylicOpacity`
<img id="img1" src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/DWORD32.png" width="600px" align="center">

4. Edit value from `0 to 255` (transparent to solid)
<img id="img1" src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/editValue.png" width="600px" align="center">

<br>

## Changing back
Delete the registry word 

OR

Change value to 255

<br>

## To see changes:
Restart `Windows Explorer` through Task Manager
<img id="img1" src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/restart.png" width="600px" align="center">

OR

Restart computer
