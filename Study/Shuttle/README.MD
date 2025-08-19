# Shuttle | Readme

Welcome! This repository houses the research, data, and calculations we have collected from trusted, publicly‑available sources such as NASA, SpaceX, and Google. All content pertains to shuttle design, launch vehicle performance, and related engineering analyses.

> Note – Each sub‑directory contains a README.md that explains its purpose and lists the files it holds.

🔎 What You’ll Find

| Category        | Description                                                                                          | Example Files                                   |
|-----------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------|
| **Design**      | High‑level layout, mass budget, subsystem block diagrams.                                            | `docs/design/architecture.md`                  |
| **Launch**      | Launch‑site checklists, ascent profile, flight‑software flow.                                        | `docs/launch/launch-timeline.md`               |
| **Propellant Data** | Chemical composition, densities, specific‑impulse values for LOX/LH₂, RP‑1, methane, etc.           | `data/propellants/lox_rp1.csv`                 |
| **Calculations**   | Re‑usable Jupyter notebooks or Python scripts that turn the raw data into actionable numbers.      | `calculations/fuel_mix/fuel_fraction.ipynb`    |
| **References**     | Bibliographic entries with permanent URLs/DOIs for every source used.                            | `docs/references/bibliography.bib`             |

All content is modular – new topics will be added as their own top‑level folder (e.g., `thermal/`, `avionics/`).

🤝 Contributing
We welcome external collaborators! Please observe the following workflow:

1. Fork the repository and create a new branch for your work.
2. Make changes only within the appropriate sub‑folder and update the local README.md for that folder.
3. Document any new sources in docs/references/ with a complete citation (title, author, URL/DOI, date accessed).
4. Run the linting script (provided in scripts/lint.sh) to ensure consistency.
5. Open a Pull Request with a clear description of what you added or modified.
> All contributions are subject to the Apache License 2.0 (see the License section). By submitting a PR you affirm that you have the right to license your contribution under these terms.

📜 License
The code, notebooks, and derived data in this repository are licensed under the Apache License, Version 2.0.
The raw reference documents (NASA PDFs, SpaceX press releases, etc.) are not owned by us; they remain under their original copyright.

📬 Contact
Lead Maintainer: Soon...
__________________________________
Issue Tracker: Use GitHub Issues for bugs, feature requests, or source‑verification questions.
