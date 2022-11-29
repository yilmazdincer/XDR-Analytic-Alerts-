# Description
A signed process injected to another process that, on a global level, it usually doesn't inject into
# Attacker's Goals
Attackers may use various methods to execute code from a context of a signed process to avoid detection.
# Investigative Actions
Check if the actor process loaded a suspicious dll before the alert.
Check if the actor process was injected before the alert.
Check if the process execution and connections are legitimate.
