# Description
A non-PowerShell process loaded a known PowerShell module. This image load may be an indication of PowerShell execution without directly invoking the PowerShell.exe binary.
# Attacker's Goals
An attacker is attempting to run PowerShell without PowerShell.exe to evade detection.
# Investigative Actions
Investigate the process and command line executed and whether it's benign or normal for this host.
