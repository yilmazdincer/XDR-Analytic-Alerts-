# Description
The endpoint, which is not an internal SMTP server, emailed an excessive amount of data from your network.
# Attacker's Goals
Transfer data they have stolen from your network to a location that is convenient and useful to him.
# Investigative Actions
Identify the process/user performing the data transfer to determine if the transfer is sanctioned.
Verify that the source is not a mail server.
Check if the target address represents a mail service that rarely used in the organization. If so, this might indicate on file exfiltration attempt.
