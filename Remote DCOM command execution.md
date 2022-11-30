# Description
A remotely triggered DCOM initiated a command execution by a host that rarely executes processes using DCOM to other remote hosts.
# Attacker's Goals
Perform lateral movement to new hosts to expand the foothold within a network.
# Investigative Actions
Investigate the processes being spawned on the host for malicious activities.
Correlate the DCOM call from the source host and understand which software initiated it.
