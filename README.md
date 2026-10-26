# Middle-earth interactive podcast prototype

Open `index.html` in a browser. It is dependency-free and works as a local file.

What exists now:

- A usable listener interface with episode progress, depth controls, optional answer detours, a question box, and saved position.
- Episode 1 script in `episode-01.md`: about 9 minutes of core narration, with three optional two-minute detours.
- Isabella's approved 4.8-second voice sample is wired to the “Hear Isabella’s voice” button. It is deliberately labelled as a sample, not presented as the completed episode.

What is needed before it becomes a full audio experience:

1. Restore or reinstall the local Kokoro renderer used for `bf_isabella`.
2. Render the script in short chunks, join them, and replace the sample source with the resulting full episode MP3.
3. Add a small local question-answer service if live source-grounded replies are required. The current interface demonstrates that behaviour but does not pretend to answer arbitrary questions.
