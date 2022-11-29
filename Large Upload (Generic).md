# Description
The endpoint transferred large amounts of data to an external site using a different protocol from HTTP/s, FTP, or SMTP. (A specific detector is used for each of those protocols.) Cortex XDR Analytics assumes that data transfers out of your network are ordinarily performed using one of those three services, so it expects that data transfers over all other ports to be low. For the same reason, Cortex XDR Analytics also assumes endpoint traffic towards a specific destination should be about the same over long periods of time. An attacker may be exfiltrating data directly to the internet.
# Attacker's Goals
Transfer data he has stolen from your network to a location that is convenient and useful to him.
# Investigative Actions
Check if the traffic is related to SSH activity, it can trigger this alert. It is possible that someone on your network is legitimately engaged in SSH activity.
Check if the traffic is to/from a misconfigured network.
Check if the traffic is to a new external service or server that has recently been adopted for use by an organization in your enterprise.
Identify the process/user performing the data transfer to determine if the transfer is sanctioned.
