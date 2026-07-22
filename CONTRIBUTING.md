# Contributing to OpenRoot

Thank you for wanting to lift the scaffold! Here's how to add your wisdom.

## Adding a Wisdom Entry

1. Open `wisdom/wisdom_corpus.json`.
2. Find the relevant section (e.g., `fusion_protocols`, `resilience_testing`).
3. Add a new entry with this template:
json { "id": "YOUR-ID-001", "source": "Experience/Scripture/SunTzu/etc", "concept": "Short concept name", "operational_translation": "What does this mean for code/systems?", "decision_rule": "if_then statement for automation", "eta_impact": "Did this improve efficiency? How?" }


4. Ensure the ID is unique.
5. Submit a Pull Request.

## Review Process

- Entries are reviewed for alignment with core principles.
- Approved entries are merged immediately.
- No gatekeeping. If it lifts the least, it belongs here.

## Code Contributions

- Keep functions atomic and small.
- Document every line.
- Test with real hardware (Termux + Shizuku preferred).

*"By this all men will know that you are My disciples, if you have love for one another." - John 13:35*
