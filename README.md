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

### Bonus Modes

- **📋 Daily Quiz** — 10 questions across all unlocked skills. Tracks your score history and identifies weak areas.
- **📈 Progress Chart** — Canvas line chart showing daily scores over time, plus per-skill accuracy breakdown.
- **⚡ Speed Round** — 60-second timed drill. No explanations, just rapid-fire. Tracks personal bests per skill.

## Tech

- Single HTML file (~1100 lines), zero dependencies
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
