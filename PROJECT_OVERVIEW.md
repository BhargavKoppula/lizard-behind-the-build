# Project overview

## What this project is

**Lizard — Behind the Build** is a public project journal by Bhargav Koppula. It documents the thinking, design direction, experiments and lessons around Lizard, an experimental Chrome extension for personal session reflection.

This repository contains selected narrative and product documentation only. It is not the extension source, a binary distribution or a complete engineering manual. The source is maintained in a private repository; the public request process is described in [SOURCE_ACCESS.md](SOURCE_ACCESS.md).

## Current product status

Lizard is published in the Chrome Web Store as version **3.3.1**. The product supports user-selected Work, Reading and Video sessions, session timelines and history, simple pattern summaries, exports, notifications and an optional Lizzy companion. The purpose is to make a session easier to review—not to determine what a person was thinking or whether they were productive.

The product's development label “v2” and its package version 3.3.1 are different naming systems. The current Store package is 3.3.1; “v2” describes an earlier phase in the product's evolution, not the published package version.

## Product boundary

Lizard uses browser interaction and, where available, media-player signals as limited observations. Inactivity is not proof of distraction. Interaction is not proof of attention. Video playback does not prove viewing, comprehension or learning. The project has not been scientifically validated as a measure of attention or productivity.

## Evidence and historical care

This journal is based on creator-provided history, available project records, the reviewed 3.3.1 package documentation and the public Store listing. It separates confirmed milestones from reconstructed narrative. Dates are included only where a retained record supports them; the exact initial motivation and several decision dates remain unknown.

QA records include browser scenarios in which video playback time remained at zero, even when a player was detected. Automated tests, manual browser observations and Store acceptance are different kinds of evidence. A published listing should not be read as proof that every scenario passed.

## Privacy at a high level

The reviewed extension snapshot was designed around browser-local session records. Static review did not identify an application-data upload path, but that is not a network capture and does not describe browser or Store telemetry. Consult the current Chrome Web Store listing and its linked privacy information for the latest user-facing disclosures; this journal is not a substitute for them.

## Rights and reuse

This repository is published without a separate licence for its prose or screenshots. The MIT licence in the separate private extension repository is not copied here and should not be assumed to license these materials. This repository grants no general reuse permission beyond what applicable law allows.

## Contact

For source-access or collaboration questions, see [SOURCE_ACCESS.md](SOURCE_ACCESS.md). For feedback and project discussion, see [FEEDBACK.md](FEEDBACK.md).
