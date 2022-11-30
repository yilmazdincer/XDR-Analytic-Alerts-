# Description
Runonce.exe executes commands under the Registry key HKLM\SOFTWARE\Microsoft\Windows\CurrentVersion\RunOnce, typically on computer boot and user login events.
# Attacker's Goals
An attacker is trying to perform an action on the system at a later point, achieving persistence.
# Investigative Actions
Investigate the endpoint to determine if it's a legitimate process that is supposed to use RunOnce in its operation.
