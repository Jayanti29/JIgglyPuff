# JIgglyPuff
Jigglypuff Mood Tape is a nostalgic cassette-style web app that transforms emotions into generative music using the Web Audio API. It features animated reels, mood-based color themes, a Calm Advisor, playlist import, and a dynamic tape generator — all built in pure HTML, CSS, and JavaScript.
🎧 Jigglypuff Mood Tape

Jigglypuff Mood Tape is a nostalgic cassette-style web app that turns emotions into sound.

It is designed to feel warm, tactile, and slightly magical — like holding an old mixtape in your hands, but built entirely in the browser.

This version uses a custom Web Audio synthesis engine to generate music dynamically instead of streaming real songs.

✨ What This Project Is

This is not just a music player.

It is a mood-responsive cassette experience where:

You choose a playlist
You generate a mood tape
You change the tape colour
You ask the Calm Advisor how you feel

And the interface responds visually and musically.

Everything runs in pure frontend code.

No backend.
No external API keys.
No frameworks.

🎵 How The Music Works

Instead of streaming real copyrighted songs, this project uses the Web Audio API to synthesize music in real time.

Each playlist track has:

A defined musical style
A seed value for variation
Tempo and chord profiles
Drum and ambient layers

When you press play, the app composes looping sections dynamically.

That is why the artists are labeled “Synth” — it is inspired music, not streamed originals.

🌿 Features

Vintage animated cassette UI
Spinning reels synced with playback
Floating cassette glow effect
Wave bar animation
Multiple curated playlists
Calm Advisor with emotional suggestions
Mood-based colour detection
Dynamic tape generator
Playlist file import support
Volume control
Progress simulation bar
Customisable tape colour palette
Responsive layout

⚠️ Current Limitations

Sound may not start automatically in some browsers due to Web Audio autoplay restrictions.
A user interaction such as clicking play is required to unlock audio.

Music is synthesized and not real studio recordings.
Streaming services are not embedded.

Progress bar simulates duration and does not represent actual track length.

These are intentional design choices for a fully frontend creative build, but improvements are planned.

🛠️ Built With

HTML5
CSS3
Vanilla JavaScript
Web Audio API

Everything lives inside a single HTML file.

📂 Structure

Single file architecture

index.html
README.md

No external dependencies.

🎨 Interactive Sections

Cassette Player
Playlist Tabs
Calm Advisor
Colour Palette System
Mood Tape Generator
Playlist Import

All sections are connected through shared state and audio engine logic.

🌙 Why I Built This

I wanted to experiment with emotion-driven UI and generative sound inside the browser.

This project explores:

Creative frontend animation
Audio synthesis
Mood-based interface behaviour
Nostalgic design storytelling

It blends aesthetic design with interactive systems thinking.

🔮 Future Improvements

More advanced synthesis layers
True duration tracking
Embedded legal streaming integration
Saving generated tapes locally
Improved audio realism
Refactoring into modular structure
Optional React production version

👩‍💻 Author

Jayanti Gautam
BCA Data Science Student
Creative Frontend Developer
