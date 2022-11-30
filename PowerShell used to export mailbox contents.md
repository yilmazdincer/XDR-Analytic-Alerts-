# Description
An attacker may use PowerShell to export the contents of a mailbox as part of the data staging before exfiltration
# Attacker's Goals
Export the content of a mailbox, preparing for data exfiltration.
# Investigative Actions
Examine the PowerShell command to identify which mailbox has been exported.
verify that this command was executed by a trusted source.
