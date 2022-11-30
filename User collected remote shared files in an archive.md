# Description
Multiple files from remote shares were archived in a local file. This may indicate collection of data and staging before exfiltration
# Attacker's Goals
Collect data and stage it on an endpoint in the organization.
# Investigative Actions
Check whether the process that created the archive creates network connections as well.
Check whether other users in the organization used the same process for remote archive file activity.
