# Description
The endpoint transferred an excessively large amounts of data to a single destination over FTP.
# Attacker's Goals
Exfiltrate stolen data from the victim network to an attacker's controllable resource.
# Investigative Actions
Verify that the source is not an FTP server. If Cortex XDR Analytics has failed to identify the entity as a valid FTP server, this alert is likely to be a false positive.
Identify the entity performing the data transfer to determine if the transfer is sanctioned.
Use Pathfinder to interrogate the endpoint for suspicious artifacts that are using endpoint processes or loaded modules.
