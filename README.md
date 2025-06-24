ch `Txxxx/` folder aligns with a [MITRE ATT&CK®](https://attack.mitre.org/) technique (e.g., `T1008 - Fallback Channels`).

## 📚 Purpose

These tests serve to:
- Simulate realistic adversary techniques for purple teaming
- Validate and tune detections in platforms like Microsoft Sentinel
- Encourage learning through hands-on scripting and modular design

## 🛠 Getting Started

To run a test:

1. Clone this repository
2. Ensure [Atomic Red Team](https://github.com/redcanaryco/atomic-red-team) and `Invoke-AtomicTest` are installed
3. Run a custom test locally:
   ```powershell
   Invoke-AtomicTest Txxxx -PathToAtomicsFolder "Path\To\Custom_RedTeam_Scripts\Txxxx" -ShowDetails

✍️ Authorship & Intent

Every test is written with clarity, ethics, and realism in mind—crafted for defenders, educators, and explorers of cyber capability. Inspired by adversaries, grounded in empathy.
If you build upon these, keep the spirit of transparency, curiosity, and community alive.

© 2025 Chris Carucci (a.k.a. GITSGHOST) 🛰 “Even in fallback, we signal.”
