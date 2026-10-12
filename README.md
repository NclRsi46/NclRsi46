# Nicolas Rossi

Cybersecurity student at Pace University (B.S., graduating Dec 2027), focused on digital forensics, incident response, and detection. I'm looking for a Summer 2027 internship in DFIR or detection.

## Projects

**[phishing-detection-ml](https://github.com/NclRsi46/phishing-detection-ml)** is a phishing domain classifier in Python and scikit-learn. The first version reported 99.46% accuracy, and that number was a data leak: the benign rows were bare homepages and the phishing rows were full links, so the model learned that a path meant phishing. I rebuilt it to score domain names only, grouped the train/test split by phishing campaign, added a time-based split, and report recall at fixed false positive rates instead of accuracy. A character n-gram model now catches 27.7% of phishing domains at a 1% false positive rate (mean of 10 splits), and an audit traces much of that to abused TLDs and kit wording reused across campaigns. The README covers the leak, the fixes, and the limitations.

## Work

**Corveonic**, Co-Founder & Security Lead (Jul 2026 to present). We run an AI and workflow automation consultancy. On the security side I built an append-only audit log enforced by a database trigger and hardened client portal access with forced row-level security and short-lived scoped JWTs. I also built a GitHub Actions gate, using gitleaks and a custom Python linter, that blocks pull requests containing secrets or PII.

**Pace University ITS**, Student Assistant (Nov 2025 to present). Walk-in support for 106 workstations across the Tech Zone and two computer classrooms. With my supervisor, I collected forensic artifacts with KAPE from a potentially compromised lab workstation and escalated the collection to Pace's security team.

## Competitions

- **NSA Codebreaker Challenge** (2026): Tasks 1 to 3 solved so far, covering log analysis, memory forensics with Volatility 3, and reversing a binary with Ghidra.
- **CPTC** (2026): advanced past the national qualifier. Regionals are on October 24.
- **NECCDC** (2026): advanced to Regionals with Pace. I managed Teleport for privileged access control and reviewed its audit logs and session recordings for signs of red team activity.
- **NCL** (Fall 2025): 639th of 7,876 nationally, top 8% in the individual game and 1st at Pace.

Codebreaker write-ups will go up here after the challenge closes.

[Site](https://nclrsi46.github.io) · [LinkedIn](https://www.linkedin.com/in/nicolas-rossi2228462333) · [Email](mailto:nicolas.g.rossi@pace.edu)
