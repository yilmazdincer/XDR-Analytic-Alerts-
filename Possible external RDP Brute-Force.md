# Description
Multiple failed remote logins originated from an external ip with at least one successful login. This may indicate a successful brute-force attack.
# Attacker's Goals
The attacker attempts to gain access to the accounts.
# Investigative Actions
If the source IP is an internal IP, adjust network ip ranges.
Identify the user performing RDP and check that it is authorized.
Check whether this IP has a malicious reputation.
Reset the user's password.
Follow further actions done by the user.
