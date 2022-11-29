# Description
Registering netsh helper DLLs is uncommon, and could be used by malware for persistence.
# Attacker's Goals
Command execution and persistence on the host.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
