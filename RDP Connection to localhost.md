# Description
RDP connection to localhost can be used for privilege escalation by leveraging Windows Accessibility Features.
# Attacker's Goals
An attacker may initiate RDP tunneling for a more convenient and stable interface.
# Investigative Actions
Identify the process/user performing RDP and check that it is authorized.
Check whether the initiating process also connects to an external host.
