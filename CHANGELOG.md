# Changelog

## [v0.3.0](https://github.com/runapi-ai/elevenlabs/releases/tag/v0.3.0) - 2026-10-15

### Removed
- Remove retired model choices from creation metadata and document historical task lookup.
  Migration: Retired models return HTTP 410 for new requests. Query existing task IDs with the original task endpoint; no automatic replacement is applied.
- Remove retired audio-isolation from the selectable ElevenLabs skill variants.
  Migration: Do not submit new audio-isolation tasks; new requests return HTTP 410. Query existing task IDs through the task-status API. Other ElevenLabs variants remain available.


## [v0.2.9](https://github.com/runapi-ai/elevenlabs/releases/tag/v0.2.9) - 2026-08-12

### Changed
- Generate the elevenlabs skill from the shared RunAPI recipe with contract-discovered request rules and task behavior, direct local media inputs, complete result verification, and bounded recovery.


## [v0.2.8](https://github.com/runapi-ai/elevenlabs/releases/tag/v0.2.8) - 2026-08-10

### Changed
- Complete marketplace distribution for the RunAPI ElevenLabs skill.


## [v0.2.7](https://github.com/runapi-ai/elevenlabs/releases/tag/v0.2.7) - 2026-06-18

### Changed
- Sync skill content with the latest SDK surface

## [v0.2.6](https://github.com/runapi-ai/elevenlabs/releases/tag/v0.2.6) - 2026-06-01

### Changed
- Align skill with upstream Input Contract and public API vocabulary changes
- Update endpoint definitions and field constraints

## [v0.2.5](https://github.com/runapi-ai/elevenlabs/releases/tag/v0.2.5) - 2026-05-22

Initial release.
