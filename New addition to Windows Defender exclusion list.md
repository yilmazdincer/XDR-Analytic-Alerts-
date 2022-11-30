# Description
Windows Defender keeps the exclusion list in the Registry, and any addition to it will cause it to ignore a process.
# Attacker's Goals
Gain code execution on the host and evade security controls.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
