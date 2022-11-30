# Description
A locked-out user account (event ID 4725 or 4740) was used in a Kerberos TGT pre-authentication attempt.
# Attacker's Goals
Authenticate using the principal in the TGT, not knowing that it has been revoked.
# Investigative Actions
Check whether you have issues with your Cloud Identity Engine failing to sync data from Active Directory.
Check whether the attempt to use the principals (user accounts) specified in the alert are legitimate. For example, a user or a script that was not updated that the account has been revoked.
The lockout can be temporary, for example, in the case of too many login attempts, and may not be visible after the account was released.
Search for Windows Event Log 4740 to ascertain whether the account was locked out during the time of the alert.
