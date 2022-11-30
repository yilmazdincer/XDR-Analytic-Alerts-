# Description
An abnormal process accessed the PowerShell console history file. This may be a sign of malicious PowerShell execution without directly invoking the powershell.exe binary.
# Attacker's Goals
An attacker is attempting to run PowerShell without powershell.exe to evade detection.
# Investigative Actions
Investigate the process and command line executed and whether it's benign or normal for this host.
