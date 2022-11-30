# Description
Attackers or malware may use WMI queries to list the users of a host, and potentially its owner.
# Attacker's Goals
Attacker or malware can use WMI queries to discover host users and enumerate a huge amount of information.
# Investigative Actions
Examine the process that executed the WMI query and verify that the process is from a trusted source.
Inspect the system for suspicious activity that is related to that process.
