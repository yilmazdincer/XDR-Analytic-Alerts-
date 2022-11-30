# Description
The endpoint performed DNS lookups to an excessively large number of apparently random root domain names. This alert might be symptomatic of malware that is trying to connect to its command and control (C2) servers.
The attacker's C2 server runs on one or more domains that can eventually be identified and blacklisted. To avoid this, malware will sometimes use Domain Generation Algorithms (DGA) that produce many unique, random-looking domain names every day. Because only a few of these domains are ever registered, the installed malware must blindly try to access each generated domain name in an effort to locate an active one, which may also trigger the Failed DNS alert.
# Attacker's Goals
Communicate with malware running on your network for controlling malware activities, performing software updates on the malware, or for taking inventory of infected machines.
# Investigative Actions
Make sure your DNS servers are not misconfigured and are responsive. This detector assumes that most DNS lookups succeed, and will only raise an alert when it sees many failed lookups. Misconfigured or unresponsive DNS servers can result in a false positive.
Make sure you do not have external domains configured as internal domains. This can result in clients attempting to (for example) resolve google.com.local first, before resolving google.com. This can result in a false positive for this alert.
Ensure that the endpoint is configured properly for your DNS servers. Make sure it is configured to use the correct DNS IP address, and that the IP address is not for a firewalled DNS server. Misconfigured DNS clients can result in many failed lookups, which will result in a false positive for this alert.
Make sure the endpoint is not a DNS, Proxy, NAT or VPN gateway server. If these have been misdetected by Cortex XDR Analytics, then their ordinary operations can trigger this alert.
