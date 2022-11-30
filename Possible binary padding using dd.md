# Description
A suspicious dd command ran and added data to a binary. This may indicate binary padding to change the hash of a file.
# Attacker's Goals
An adversary may use binary padding to avoid hash-based blacklists and static antivirus signatures.
# Investigative Actions
Check the padded file and try to understand the impact of padding this specific binary.
