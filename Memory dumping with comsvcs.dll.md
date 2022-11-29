# Description
A process memory dump was performed using comsvcs.dll MiniDump. This method is commonly used by attackers to dump Lsass.exe (Local Security Authority Subsystem Service) process memory to a file, so they could later extract credentials from the memory dump.
# Attacker's Goals
Attackers may attempt to dump the memory of sensitive processes.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
