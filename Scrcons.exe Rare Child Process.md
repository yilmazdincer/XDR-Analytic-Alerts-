# Description
The Windows Management Instrumentation (WMI) standard event consumer scrcons.exe executed a rare VBScript or PowerShell script. Executing a rare script can be an indication of local or remote code execution abuse by an attacker.
# Attacker's Goals
The attacker is trying to gain Persistence via WMI script registration.
# Investigative Actions
Review registered WMI ActiveScriptEventConsumer.
