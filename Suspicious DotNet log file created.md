# Description
Payloads that use the DotNet framework may generate suspicious Microsoft DotNet log files.
# Attacker's Goals
Run/Inject DotNet code in the context of signed process.
# Investigative Actions
Verify if the actor process is using DotNet in a valid way.
Check if a new application was recently installed on the host at the time of the alert.
