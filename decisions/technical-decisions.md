# Technical decisions

This public summary records technical direction only at a product level. It intentionally omits source paths, permission configuration, message formats, schemas and private implementation algorithms. Most entries are reconstructed from retained technical documentation and QA evidence rather than contemporaneous decision records.

## Build in the browser context

Lizard became a Chrome extension so that a person could start and review sessions in the browser where much computer-based work happens. That choice also brought browser-controlled lifecycle behavior and site/player differences into the product's reliability and privacy considerations.

**Evidence:** current published product and retained architecture/history documentation. **Unknown:** the original selection discussion and alternatives considered.

## Make sessions reviewable across interruptions

The project moved from a simple timer toward session continuity and later review. The current records and technical documentation describe persistent session state and browser-assisted recovery at a high level. The public journal does not publish the underlying recovery design.

**Evidence:** retained technical and QA documentation. **Unknown:** the exact transition date, contemporaneous alternatives and original rationale.

## Prefer local-first records and user control

The reviewed package is documented as keeping session records in browser-local extension storage, with exports initiated by the user and a control for removing completed records. Static code inspection did not identify an application-data upload path, but it is not a live network capture and does not establish what browser or Store telemetry may occur outside the extension code.

**Evidence:** the reviewed package documentation and privacy audit. **Unknown:** no packet-capture study or complete live-installation network audit is represented here. Exported files are outside the extension's deletion control.

## Separate the public journal from implementation

This journal is designed to discuss the motivation, product choices and lessons without distributing the extension source or its internal engineering manual. Requests to review source are handled individually; this project makes no promise of public source access.

**Evidence:** creator's explicit publication boundary for this journal. **Unknown:** no source-access request outcome is implied.

## Treat automated checks as limited evidence

Deterministic Node tests, static checks, manual browser tests and Store acceptance answer different questions. The retained QA record includes video scenarios where playback time remained at zero. A passing test or an accepted Store package must not be presented as proof that every browser situation works.

**Evidence:** retained QA index and publication record. **Unknown:** complete reports and screenshots for some manual runs are unavailable.
