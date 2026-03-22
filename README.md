# 🎮 Silly Gamez — Claude

> 🔥 Pure chaos. Pure fun. An AI-assisted party game collection built with Claude — featuring neon aesthetics, spin wheels, sarcasm sound effects, and 200+ questions across 12 categories. Built by Claude, played by everyone. 🎉

---

## 🕹️ Live Games

| Game | Description | Status |
|------|-------------|--------|
| 🤔🔥 Truth or Dare | Neon nightclub party game with spin wheel, punishments & sounds | ✅ Live |

> More games coming soon...

---

## ✨ Truth or Dare — Features

- 🌀 **Spin Wheel** — Animated neon Canvas wheel that ticks through player names and auto-advances turns
- 🎲 **Random Mode** — Instant turn selection, no animation, fast-paced flow
- 😈 **Punishment System** — Refused a dare? Get a random punishment: physical, social, food, or creative
- 🔊 **Web Audio Sounds** — 100% synthesized in-browser: truth chime, dare buzz, loser trombone, win fanfare, wheel ticks
- 💬 **Sarcasm Toasts** — 19 savage roast messages fire every time someone refuses (*"Bruhhhhhh"*, *"LOSER ALERT 🚨"*, *"This is your villain origin story"*)
- ✏️ **Custom Questions** — Add your own Truth or Dare questions, tagged by category, mixed into the pool
- ⏭️ **Skip System** — 2 skips per player, tracked individually
- 🎚️ **Content Levels** — Family / Mild 16+ / Adult 18+ / Personal / Political — stackable per session
- 📂 **12 Categories** — Toggle any on or off before each game
- 🎊 **Confetti** — Canvas confetti on every completed turn
- 📱 **Fully Responsive** — Mobile, tablet, and desktop

---

## 📂 Categories

| | Category | Vibe |
|--|----------|------|
| 🎮 | Gaming | Rage-quits, in-game purchases, toxic plays |
| 🍕 | Food & Drink | Weird combos, food dates, cooking confessions |
| 📚 | Education | School secrets, cheating, memorable teachers |
| ✈️ | Travel | Bucket lists, getting lost, holiday romances |
| 💬 | Relationships | Friendships, exes, crushes, personal confessions |
| 🗳️ | Political | Laws, voting, world problems, hot takes |
| 💪 | Fitness | Gym confessions, fitness goals, embarrassing moments |
| 🎬 | Pop Culture | Movies, celebs, binge-watches, fan fiction |
| 😳 | Embarrassing Moments | Public fails, cringe phases, bad autocorrects |
| 🤫 | Secrets & Confessions | Hidden talents, kept secrets, snowballing lies |
| 🌶️ | Hot Takes | Unpopular opinions, overrated things, hills to die on |
| 🤔 | Would You Rather | Impossible dilemmas with dramatic re-enactments |

---

## 🔊 Sound Effects — Web Audio API

All sounds are **synthesized in real time** — no audio files, no CDN, works fully offline.

| Trigger | Sound |
|---------|-------|
| Sound enabled | 🎵 Ascending chime confirmation |
| Truth chosen | 🔔 Soft gentle melody |
| Dare chosen | 🔥 Edgy sawtooth buzz |
| Card appears | 🃏 Quick frequency whoosh |
| Wheel spinning | 🌀 Click-tick per segment crossed |
| Turn completed | 🎉 Win fanfare |
| Player refuses | 💀 Sad trombone wah-wah |

> **Note:** Tap the 🔊 toggle at the top of the game and turn your volume up before starting!

---

## 🚀 Getting Started

### Option 1 — Just open it
No build step. No install. Single HTML file.

```bash
open index.html
```

### Option 2 — Clone & serve

```bash
git clone https://github.com/your-username/silly-gamez-claude
cd silly-gamez-claude
npx serve .
```

Then open `http://localhost:3000` in your browser.

---

## 🕹️ How to Play

1. Enter player names (2–8 players)
2. Choose turn style — **Random** or **Spin Wheel**
3. Select content levels and toggle categories on/off
4. Optionally add your own custom Truth or Dare questions
5. Enable 🔊 sound and crank the volume
6. Tap **"Let's Go! 🎉"**
7. Each turn — choose **Truth** or **Dare**, answer or face the punishment
8. Use your **2 skips** wisely — they don't refill!

---

## 📁 Project Structure

```
silly-gamez-claude/
├── index.html          # Truth or Dare — entire game in one file
├── README.md           # This file
└── LICENSE             # MIT
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Single-file structure |
| **CSS3** | Custom properties, glassmorphism, keyframe animations |
| **Vanilla JS** | All game logic, state, randomization — no libraries |
| **Web Audio API** | Real-time sound synthesis |
| **Canvas API** | Spin wheel + confetti particle system |
| **Google Fonts** | Bebas Neue + Outfit via CDN `<link>` only |

> ✅ Zero npm dependencies. Zero build tools. Zero backend.

---

## 🎨 Customization

### Add questions
Questions live in the `QDB` object in the `<script>` tag:
```js
QDB.categoryName.contentLevel.truth.push("Your new question here")
QDB.categoryName.contentLevel.dare.push("Your new dare here")
```

### Add punishments
```js
PUNISHMENTS.push({ text: "Your punishment here", cat: "💪 Physical" })
```

### Add sarcasm lines
```js
SARCASM.push("😂 Your roast line here")
```

### Change the theme
All colours are CSS custom properties on `:root`:
```css
--pink: #ff2d78;
--cyan: #00f0ff;
--purple: #b94fff;
--yellow: #ffe03a;
--green: #00ffaa;
```
Edit any of these to retheme the entire game instantly.

---

## 🤝 Contributing

PRs are welcome! Great first contributions:

- 💬 More questions in any category or content level
- 😈 New punishment ideas
- 🙄 More sarcasm toast lines
- 🎨 New theme options
- ⏱️ Timer mode per turn
- 🏆 Score / leaderboard system
- 🌐 Shareable game room links

---

## 📄 License

MIT License — free to use, modify, and distribute.  
See [LICENSE](./LICENSE) for details.

---

<div align="center">

Made with 🔥 for party nights everywhere

*Built with [Claude](https://claude.ai) by Anthropic*

</div>
