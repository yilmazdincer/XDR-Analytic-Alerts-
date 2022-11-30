# Description
A host that rarely initiates WMI to other remote hosts triggered a remote process execution by using WMI RPC.
# Attacker's Goals
Perform lateral movement to new hosts to expand the foothold within a network.
# Investigative Actions
Investigate the processes being spawned on the host for malicious activities.
Correlate the RPC call from the source host and understand which process or software initiated it.
