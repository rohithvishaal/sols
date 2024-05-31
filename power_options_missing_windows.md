# Solution for shutdown option missing in start menu in Windows 10/11
- Open registry editor
- Navigate to `Computer\HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer`
- Add or modify the key `NoClose`and set the value to 0 and restart the system
