# TaskbarAcrylicOpacity
Windows registry to change taskbar opacity


#### Registry path
* `HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
#### Registry name
* `TaskbarAcrylicOpacity`
#### Registry value
* `0 to 255`


## Steps
* Taskbar transparency needs to be `ON`
* Create a new DWORD (32 bit) value named `TaskbarAcrylicOpacity`
* Edit value from `0 to 255` (transparent to solid)

## To see changes:
  * Restart `Windows Explorer` through Task Manager 
#### OR 
  * Restart computer
