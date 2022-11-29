# Description
Certutil was used to parse a pfx certificate file.
# Attacker's Goals
Attackers want to check pfx details. If details suffice, the correct certificate can be used for authentication, persistence or NTLM extraction.
# Investigative Actions
Check if the pfx parsing is legitimate for the user (Testing, IT, etc.).
Follow further actions done by the user (ex. authentication using certificates).
