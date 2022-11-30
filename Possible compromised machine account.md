# Description
A Kerberos TGT for machine account has been used that does not match hostname
# Attacker's Goals
Gain special user Kerberos ticket to move laterally.
# Investigative Actions
Check the source host for possible credential dumping.
Check the delegated account credentials and if it has high privileges.
Check the ticket destination to verify whether it is a sensitive asset.
