# Description
A user added SID history to an account. This may be indicative of a user's migration between domains or a SID injection attack.
# Attacker's Goals
Adversaries may use SID history to escalate privileges and bypass access controls.
# Investigative Actions
Verify if migration between domains was involved.
Search for suspicious actions by the user, such as forged Kerberos tickets.
