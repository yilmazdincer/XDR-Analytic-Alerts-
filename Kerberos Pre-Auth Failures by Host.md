# Description
The endpoint failed an unusual number of Kerberos pre-authentications (TGT requests) from at least three users when compared to its baseline. This can indicate a password-spraying attack.
# Attacker's Goals
The attacker is attempting to gain an initial foothold in the domain using a list of valid users and a guessed password.
# Investigative Actions
Verify whether the host that generated the alert is normally used by many users (for example, a terminal server).
Verify any later authentication success for the user accounts referenced by the alert, as these can indicate the attacker managed to guess the credentials.
