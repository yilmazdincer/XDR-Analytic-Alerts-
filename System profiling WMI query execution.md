# Description
Attackers or malware may use WMI queries to identify the system and evade execution in sandbox environments
# Attacker's Goals
Attacker or malware can use WMI queries to identify system components and prevent execution in sandbox \ virtualized environments to evade detection.
# Investigative Actions
Examine the process that executed the WMI query and verify that the process is from a trusted source.
Inspect the system for suspicious activity that is related to that process.
