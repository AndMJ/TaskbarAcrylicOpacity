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
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/value255.png" width="1000px" align="center">

#### After
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/value0.png" width="1000px" align="center">




<br><br>

## Steps
1. Taskbar transparency needs to be `ON`
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/transparency.png" width="325px" align="center">

<br>

2. Open Registry, (WIN+R) and type `regedit`
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/winR.png" width="325px" align="center">

<br>

3. Copy paste the path above
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/path.png" width="600px" align="center">

<br>

4. inside this path, create a new DWORD (32 bit) value named `TaskbarAcrylicOpacity`
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/DWORD32.png" width="325px" align="center">

<br>

5. Edit value from `0 to 255` (transparent to solid)
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/editValue.png" width="325px" align="center">

<br>

## Changing back
Delete the registry word 

OR

Change value to 255

<br>

## To see changes:
Restart `Windows Explorer` through Task Manager

<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/restart.png" width="325px" align="center">

OR

Restart computer
