# Poker Trainer

A progressive, mastery-based poker training app. Master odds, strategy, lingo, and etiquette — one skill at a time.

**[Play it live →](https://saranormous.github.io/poker-trainer/)**

## How It Works

Each skill unlocks when you **prove mastery** of the previous one (7/10 correct in a rolling window). No grinding — just demonstrated ability.

### Skill Track (6 skills, 3 difficulty tiers each)

| # | Skill | What You Learn |
|---|-------|----------------|
| 1 | **Hand Rankings** | Which hand wins? Obvious gaps → kicker fights → ties |
| 2 | **Lingo & Etiquette** | Poker terms + table manners (52 questions) |
| 3 | **Count Outs** | Flush draws, OESDs, combo draws, discounted outs |
| 4 | **Pot Odds** | Call or fold? Clear spots → thin margins → implied odds |
| 5 | **Preflop** | Raise/call/fold by position. Premiums → ranges → 3-bets |
| 6 | **Equity** | Estimate preflop matchup percentages within tolerance |

### Kids Mode 🎒

A full kid-friendly experience for ages 8+. Same 6 skills, but scaffolded with simpler language, fun visuals, and encouraging feedback. Kids progress to the same hard concepts!

- **Multi-profile system** — first launch asks for name + Kid/Grown-Up. Multiple players share one device with separate progress.
- **Purple theme** with larger cards, rounder buttons, bouncy animations
- **Animal player names** (🦊 Fox vs 🐻 Bear) instead of Player 1/2
- **Encouraging feedback** — "🎉 Amazing!" / "Good try! 🌟" instead of "Correct/Wrong"
- **Star rewards** + rank progression (Beginner 🌱 → Card Shark 🦈 → Poker Champ 🏆)
- **Gentler mastery gate** — 5/8 instead of 7/10
- **Kid-safe lingo** — casino etiquette and advanced terms filtered out
- **Simplified explanations** — "helper cards" instead of "outs", "good deal 👍" instead of "+EV"

### Bonus Modes

- **📋 Daily Quiz** — 10 questions across all unlocked skills (6 in kids mode). Tracks score history and identifies weak areas.
- **📈 Progress Chart** — Canvas line chart showing daily scores over time, plus per-skill accuracy breakdown.
- **⚡ Speed Round** — 60-second timed drill (45s for kids). No explanations, just rapid-fire. Tracks personal bests per skill.

## Tech

- Single HTML file, zero dependencies
- Vanilla JS, CSS Grid/Flexbox, Canvas API
- localStorage for persistence
- Mobile-first responsive design
- Deployed via GitHub Pages

## Development

```bash
npx serve -l 3999    # dev server
```

## License

MIT
