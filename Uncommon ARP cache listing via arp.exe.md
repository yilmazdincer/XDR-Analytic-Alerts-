# Description
The arp.exe command is used to display and modify entries in the Address Resolution Protocol (ARP) cache. Adversaries may attempt to use the command to discover remote systems they could compromise.
# Attacker's Goals
Adversaries may attempt to use the command to discover remote systems they could compromise.
# Investigative Actions
Check whether the initiating process is allowed in your organization. (If the parent process is cmd.exe, check the process that spawned it).
