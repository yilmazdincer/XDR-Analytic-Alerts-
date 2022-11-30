# Description
A user account was modified with delegation to a service
# Attacker's Goals
An attacker may attempt to control an Active Directory environment.
# Investigative Actions
Verify this action with the user who performed the change.
Check if the account modified is a service account.
Follow actions by the user, including TGT and TGS requests.
Monitor for anomalous Kerberos activity.
