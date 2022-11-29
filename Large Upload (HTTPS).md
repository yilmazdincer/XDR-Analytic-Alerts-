# Description
The endpoint transferred an excessive amount of data to an external site over HTTPS. The destination is not a popular upload site for endpoints on your network, and the endpoint performing the upload has not previously downloaded a large amount of data from the site. The upload is considered excessive based on comparison to baseline measurements of HTTPS data transfers on your network. An attacker may be exfiltrating data directly to the internet.
# Attacker's Goals
Transfer data she has stolen from your network to a location that is convenient and useful to her.
# Investigative Actions
Check if this alert has been falsely triggered by DNS load balancers. If an endpoint routinely uploads data to a site that uses load balancers, the transfer might ordinarily be split into multiple sessions and across multiple subdomains, which can cause the baseline measurement to be incorrect. In that situation, a routine upload that randomly places the bulk of the data in a single session to a single subdomain can look excessive to the Cortex XDR Analytics detector.
Check if the device performing the data transfer is a mobile phone performing a backup. Cortex XDR Analytics will not always measure the baseline properly for mobile devices, especially if the backups are performed infrequently and contain a great deal of data. If the data transfer is a mobile device running a backup, check to ensure that only appropriate data is included in the backup.
Identify the process/user performing the data transfer to determine if the transfer is sanctioned.
