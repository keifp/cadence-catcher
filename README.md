# Cadence Catcher

**Play it:** https://keifp.github.io/cadence-catcher/

A five-question aural-skills game: listen to a four-voice chorale phrase and name the cadence that ends it (perfect authentic, imperfect authentic, half, deceptive, or plagal). Built by Keith Pace, D.M.E., as a work sample in music theory assessment design.

## Design decisions

- **Original stimuli.** Five four-voice phrases, voice-led without parallel fifths or octaves. Three share the same opening so the cadence is the only variable.
- **Ear first.** Answering by ear earns 2 points; revealing the score drops it to 1.
- **Answer choices without hints.** Options show only the cadence name, as on an exam. Definitions appear in the feedback after answering.
- **Feedback that teaches.** Each answer explains the harmony, gives a "listen for" cue and a definition, and the end screen offers a retry round for missed questions.
- **Item notes.** Every question documents the skill assessed, expected difficulty, and the reasoning behind its strongest distractor.
- **Accessibility.** Keyboard operable with visible focus, live-region announcements for screen readers, and alt text for each score that describes pitches without revealing the answer.

## Files

- `index.html`: the complete game (HTML, CSS, JavaScript, and inline SVG scores)
- `audio/`: one MP3 per excerpt

Scores were engraved with Verovio from MEI encodings; audio was rendered from MIDI with a General MIDI piano.

An independent work sample. Not affiliated with or endorsed by College Board or the AP Program.

Contact: keithpace@me.com · keithpace.com
