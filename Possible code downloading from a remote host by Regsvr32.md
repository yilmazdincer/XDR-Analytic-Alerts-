# Description
Regsvr32 may be used to fetch arbitrary code from a remote host and execute it without dropping the payload onto the disk. Known to be used for malicious purposes.
# Attacker's Goals
Gain code execution on the host and evade security controls.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
