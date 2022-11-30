# Description
A suspicious process changed or created the ~/.ssh/authorized_keys file.
# Attacker's Goals
Adversaries use this to ensure that they are possessing the corresponding private key and may log in as an existing user via SSH.
# Investigative Actions
Check the file modification, try to understand the impact of the related processes and network connections.
