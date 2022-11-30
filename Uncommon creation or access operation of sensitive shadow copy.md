# Description
An uncommon creation or access of a sensitive Shadow Copy volume path
# Attacker's Goals
Attackers may try to copy sensitive data or dump OS credentials from the host file system by using Shadow Copy volume utilities.
# Investigative Actions
Verify if the shadow copy operation is part of an IT activity.
Look for other hosts performing the same shadow copy event with similar causality process behavior.
Inspect the causality process and its characteristics as they appear on other hosts.
