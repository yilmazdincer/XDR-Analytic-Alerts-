# Description
A dormant user account tried to authenticate to a service using a TGS, after having been unused for a year or more. This may indicate the account is misused by an attacker.
# Attacker's Goals
Use a compromised user account which has not been used in a long while, and are therefore less likely to be noticed.
# Investigative Actions
See whether the service authentication was successful.
Confirm that the activity is benign (e.g. the user returned from a long leave of absence).
Check whether you have issues with your Cloud Identity Engine failing to sync data from Active Directory.
