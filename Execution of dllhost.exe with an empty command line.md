# Description
The process dllhost.exe was executed with an empty command line. This behavior is suspicious, and may be caused by a malicious actor using 'Image File Execution Options' in the registry to evade detection.
# Attacker's Goals
Evade detection when running suspicious commands.
# Investigative Actions
Check if an entry for dllhost.exe was added in the registry, under "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options".
