# QuickLock
One click system lock written in C#

No project files provided just a the one .cs file
Originally made in .net 5.0

### What does it do?
It locks your Windows computer when executed.

### Why?
When remoting into Windows systems you can't press Win + L in some circumstances.

### How does it do this?
By running 'rundll32.exe' with "user32.dll,LockWorkStation"
