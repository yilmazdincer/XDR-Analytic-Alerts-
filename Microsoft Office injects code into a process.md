# Description
An attacker may inject payloads into processes via Microsoft Office. While legitimate in certain cases, code injection can also be used in malicious ways.
# Attacker's Goals
An attacker attempts to gain code execution via a phishing document.
Attackers may inject code into processes to evade process-based defenses, as well as possibly elevate privileges.
# Investigative Actions
Check the source of the document (received by mail or loaded locally).
Check whether the injecting process is benign, and if this was a desired behavior as part of its normal execution flow.
