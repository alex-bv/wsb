# Windows Sandbox (.wsb)

This repository is used to store Windows Sandbox configuration(s).
The purpose of stored configuration(s) is to provide a privacy-focused yet not overloaded sandbox environment.

## How-to:
To use Windows Sandbox, one need to enable the Windows Sandbox Optional Feature by running PowerShell command:
```
Enable-WindowsOptionalFeature -FeatureName "Containers-DisposableClientVM" -All -Online
```
To use Windows Sandbox configuration, save it, then double-click on.

## Reference:
For more information, check:
- [Microsoft Windows Sandbox. Overview.](https://learn.microsoft.com/en-us/windows/security/application-security/application-isolation/windows-sandbox/windows-sandbox-overview)
- [Microsoft Windows Sandbox. Architecture.](https://learn.microsoft.com/en-us/windows/security/application-security/application-isolation/windows-sandbox/windows-sandbox-architecture)
- [Microsoft Windows Sandbox. Configuation.](https://learn.microsoft.com/en-us/windows/security/application-security/application-isolation/windows-sandbox/windows-sandbox-configure-using-wsb-file)
