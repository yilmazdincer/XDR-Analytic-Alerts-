# Description
We observed two different hosts sending TGS using the same TGT. This may indicate a TGT was stolen and passed to another host.
# Attacker's Goals
Lateral movement using stolen user-account credentials.
# Investigative Actions
Check if the mentioned hosts are not the same, and investigate if the ticket was stolen from one of them.
