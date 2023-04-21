# Fixing the Alt+F4 hotkey issue on the A4Tech keyboard

On A4Tech keyboards, pressing the `Fn`+`Alt`+`F4` hotkey (or `Alt`+`F4` when `Fn` is locked by `Fn`+`Esc`) performs a search action instead of the standard window close action.

The [AutoHotkey](https://www.autohotkey.com/) script `a4tech-alt_f4.ahk` remaps the `Alt` and `Search` keys to `Alt`+`F4`.

The executable file [`a4tech-alt_f4.exe`](https://github.com/pb1161/a4tech-keyboard/releases/latest/) compiled from the AutoHotkey script can be placed in the Windows startup folder:
```
C:\Users\{username}\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup
```
Tested on A4Tech FBX50C keyboard and Microsoft Windows 10 22H2.
