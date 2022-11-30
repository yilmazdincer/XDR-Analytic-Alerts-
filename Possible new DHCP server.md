# Description
A DHCP response was sent from an unknown DHCP server. Attackers may send a DHCP response to a host in his LAN to inject a DNS server, route or WPAD server.
# Attacker's Goals
The attacker is attempting a man-in-the-middle NTLM relay attack to intercept authentication attempts and move laterally within an environment.
# Investigative Actions
Check if the source agent is a legitimate DHCP server.
Check if the attacked host send DNS queries to an unusual IP.
Check if the attacked host send WPAD HTTP/S requests to an unusual host.
