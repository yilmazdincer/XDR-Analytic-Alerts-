# Description
A high amount of Kerberos principal unknown errors were generated on users in the last hour. This may be indicative of Kerberos user enumeration.
# Attacker's Goals
The attacker may attempt to gain an initial foothold in the domain by enumerating users and finding service accounts.
# Investigative Actions
Check whether any service principal names (SPNs) were not set correctly, as they will always return a principal unknown error.
