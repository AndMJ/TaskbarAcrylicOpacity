# TaskbarAcrylicOpacity
Windows registry to change taskbar opacity
#### Registry path
* `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
#### Registry name
* `TaskbarAcrylicOpacity`
#### Registry value
* `0 to 255`

<br>

#### Before
<img id="img1" src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/value255.png" width="800px" align="center">

#### After
<img id="img2" src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/value0.png" width="800px" align="center">




<br><br>

## Steps
* Taskbar transparency needs to be `ON`
* Create a new DWORD (32 bit) value named `TaskbarAcrylicOpacity`
* Edit value from `0 to 255` (transparent to solid)

## To see changes:
  * Restart `Windows Explorer` through Task Manager 
#### OR 
  * Restart computer
