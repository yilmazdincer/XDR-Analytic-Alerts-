# Description
The endpoint has failed connections to other endpoints that have been inactive for more than 24 hours, or that Cortex XDR Analytics has never seen on the network. The endpoint has made an abnormally large number of these failed connections and/or is attempting to connect to an abnormal mixture of missing or inactive endpoints.
Your network might contain legitimate scanners that could cause a false positive for this alert. Cortex XDR Analytics attempts to filter these out by checking if a scanner has been active for a long consecutive period of time. Consequently, if this alert is seen, it represents new activity on your network.
An attacker may be trying to move laterally, or to scan different parts of the network to look for other endpoints that expose a specific service. Worms also perform a similar activity to automatically infect additional hosts in the network.
# Attacker's Goals
An attacker does not know your network and is exploring it for new or unknown subnets.
# Investigative Actions
Validate that the source is not a sanctioned port scanner.
Check for suspicious artifacts in the endpoint profile.
deneme1234
