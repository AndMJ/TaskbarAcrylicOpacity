<h1 align="center"> TaskbarAcrylicOpacity <br> Windows 10 registry</h1>


This is a way of changing Windows 10 taskbar opacity/make taskbar transparent without 3rd party software. This way you you don't need to add more processes running on Windows.
#### Registry path:
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced`
#### Registry name:
`TaskbarAcrylicOpacity`
#### Registry value:
`0 to 255`

<br>

## Screenshots
#### Before:
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/images/value255.png" width="1000px" align="center">

#### After:
<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/images/value0.png" width="1000px" align="center">




<br><br>

## Steps
1. Go on settings and make sure taskbar transparency effects are `On`, otherwise this will not work.

    <img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/images/transparency.png" width="325px" align="center">

<br>

2. Open Registry, press **WIN+R** and type `regedit`.

    <img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/images/winR.png" width="325px" align="center">

<br>

3. Copy paste the path [above](#registry-path).

    <img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/images/path.png" width="600px" align="center">

<br>

4. Inside this path, create a new **DWORD(32 bit) Value** named `TaskbarAcrylicOpacity`.

    <img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/images/DWORD32.png" width="325px" align="center">

<br>

5. Edit the DWORD and set **Value data** to `0`, if you want it to still have a litle `blur`, set the value to `10` or `20`, for example. Higher the value(max is `255`), higher the blur.

    <img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/images/editValue.png" width="325px" align="center">

<br>

## Changing back
Delete the registry word.

OR

Change the value to 255 (max blur).

OR

Turn taskbar transparency effects `Off`, making taskbar solid.

<br>

## To see changes:
Restart `Windows Explorer` through Task Manager.

<img src="https://github.com/AndMJ/TaskbarAcrylicOpacity/blob/main/images/restart.png" width="325px" align="center">

OR

Reboot/restart computer.
