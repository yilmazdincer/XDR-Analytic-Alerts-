# Description
A process wrote a known networking driver with network sniffing capabilities to disk, attackers can use it to sniff passwords and other credentials from the network.
# Attacker's Goals
Read raw network data over promiscuous mode, this can allow the attacker the capabilities to sniff passwords and other credentials from the organization network, in other cases also interfere with the network.
# Investigative Actions
Verify if the process is known for the IT/ User.
Check if the driver installed recently, if it was installed with sc.exe this action can be malicious (check who ran sc.exe to verify that).
