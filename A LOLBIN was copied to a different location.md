# Description
To evade detection, attackers may copy a LOLBIN executable to a different location.
# Attacker's Goals
Command execution via lolbins and detection avoidance via file rename.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
Check the destination path of the lolbin and try to see if it's benign.
