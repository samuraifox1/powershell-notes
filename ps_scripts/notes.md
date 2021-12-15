# Notes

- Before Windows PowerShell 5.0
- `Windows PowerShell 5.1` : Built on top of `.NET Framework v4.5`
- `PowerShell 6.0` : OpenSource Powershell on top of `.NET Core 2.0`. Moving from the .NET Framework to .NET Core allowed PowerShell 
- to become a cross-platform solution. PowerShell runs on Windows, macOS, and Linux
- `PowerShell 7.0` : Built on `.NET Core 3.1`
- `PowerShell 7.2` : will be uuild on `.NET 6.0`

# Note: Windows PowerShell =!= PowerShell: 
The differences are most notable in the availability and behavior of PowerShell cmdlets between Windows and 
non-Windows platforms and the changes that stem from the differences between the .NET Framework and .NET Core.

## Key Points:
* PowerShell on Linux and macOS uses .NET Core
* .NET Core is a subset of the full .NET Framework  of Microsoft Windows OS
* Scripts that run on Windows may not run on non-Windows platforms. 
* Therefore, always try to write cross-platform PowerShell as fas  as possible. 
