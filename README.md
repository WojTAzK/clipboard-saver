# Clipboard-Saver ![Clipboard-Saver-icon](https://user-images.githubusercontent.com/48928433/175969781-007d5cc7-6fd1-4208-b3f0-82469458268e.png)

<br>

[Releases](https://github.com/WojTAzK/clipboard-saver/releases) - 
version info: <br>
|File name|Content|Direct link|
|---|---|---|
|`Clipboard-Saver-EXE.zip` | .exe | [Download .exe](https://github.com/WojTAzK/clipboard-saver/releases/download/v1.0.1/Clipboard-Saver-EXE.zip)|
|`Clipboard-Saver-PS1.zip` | .ps1 | [Download .ps1](https://github.com/WojTAzK/clipboard-saver/releases/download/v1.0.1/Clipboard-Saver-PS1.zip)|
|`Clipboard-Saver-EXE-PS1.zip` | .exe and .ps1 | [Download .exe & .ps1](https://github.com/WojTAzK/clipboard-saver/releases/download/v1.0.1/Clipboard-Saver-EXE-PS1.zip)|

<hr>

Note: Copied file/s will be saved as text in format: `C:\Path\To\File.exe`

<hr>

.Exe was generated from .ps1 script with [ps2exe](https://github.com/MScholtes/PS2EXE)

<br>

You can do that yourself with PowerShell <br>
e.g.: <br>
```diff
ps2exe .\Clipboard-Saver.ps1
```
(you need to have ps2exe installed) [how to install](https://github.com/MScholtes/PS2EXE#installation)

<hr>

I used this command: <br>
```diff
ps2exe .\Clipboard-Saver.ps1 -noConsole -copyright "Wojciech Kowal" -version "1.0.0" -iconFile .\Clipboard-Saver-icon.ico
```

<hr>

You can get the Clipboard-Saver icon [here](https://flaticons.net/custom.php?i=w5QIeDTq6WkDszIWIxI4qt7Z5ePi6)

<hr>

[How to assign keyboard shortcut](https://github.com/WojTAzK/clipboard-saver/wiki/Assign-keyboard-shortcut)
