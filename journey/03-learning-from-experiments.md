# 3. Learning from experiments

The most consequential lesson was a limit, not a metric: interaction is not the same thing as attention. Reading, thinking or planning may be quiet. Frequent mouse or keyboard activity may be unrelated to the task. A browser extension can describe signals it observes; it cannot read a person's mind.

That insight changed the language and the product goal. Lizard moved from “prove focus” toward “help me review what happened during this session.” Quiet time became an ambiguous observation rather than a diagnosis of distraction; activity became a signal rather than a score for productivity.

Experiments also exposed ordinary product-quality problems. Session summaries and timelines did not always agree; popup views could become stale; and video-player discovery did not always translate into recorded playback. These findings were useful precisely because they were not success stories.

The evidence has different strengths:

- Automated regression checks exercise controlled cases; they do not simulate every Chrome page.
- Static checks can verify files and syntax, not whether a person experiences the intended behavior.
- Manual browser tests cover particular setups and sites, not every browser or media player.
- Chrome Web Store acceptance means a submission was reviewed for Store distribution; it is not proof of scientific validity or of every QA scenario.

Retained November 2026 browser notes reported cases where video playback time stayed at zero even after the player was found. The final browser report and screenshots for some runs were not preserved. The project record keeps that uncertainty visible rather than claiming the issue was resolved.

The lesson for future work is to report what was observed, the test setup and what was not tested. A product journal should preserve a failed or inconclusive experiment, not edit it into a clean launch story.
