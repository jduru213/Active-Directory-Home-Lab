# Active-Directory-Home-Lab
## Splunk Inputs.conf File

[WinEventLog://Application]

index = end-users

disabled = false


[WinEventLog://Security]

index = end-users

disabled = false


[WinEventLog://System]

index = end-users

disabled = false


[WinEventLog://Microsoft-Windows-Sysmon/Operational]

index = end-users

disabled = false

renderXml = true

source = XmlWinEventLog:Microsoft-Windows-Sysmon/Operational
