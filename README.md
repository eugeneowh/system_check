tested on windows 10 (only)

Checks installed applications with `wmic product get Name, Version, InstallLocation`
Checks scheduled tasks with `schtasks /query /fo LIST /v`
Checks each installed applications with `icacls "' + appPath.slice(0, -1) + '"')` << still very buggy, to fix soon?
