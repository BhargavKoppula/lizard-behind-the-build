# Lessons learned

These lessons are drawn from the available project record. Dates and original decision details are intentionally omitted where they cannot be established.

## Interaction is not attention

A browser can observe limited input and media-player signals, not a person's thoughts. Quiet work may involve no input, and frequent activity may be unrelated to the intended task. Use neutral descriptions and leave interpretation to the person.

## A summary is only as good as its evidence

A timer, timeline or pattern can make a session easier to inspect, but a precise-looking number can imply more certainty than the observations support. Define what each summary represents, expose missing context and avoid presenting heuristics as validated measures.

## Browser behavior is part of the product

Popup closure, background execution, browser lifecycle and site-specific media behavior can affect the record. Persisted state and deterministic tests address some risks, but real Chrome tests remain necessary. The retained video QA includes zero-playback outcomes; the story should preserve those findings instead of polishing them away.

## Name the kind of evidence

A source-level test shows what happened in a controlled case. A static check does not establish a user experience. A manual browser report is bounded to its particular setup. Store acceptance is not proof of every technical scenario or scientific validity.

## Keep disclosures aligned with the interface

The reviewed package has a user-facing session intention field and reflection-related record fields, but no reviewed popup reflection editor or message call. Store/privacy wording about reflections or notes therefore remains an owner-review discrepancy; this journal does not claim a reflection-entry feature is available.

## Make privacy and control concrete

Local storage is still personal data. Broad browser access, stored timestamps, user-entered intentions and exported files deserve specific explanations. An extension's delete action does not remove files already exported.
