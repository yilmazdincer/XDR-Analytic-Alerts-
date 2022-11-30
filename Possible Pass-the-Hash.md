# Description
An account was successfully logged on to with new credentials. This login type is rare and may be an attacker's attempt to pass-the-hash and move laterally within a network.
# Attacker's Goals
An attacker is attempting to steal credentials and move laterally within a network.
# Investigative Actions
Audit all login events and review for discrepancies.
Look for LSASS process access, an indication of an attacker attempting to obtain password hashes.
Check for the RunAs command with the /netonly option.
