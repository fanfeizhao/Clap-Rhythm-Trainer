BEAT BUILDER WEBSITE

HOW TO RUN IT ON YOUR MAC

1. Unzip the folder.
2. Open Terminal.
3. Move into the unzipped folder. For example:

   cd ~/Downloads/beat_builder_website

4. Start a local web server:

   python3 -m http.server 8000

5. Open this address in Chrome or Safari:

   http://localhost:8000

Use localhost rather than double-clicking index.html because microphone access
works more reliably from a local web server.

MAIN FEATURES

- 1 to 12 measures
- Custom time signatures
- Notes, rests, dotted notes, triplets, and automatic ties
- Horizontal or 4-measures-per-row layout
- Custom pitch, volume, waveform, and uploaded audio sounds
- Metronome and one-measure count-in
- Pause, resume, and exit playback
- Microphone clap detection and timing feedback

For best recording results:
- Stay quiet while recording.
- Use headphones if the metronome continues during the score.
- Do not clap on rests.
- Do not clap again for a tied continuation.
