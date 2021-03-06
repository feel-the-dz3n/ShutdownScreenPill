# Shutdown Screen Pill [![Build status](https://ci.appveyor.com/api/projects/status/lf0xepyu9l7293qr?svg=true)](https://ci.appveyor.com/project/feel-the-dz3n/shutdownscreenpill)
This program enables or disables "It's not safe to shutdown your computer" screen. It uses some Microsoft hotfix introduced for Server 2003. It adds a registry value (``HKLM\Software\Policies\Microsoft\Windows NT``) and calls ``ExitWindowsEx(EWX_SHUTDOWN, ...)``.

Supported OS versions:
 - Windows Server 2003 (updated)
 - Windows Vista
 - Windows 7
 - Windows 8
 - Windows 8.1
 - Windows 10

Download [artifacts at AppVeyor](https://ci.appveyor.com/project/feel-the-dz3n/shutdownscreenpill) page or go to [releases tab](https://github.com/feel-the-dz3n/ShutdownScreenPill/releases).
