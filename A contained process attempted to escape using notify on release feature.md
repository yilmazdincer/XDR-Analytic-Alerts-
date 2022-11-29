# Description
A contained process attempted to escape the host by leveraging Dockers notify on release feature. The calling process modified relevant files that might trigger a command on the host
# Attacker's Goals
Execute arbitrary commands on the host and gain larger foothold.
# Investigative Actions
Check which commands were executed on the host afterwards.
Look for the root cause of the execution within the container.
Examine the release_agent script content on the container.
