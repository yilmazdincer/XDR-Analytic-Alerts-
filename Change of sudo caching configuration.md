# Description
Change of sudo caching configuration possibly aimed to allow privilege escalation
# Attacker's Goals
Attackers may use the sudoers file to elevate privileges.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
