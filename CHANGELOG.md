# Changelog

All notable changes to the OCTP specification are documented here.

Format: [version] — date — description

---

## [0.1.0] — 2026-02-26

Initial community draft of the Open Contribution Trust Protocol specification.

### Added
- Core envelope schema with four sections: header, provenance, verification, integrity
- ProvenanceMethod enum: human_only, ai_assisted_human_reviewed, ai_generated_human_reviewed, ai_generated_unreviewed
- ReviewLevel enum: none, glance, moderate_review, substantial_modification, complete_rewrite
- Cryptographic signing model using ES256
- Optional context section for free-form contributor notes
- JSON Schema for envelope validation
- Minimal and full example envelopes
- RFC process and template