# Description
A high amount of user accounts were locked out in a short time period. This may be the result of a brute-force or password spray attack.
# Attacker's Goals
An attacker may be attempting to gain unauthorized access to user accounts.
# Investigative Actions
Investigate the associated authentication attempts and login failures (e.g. 4625, 4776 events).
Check if any programs were cached with old credentials, resulting in account lockouts.
Find the computer responsible for the lockouts and verify if it exists on the domain.
Monitor services that may be running with a user's credentials.
