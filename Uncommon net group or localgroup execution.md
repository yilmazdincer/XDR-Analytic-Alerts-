# Description
The 'net' group or localgroup command is used to add, display, or modify local or domain-level groups. Adversaries may attempt to use the command to find local or domain-level groups and permissions settings or modify local or domain-level group memberships.
# Attacker's Goals
Attackers may attempt to use the command to find local or domain-level groups permissions settings or modify local or domain-level memberships.
# Investigative Actions
Check if the queried group is a sensitive one (e.g. administrators).
Check whether the initiating process has executed additional discovery commands.
