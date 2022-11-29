# Description
AutoIT scripts have legitimate uses, but are often abused by malware to execute in a signed process context
# Attacker's Goals
Gain code execution on the host and evade security controls.
# Investigative Actions
Check whether the command line executed is benign or normal for the host and/or user performing it.
Check whether the user in the command line is an administrator or other sensitive account.
