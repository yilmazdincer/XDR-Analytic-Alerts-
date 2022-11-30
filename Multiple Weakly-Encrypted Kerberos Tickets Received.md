# Description
A user accessed a number of services associated with user accounts in the 10 minutes leading to the alert, generating a number of weakly encrypted Kerberos TGS (ticket granting service) tickets that is significantly larger than the number of weakly encrypted TGS tickets received by that user in the 30 days leading to the alert. Services associated with user accounts are a common target for Kerberoasting due to default weak encryption.
# Attacker's Goals
Crack account credentials by obtaining easy-to-crack Kerberos tickets.
# Investigative Actions
Check who used the host at the time of the alert, to rule out a benign service or tool accessing those services.
