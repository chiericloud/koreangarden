# 숫자 정원 · Number Garden 🌸

A cozy little quiz app for learning **Korean numbers** — both counting systems, no flashcards, no keyboard needed.

## Why two number systems?

Korean has two sets of numbers, and knowing *which one to use when* is half the battle:

- **한자어 Sino-Korean** (일, 이, 삼…) — dates, money, phone numbers, minutes, and anything over 99
- **고유어 Native Korean** (하나, 둘, 셋…) — counting things, your age, and hours (goes up to 99)

Number Garden quizzes you on either system, or both mixed, with a little tag on each question telling you which one is being asked.

## How to play

Just open `index.html` in any browser — phone or desktop. No install, no build, no internet needed after loading.

- **Number pad** — see 삼십칠, tap `3` `7` ✓
- **Multiple choice** — see 37, pick the right Korean
- **Listening** — hear the number spoken (browser's built-in Korean voice), answer on the pad — mixed in occasionally, can be turned off

Work your way through five levels, from 🌱 Seedling (1–10) to 🌲 Forest (1000–9999). Score 8/10 to unlock the next one.

## Features

- 📱 Mobile-first, one-hand friendly
- 🔤 Romanization toggle (sam-sip-chil) for pre-Hangul learners
- 🔊 Free audio via the Web Speech API — no accounts or API keys
- 🔥 Streaks, accuracy, and star ratings saved locally in your browser
- 🌙 Automatic warm dark mode
- 🎨 Watercolor Korean-garden background, embedded right in the file
- 🧘 Zero dependencies — one HTML file, nothing tracked, nothing sent anywhere

## Tech

A single self-contained `index.html`: vanilla JavaScript, plain CSS, `localStorage` for progress, `speechSynthesis` for audio. That's it.

## License

[MIT](LICENSE)
