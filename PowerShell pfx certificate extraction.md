# Description
PowerShell was used to extract a pfx certificate file.
# Attacker's Goals
Attackers may export certificates to .pfx files to use them for authentication, persistence or NTLM extraction.
# Investigative Actions
Check if the pfx creation is legitimate for the user (Testing, IT, etc.).
Follow further actions done by the user (ex. authentication using certificates).
