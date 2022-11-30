# Description
The Windows Firewall has been disabled. Malware may turn it off to exfiltrate data and communicate with C2 servers.
# Attacker's Goals
An attacker may turn the firewall off to exfiltrate data and communicate with C2 servers.
# Investigative Actions
Check whether the command line executed is benign or normal for the host and/or user performing it.
Investigate the endpoint to determine if the process is legitimately disabling the firewall.
