# Description
Multiple user accounts authenticated to a host via NTLMv1 or LM authentication for the first time in the past 30 days. This may be a result of an NTLM downgrade attack A downgrade attack may force the client to authenticate with a weaker hash/protocol (such as NTLMv1 or even LM) instead of NTLMv2.
# Attacker's Goals
The attacker attempts to gain access to the accounts.
# Investigative Actions
Audit all login events with a weaker protocol and review any anomalous usage.
Investigate the mentioned host for additional suspicious activity.
