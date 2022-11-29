# Description
Attackers may modify ld.so.preload to load their malicious code into every dynamically linked process.
# Attacker's Goals
Gain persistence and inject itself into every program on the system.
# Investigative Actions
Check whether the executing process is benign, and if this was a desired behavior as part of its normal execution flow.
Download the /etc/ld.so.preload file from the host and see if and what libraries are specified there.
Download any library specified and see if it's benign.
