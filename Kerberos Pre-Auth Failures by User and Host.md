# Description
The user account on this host failed Kerberos pre-authentications (TGT requests) an unusual number of times. This can indicate a Kerberos brute-force attack.
# Attacker's Goals
The attacker is attempting to guess the credentials for the user account.
# Investigative Actions
Verify that the password for the account has not been changed recently, without updating the user or the program using it.
Verify any later authentication success for the user accounts referenced by the alert, as these can indicate the attacker managed to guess the credentials.
