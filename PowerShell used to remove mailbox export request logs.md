# Description
An attacker may use PowerShell to remove evidence of an export request for a mailbox as part of the clean-up stage.
# Attacker's Goals
Remove evidence for mailbox export commands.
# Investigative Actions
Examine the PowerShell command to identify which mailbox has been compromised.
Investigate the host that executes the command for potential further exploitation.
