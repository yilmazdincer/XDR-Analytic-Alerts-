# Description
A signed process connected to an external domain that, on a global level, it usually doesn't connect to
# Attacker's Goals
Attackers may use various methods to execute code from a context of a signed process to avoid detection.
# Investigative Actions
Check the destination domain reputation.
Check if the actor process loaded a suspicious dll before the alert.
Check if the actor process was injected before the alert.
Check if the process execution and connections are legitimate.
