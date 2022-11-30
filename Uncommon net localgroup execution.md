# Description
The 'net localgroup' command is used to add, display, or modify groups local to the host. Adversaries may attempt to use the command to find host groups and permissions settings or modify local group memberships.
# Attacker's Goals
Attackers can attempt to use the command to find endpoint groups and permissions settings or modify local group memberships.
# Investigative Actions
Check if the queried group is a sensitive one (e.g. administrators).
Check whether the initiating process has executed additional discovery commands.
