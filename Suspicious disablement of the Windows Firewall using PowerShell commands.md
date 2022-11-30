# Description
The Windows Firewall has been disabled using PowerShell. Malware may turn it off to exfiltrate data and communicate with C2 servers.
# Attacker's Goals
An attacker may turn the firewall off to exfiltrate data and communicate with C2 servers.
# Investigative Actions
Check Windows event logs to see the PowerShell command or script that was executed.
Check whether the PowerShell command is benign or normal for the host and/or user performing it.
Investigate the endpoint to determine if it's a legitimate process that disabled the firewall.
