ipconfig /release
ipconfig /renew
ipconfig /flushdns
netsh int ip reset
netsh winsock reset
netsh interface ipv4 reset
netsh interface ipv6 reset
netsh advfirewall reset
del /f /s /q %systemdrive%\*.tmp
del /f /s /q %systemdrive%\*._mp
del /f /s /q %systemdrive%\*.log
del /f /s /q %systemdrive%\*.gid
del /f /s /q %systemdrive%\*.chk
del /f /s /q %systemdrive%\*.old
del /f /s /q %systemdrive%\recycled\*.*
del /f /s /q %windir%\*.bak
del /f /s /q %windir%\prefetch\*.*
rd /s /q %windir%\temp & md %windir%\temp
del /f /q %userprofile%\cookies\*.*
del /f /s /q "%userprofile%\Local Settings\Temporary Internet Files\*.*"
del /f /s /q  "%userprofile%\Local Settings\Temp\*.*"
del /q /f /s "%USERPROFILE%\AppData\Local\Microsoft\Windows\Temporary Internet Files\*.*"
del /f /s /q  "%userprofile%\recent\*.*"
del /q /f /s "%USERPROFILE%\AppData\Local\Temp\Excel8.0\*.exd¡±
del /q /f /s "%USERPROFILE%\AppData\Roaming\Microsoft\Office\*.tmp"
del /f /s /q "%userprofile%\Local Settings\Temp\*.*"
del /s /q C:\Windows\temp\*
del /f /s /q "%userprofile%\recent\*.*"
del /q /f /s "%USERPROFILE%\AppData\Local\Temp\*.*"
rd /s /q %windir%\temp & md %windir%\temp
del /q/f/s %TEMP%\*
rd /s /q %windir%\temp & md %windir%\temp
del /f /q %userprofile%\cookies\*.*
del /f /q %userprofile%\recent\*.*
del /f /s /q "%userprofile%\Local Settings\Temporary Internet Files\*.*"
del /f /s /q "%userprofile%\Local Settings\Temp\*.*"
del /f /s /q "%userprofile%\recent\*.*"
del /s /f /q c:\windows\temp\*.*
rd /s /q c:\windows\temp
md c:\windows\temp
del /s /f /q C:\WINDOWS\Prefetch
del /s /f /q %temp%\*.*
md %temp%
deltree /y c:\windows\tempor~1
deltree /y c:\windows\temp
deltree /y c:\windows\tmp
deltree /y c:\windows\ff*.tmp
deltree /y c:\windows\history
deltree /y c:\windows\cookies
deltree /y c:\windows\recent
deltree /y c:\windows\spool\printers
del c:\WIN386.SWP
Del /S /F /Q %Windir%\Temp
Del /S /F /Q %temp%
echo of |clip
rd /q /s c:\$Recycle.Bin
rd /q /s d:\$Recycle.Bin
%SystemRoot%System32Cmd.exe /c Cleanmgr /sageset:16 & Cleanmgr /sagerun:16
del *.log /a /s /q /f
del /s /f /q C:\ProgramData\Tencent
del /s /f /q c:\Windows\Prefetch
del /s /f /q C:\aow_drv.log
echo Done , Team MATRIX HAX 
call %temp%\TEMPmessage.vbs
exit /b

