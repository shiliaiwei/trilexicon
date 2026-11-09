# MPTC Trilingual Digital Terminology Lexicon (SHA-256 Standard)

Production cryptographic registry for the official MPTC Digital Terminology Lexicon (2025).

All proprietary assets, lexicon datasets, prompts, workflows, and skill manifests are published strictly as one-way SHA-256 cryptographic digests:
- Data entries (`data/`): SHA-256 digested JSON structures and term mappings.
- Audio resources (`audio/`): SHA-256 cryptographic checksums for pre-recorded broadcast WAV audio.
- Visual assets (`images/`): SHA-256 cryptographic checksums for 48px rounded photographic canvas assets.
- Prompt specifications (`prompts/`): SHA-256 digested generation instructions.
- Skills and Rules (`.agents/skills/`, `.agents/rules/`): SHA-256 digested skill files (including all `SKILL.md` manifests) and governance specifications.
- Documentation & Config (`docs/`, `config/`): SHA-256 digested specifications and reference media checksums.

All original unhashed master resources remain securely on-premises and backed up to authenticated Google Drive.
