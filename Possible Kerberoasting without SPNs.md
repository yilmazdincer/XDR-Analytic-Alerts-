# Description
A user specifically requested weak and deprecated encryption in a Kerberos TGS request. This provides easy-to-crack hashes, and is typically a sign of a Kerberoasting attack. The requested service was specified by using a suspicious SPN type, which is often used by Kerberoasting tools to request by SAN instead of SPN.
# Attacker's Goals
Crack service account credentials by obtaining an easy-to-crack Kerberos ticket.
# Investigative Actions
Check who used the host at the time of the alert, to rule out a benign service or tool requesting weak Kerberos encryption.
