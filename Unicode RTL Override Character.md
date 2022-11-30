# Description
An attacker may use a special right-to-left (RTL) override character to trick users into executing malicious files that look like benign file types.
# Attacker's Goals
Trick users into executing malicious files by making their file types seem benign.
# Investigative Actions
Investigate the executed process causality group. There is no reason for benign files to contain the Unicode right-to-left override character in their name.
