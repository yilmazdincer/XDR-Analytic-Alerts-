# Description
Runonce.exe executes commands under the Registry key HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce, typically on computer boot and user logon events.
# Attacker's Goals
Command execution and persistence on the host.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
