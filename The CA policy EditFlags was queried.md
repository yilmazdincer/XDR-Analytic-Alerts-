# Description
The CA policy EditFlags was queried
# Attacker's Goals
Querying this registry value can indicate an attacker is looking for an enabled EDITF_ATTRIBUTESUBJECTALTNAME2 flag.
When this flag is enabled, it allows users to request certificates with a Subject Alternate Name(SAN).
This can allow an attacker to obtain a certificate with higher privileges.
# Investigative Actions
Check if the action was allowed by the user.
Monitor certificate enrollments with Subject Alternate Names.
Check for unusual high privilege users certificate authentications.
