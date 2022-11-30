# Description
Suspicious connection from a known TOR IP to an uncommon port
# Attacker's Goals
Attackers might use TOR IP combined with random ports.to hide C2 inbound communication from inside a host.
# Investigative Actions
Investigate the network configuration related to the participating port. Investigate processes that were listening to that port.
