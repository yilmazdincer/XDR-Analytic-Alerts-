# Description
The endpoint connected to an excessive number of external SMTP servers. A spambot may be trying to send spam email using multiple SMTP servers. Spambots can cause your domain to be blacklisted, and can contain other malicious functionality. The same mechanism can also be used for exfiltration. Some VPN clients can also tunnel data over SMTP. Note: This detection model looks for SMTP connections to external servers, but the volume of traffic is not considered. A count is performed based on the number of domains being contacted, as well as the number of unresolved IP addresses.
# Attacker's Goals
The attacker uses the host as an SMTP client to send mails and hide their real origin.
# Investigative Actions
Verify that the source is not an SMTP server. If Cortex XDR Analytics has failed to identify the process as a valid SMTP server, this alert will be a false positive.
Verify that IP addresses are actually not being resolved by the non-SMTP process. If the process is performing DNS resolution with a DNS service outside your network, it is possible (depending on your network topology) that Cortex XDR Analytics will not observe that traffic. Because SMTP services typically use numerous IP addresses, this situation could cause a process to exceed a limit when it would otherwise fail to do so.
If the SMTP connection activity turns out to be the result of malicious file activity, search in the Triage page for other endpoints infected with the file.
