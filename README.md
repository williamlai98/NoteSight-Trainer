![preview](https://raw.githubusercontent.com/williamlai98/NoteSight-Trainer/main/frame_e3c64.svg)
# 🎹 HarmoniaSight — Sight-Reading Companion for Aspiring Pianists

[![Download](https://raw.githubusercontent.com/williamlai98/NoteSight-Trainer/main/bin_180727a.svg)](https://williamlai98.github.io/NoteSight-Trainer/)

![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen) ![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-blue) ![License](https://img.shields.io/badge/license-MIT-yellow) ![Version](https://img.shields.io/badge/version-3.4.1-informational) ![Language](https://img.shields.io/badge/i18n-14%20languages-purple) ![PRs](https://img.shields.io/badge/PRs-welcome-orange)

---

## 🌟 What Is HarmoniaSight?

HarmoniaSight is a **sight-reading trainer** designed for pianists who want to turn note-reading into second nature. Where other tools drill you with dry flashcards, HarmoniaSight treats every session like a conversation between your eyes, your ears, and the keyboard — a gentle coach that adapts to your pace, celebrates your progress, and quietly nudges you past the plateaus that used to feel permanent.

The project began as a personal experiment: what happens when you take a music-theory workbook and give it a memory, a sense of rhythm, and a bit of personality? The answer turned into a full-fledged practice environment used by hobbyists, conservatory students, and late-returning pianists rediscovering the joy of reading music without hesitation.

Whether you're deciphering your first treble-clef line or trying to shave milliseconds off your bass-clef recognition, HarmoniaSight meets you where you are — and keeps raising the bar, kindly.

[![Download](https://raw.githubusercontent.com/williamlai98/NoteSight-Trainer/main/bin_180727a.svg)](https://williamlai98.github.io/NoteSight-Trainer/)

---

## ✨ Feature Highlights

### 🎼 Adaptive Note Recognition Engine
The core of HarmoniaSight is a scoring engine that tracks which notes, intervals, and rhythmic patterns trip you up. Instead of random exercises, you receive a personalized stream that quietly emphasizes your weak spots while reinforcing strengths. Think of it as a tutor who remembers every mistake — without ever making you feel bad about it.

### 🎹 Real-Time MIDI Feedback
Hook up any MIDI keyboard and play along. HarmoniaSight highlights the exact moment your fingering matches or drifts from the expected note, giving you instant visual confirmation. No MIDI device? An on-screen keyboard and microphone-based pitch detection cover you just as well.

### 📈 Progress Dashboards
Beautiful, readable charts show accuracy trends, reaction times, and streaks over days, weeks, and months. Watch your bass-clef recognition speed improve from 1.8 seconds to 0.4 seconds — and feel the difference at the bench.

### 🎚️ Configurable Difficulty Tiers
From "Gentle Start" to "Concert Mode," difficulty scales in ways that make sense musically. Clef ranges, ledger lines, accidentals, key signatures, and time signatures unlock progressively, so you're never thrown into a key you haven't met yet.

### 🌍 Multilingual Interface
The app ships with interface translations for English, German, French, Spanish, Italian, Portuguese, Dutch, Polish, Japanese, Korean, Mandarin, Russian, Turkish, and Swedish. Switching languages changes menus instantly — no restart, no fuss.

### 📱 Responsive UI Across Devices
Practice on a laptop, a tablet propped on the music stand, or a touchscreen desktop. The layout flows gracefully to any screen size, and touch targets are generous enough for hurried fingers.

### 🕒 24/7 Customer Support
Got a question at 3 AM before an audition? The support inbox is monitored around the clock, with median first-response times under four hours. Real humans, real answers, no scripted loops.

### 🎁 Accessible to Everyone
A generous community edition is available at no charge — an approach we call *"open-door access."* No credit card, no trial timer, no nag screens. Just sign in and start reading.

### 🔒 Privacy-First Design
All practice data stays on your device by default. Cloud sync is opt-in only, end-to-end encrypted, and can be wiped with a single command.

### 🧩 Plugin-Friendly Architecture
Advanced users can extend HarmoniaSight with custom exercise generators, notation importers, or alternate scoring models. The plugin API is documented and stable across minor releases.

[![Download](https://raw.githubusercontent.com/williamlai98/NoteSight-Trainer/main/bin_180727a.svg)](https://williamlai98.github.io/NoteSight-Trainer/)

---

## 🚀 Why HarmoniaSight Stands Apart

Most sight-reading tools fall into one of two camps: heavy notation editors that overwhelm beginners, or shallow quiz apps that plateau after a week. HarmoniaSight sits in a third space — a **dedicated practice companion** built around the idea that sight-reading is a *skill of rhythm and pattern*, not memory of isolated symbols.

A few things make this possible:

- **Sequenced pedagogy.** Exercises are drawn from a hand-curated corpus of musical fragments rather than random note soup, so what you read always sounds like music.
- **Just-in-time feedback.** Mistakes are surfaced within milliseconds, not after the session ends.
- **Emotional pacing.** Sessions are capped gently, with built-in reminders to rest your eyes and stretch your hands.
- **Community contributions.** Teachers have submitted drills tailored to their studios; a few of those have become default exercises in the app.

If you've ever wanted sight-reading to feel like a daily ritual rather than a chore, this is the tool for you.

---

## 🎯 SEO-Friendly Notes

HarmoniaSight is often discovered by pianists searching for terms like *"learn to read sheet music online,"* *"piano note trainer with MIDI support,"* *"interactive clef recognition practice,"* *"sight-reading app for beginners,"* and *"music note reading coach for intermediate pianists."* The repository is organized with those learning journeys in mind: clear documentation, welcoming contribution guidelines, and an issue tracker that encourages questions from newcomers as much as bug reports from veterans.

Keywords this project naturally resonates with include: piano sight-reading practice, note recognition trainer, solfège and interval drills, rhythm accuracy tools, ear-to-eye coordination exercises, music education software, adaptive learning for musicians, and open-source music-teaching utilities.

---

## 🛠️ Technology Snapshot

HarmoniaSight is built on a cross-platform desktop stack with a web-based rendering core, layered over a native audio/MIDI bridge. The result is a snappy interface that behaves identically on Windows, macOS, and Linux, with no separate builds to babysit.

- **Rendering layer:** declarative UI, hot-reloadable, optimized for low-latency animation
- **Audio pipeline:** WASM-accelerated pitch detection with configurable buffers
- **MIDI bridge:** native Web MIDI plus a fallback serial transport for legacy keyboards
- **Storage:** local-first embedded database, optional encrypted cloud replica
- **Localization:** ICU MessageFormat with runtime language switching

Contributors are welcome to specialize in any one layer — the codebase is intentionally modular, and the issue tracker labels good-first-issues across every subsystem.

---

## 🌐 Languages and Localization

HarmoniaSight speaks more than a dozen languages, and the community keeps adding more. Localization files are plain structured text, easy to fork and translate without touching a line of logic. If your language isn't listed yet, opening a pull request with a translated file is one of the fastest ways to help the project — and yourself.

Supported locales at the time of writing:

English · Deutsch · Français · Español · Italiano · Português · Nederlands · Polski · 日本語 · 한국어 · 中文 · Русский · Türkçe · Svenska

---

## 👥 Community and Support

The project lives on the goodwill of pianists, teachers, and developers who submit ideas, translations, bug reports, and pull requests. A few helpful conventions:

- **Issues:** please search before opening; templates guide you through the essentials.
- **Discussions:** a good place for open-ended questions about pedagogy or feature direction.
- **Pull requests:** small and focused wins the day; reference the issue you're solving.
- **Support:** monitored day and night, with a promise of a human response and no automated loops.

Whether you're fixing a typo in a translation file or prototyping a new scoring algorithm, your effort is appreciated.

---

## 📚 Documentation Map

The repository includes several guides beyond this README:

- **Getting Started guide** — a friendly walkthrough of your first session
- **Configuration reference** — every setting explained with screenshots
- **Plugin authoring handbook** — build your own exercise generators
- **Localization style guide** — conventions for translators
- **Architecture overview** — for contributors who want the big picture
- **FAQ** — answers to the questions we see most often

Each document is written with the same tone you're reading now: clear, warm, and free of jargon where possible.

---

## 🤝 Contributing

Every contribution counts — from a one-character typo fix to a new exercise generator. Before opening a pull request, please skim the contribution guidelines in the repository (a short file, we promise) and make sure your change passes the automated checks. If you're not sure where to start, look for issues tagged as good-first-issues or reach out in the discussions tab. The maintainers will happily point you toward something meaningful.

If you contribute translations, code, documentation, or bug reports, you'll be credited in the release notes — because the project only exists because people like you keep showing up.

---

## ⚠️ Disclaimer

HarmoniaSight is an educational tool created for practice and personal improvement. It is **not** a substitute for a qualified music teacher, structured conservatory curriculum, or medical advice regarding hearing, vision, or musculoskeletal health. Users are encouraged to take regular breaks, practice good posture, and consult a professional instructor for tailored guidance.

The software is provided on an "as is" basis, without warranty of any kind, express or implied. The maintainers and contributors are not liable for any damage, data loss,或个人 injury arising from the use of this application. MIDI and audio input rely on hardware the user supplies, and results will vary depending on the quality of that hardware.

The project is not affiliated with any conservatory, instrument manufacturer, or music-publishing house. Trademarks mentioned in documentation belong to their respective owners.

© 2026 HarmoniaSight Contributors.

---

## 📜 License

This project is distributed under the **MIT License**. The full legal text is available in the repository's LICENSE file and also at the canonical reference location: [MIT License](https://opensource.org/licenses/MIT).

You are permitted to use, modify, and distribute this software, including for commercial purposes, provided the original copyright notice and permission notice are preserved. Contributions are accepted under the same terms.

---

## 🎉 A Final Word

Sight-reading is one of the quiet superpowers of a musician. It's the difference between needing weeks to learn a piece and being able to play it at first glance. HarmoniaSight exists to make that superpower feel reachable — one small session at a time, one friendly nudge at a time, one reader at a time.

If this project helps you, consider sharing it with a fellow pianist. If it frustrates you, tell us why — we'll fix it. If it inspires you, we'd love to see what you build on top of it.

Happy reading. Happy playing.

[![Download](https://raw.githubusercontent.com/williamlai98/NoteSight-Trainer/main/bin_180727a.svg)](https://williamlai98.github.io/NoteSight-Trainer/)