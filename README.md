# 📚 Lexicon — GRE Vocabulary Quiz

A sleek, interactive GRE vocabulary flashcard app with multiple-choice quizzing, built as a single HTML file. No frameworks, no dependencies, no installation required — just open in a browser and start learning.

**[▶ Live Demo →](https://your-site.netlify.app)**

---

## ✨ Features

- **200+ high-frequency GRE words** — curated from A–Z, covering the most tested vocabulary on the exam
- **Multiple choice quiz** — 4 answer options per card, generated from the word bank
- **Smart distractors** — wrong answers are drawn from the same part of speech, making the quiz genuinely challenging
- **Reveal mode** — stuck on a word? Flip the card to see the full definition, example sentence, and synonyms before answering
- **Instant feedback** — correct answers glow green, wrong answers glow red, with the card auto-flipping to show you what you missed
- **Review Pile** — words you get wrong are automatically saved to a personal review pile for targeted practice
- **Category filters** — study all words, or drill down by Adjectives, Nouns, or Verbs
- **Streak tracker** — stay motivated with a live correct / wrong / streak counter
- **Progress bar** — see exactly how far through the deck you are
- **Keyboard shortcuts** — power through cards without touching the mouse
- **Fully responsive** — works on desktop, tablet, and mobile

---

## 🎮 How to Use

1. A word appears on the card with its pronunciation
2. **If you think you know it** — pick one of the 4 definitions below
3. **If you're unsure** — click **Reveal Definition** to flip the card and study it first
4. After answering, click **Next →** (or press `Enter`) to move on
5. Use **Category filters** at the top to focus on a specific word type
6. Switch to **Review Pile** to re-drill words you got wrong

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1` `2` `3` `4` | Select answer option |
| `R` | Reveal definition |
| `F` | Flip card (after answering) |
| `Enter` / `Space` | Next card |
| `S` | Skip current card |

---

## 📖 Sample Words

The database includes 200+ GRE-level words such as:

| Word | Part of Speech | Meaning |
|------|---------------|---------|
| abstruse | adjective | Difficult to understand; obscure and esoteric |
| perspicacious | adjective | Having keen insight; shrewd and discerning |
| recondite | adjective | Not known by many; dealing with obscure subjects |
| tendentious | adjective | Promoting a particular point of view; biased |
| equivocate | verb | To use ambiguous language to avoid commitment |
| acrimony | noun | Bitterness or ill feeling in speech or manner |
| hubris | noun | Excessive pride or self-confidence |
| laconic | adjective | Using very few words; brief and concise |

---

## 🚀 Getting Started

This is a **single-file app** — no build step, no server, no dependencies.

### Run locally
Just download `index.html` and open it in any browser:
```
double-click index.html
```
That's it.

### Host it yourself
Upload `index.html` to any static hosting service:
- **Netlify Drop** — drag and drop at [netlify.com/drop](https://app.netlify.com/drop)
- **GitHub Pages** — enable Pages in repository settings
- **Vercel** — import this repo at [vercel.com](https://vercel.com)

---

## 🗂 Project Structure

```
gre-flashcards/
└── index.html      ← The entire app (HTML + CSS + JS in one file)
└── README.md       ← This file
```

---

## 🛠 Tech Stack

| Layer | Choice | Why |
|-------|--------|-----|
| Structure | HTML5 | Single-file simplicity |
| Styling | CSS3 (custom properties, animations, grid) | No framework needed |
| Logic | Vanilla JavaScript (ES6+) | Zero dependencies |
| Fonts | Google Fonts (Playfair Display, DM Sans, DM Mono) | Loaded via CDN |

---

## 🎨 Design Highlights

- Dark theme with deep navy/charcoal palette
- Smooth 3D card flip animation on reveal
- Color-coded feedback: green glow for correct, red for wrong
- Staggered MCQ option animations on each new card
- Responsive 2-column option grid (collapses to 1 column on mobile)

---

## 🤝 Contributing

Want to add more words, fix a definition, or suggest a feature? Contributions are welcome!

1. Fork the repository
2. Edit `index.html` — the word database is a JavaScript array called `ALL_WORDS` near the bottom of the file
3. Each word entry follows this structure:
```javascript
{
  word: "perspicacious",
  pron: "/ˌpɜːrspɪˈkeɪʃəs/",
  pos: "adjective",           // "adjective", "noun", or "verb"
  def: "Having a ready insight into things; shrewd.",
  example: "A perspicacious reader noticed the subtle contradiction.",
  synonyms: ["insightful", "shrewd", "perceptive", "astute"]
}
```
4. Submit a pull request

---

## 📄 License

MIT License — free to use, modify, and share.

---

*Built with ❤️ for GRE prep. Good luck on your exam!*
