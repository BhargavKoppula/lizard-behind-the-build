# Tracking philosophy

Lizard can report only what its browser instrumentation observes and what its simple rules derive from those observations. The product's most important boundary is that neither layer is a direct window into attention.

## Four different layers

1. **Observed signals** are limited events the extension can see, such as a generic interaction or compatible media-player behavior.
2. **Derived summaries** are calculations about a session, such as elapsed time or the ordering of events.
3. **Heuristic labels** are categories assigned using product rules, such as an active/inactive description or a sample-dependent pattern label.
4. **Human interpretation** belongs to the person reviewing the session and their circumstances.

These layers should not be collapsed into a single “focus score.” A period with no input could be reading, thinking, planning, a break or a technical gap. A period with input could be focused work or unrelated activity.

## What Lizard does not know

Interaction does not reveal what a person is thinking, whether the task is relevant, whether they understood a text, or whether a video helped them learn. A media player can report playback state without establishing that anyone watched it. The project has not demonstrated scientific validity for attention, productivity or learning claims.

## Why cautious language matters

A number can look more certain than the observation behind it. Lizard should name its signals, keep missing/unsupported observations visible and avoid diagnostic language. The product should help someone ask their own questions, not answer those questions on their behalf.

See [known limitations](known-limitations.md) for the specific ways browser and interaction signals can be incomplete.