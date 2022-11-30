# Description
The endpoint connected, or attempted to connect, to multiple privileged ports (lower than port 1024), which are infrequently used by other endpoints (i.e. destination ports that are normally used by many endpoints will not raise this alert). Attackers perform port scans for reconnaissance purposes, to find computers or servers that accept connections in these ports, and to find vulnerable services that can be exploited.
# Attacker's Goals
An attacker is determining which ports are open or closed on remote endpoints in an attempt to identify the endpoint operating system, firewall configuration, and exploitable services.
# Investigative Actions
New endpoints that use multiple ports can cause a false positive. Ensure that the endpoint is not new on the network, and is not hosting services such as FTP servers or domain controllers that are being contacted for the first time.
Check if the activity is a SYN-ACK scan. These might result in Cortex XDR Analytics detecting the scan as coming from the wrong direction, and could mean that Cortex XDR Analytics used the wrong baseline in triggering the alert.
Check for port map and/or X11 usage. These usually open multiple ports. If the protocol usage for the specific destination is sparse, Cortex XDR Analytics could raise a false alert.
