# Description
Attackers may use the Image File Execution Options Registry key to launch their executable whenever the user attempts to execute a different one.
# Attacker's Goals
Adversaries may establish persistence and/or elevate privileges by executing malicious content triggered by Image File Execution Options debuggers.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
