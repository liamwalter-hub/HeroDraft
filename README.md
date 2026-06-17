# HeroDraft: Legends of the Multiverse

A browser-based draft-and-battle game. Pick heroes from across fiction, build your team, and watch them fight.

**[▶ Play it here](https://yourusername.github.io/herodraft/)**

---

## How to Play

### 1. Briefing
A quick commander's briefing explains the roles and strategy before you touch the draft board.

### 2. Draft Phase
You and the CPU take turns picking heroes in a **snake draft** (1–2–2–1–1–2–2–1–1–2), so neither side can dominate. Each team must fill five roles:

| Role | What they do |
|---|---|
| **Leader** | Buffs the whole team at the start of each round; tactical strikes |
| **Hero** | Versatile attacker; balanced strength, intelligence, agility |
| **Defender** | Low damage but shields wounded allies and intercepts incoming hits |
| **Warrior** | Hits hardest; bonus damage vs heroes; harder to intercept |
| **Support** | Heals the most wounded ally each round; debuffs the biggest threat |

Each team also picks an **army unit** — soldiers that deal splash damage to the whole enemy side every round.

While drafting, the **CPU Team tab** shows you enemy picks and three tiers of intel:
- **Universe synergies** within their team (their strengths)
- **Vendettas** against your specific heroes (direct threats)
- **Internal rivalries** within their own team (your exploitable openings — a hero who hates a teammate may turn on them mid-battle)

### 3. Battle Phase
Rounds play out automatically in turn order: **Leader → Support → Warrior → Hero → Defender**. Watch the combat log for narrative flavour, rival confrontations, and betrayals. The last team standing wins.

---

## Roster

40 heroes across 14 universes, each with five stats (Strength, Leadership, Durability, Intelligence, Agility), an alignment, rivals, and allies that all affect combat.

**Universes:** Lord of the Rings · Star Wars · Marvel Comics · DC Comics · Harry Potter · Game of Thrones · Star Trek · Ancient Greece · The Hunger Games · Gladiator · Alien · Arthurian Legend · Breaking Bad · Gone Girl · Silence of the Lambs

**Alignments** matter — good/evil mixed teams suffer penalties, rival pairs trigger fury bonuses, and internal rivals have an 18% chance to betray a teammate each round instead of attacking the enemy.

---

## Difficulty

| Difficulty | CPU Draft Strategy | Combat |
|---|---|---|
| Easy | Pure random picks | Standard stats |
| Medium | Power + light synergy awareness, some randomness | CPU +3% HP, +4% damage |
| Hard | Full counter-pick logic — rivals your heroes, builds synergies, avoids internal conflicts | CPU +3% HP, +4% damage |

Win rates (5,000 simulations, player using optimal strategy):
- **Easy** — ~93% player win rate
- **Medium** — ~70% player win rate
- **Hard** — ~47% player win rate (true 50/50)

---

## Mobile

Fully playable on phone. The draft screen uses a three-tab layout (Heroes / Your Team / CPU Team) so nothing is hidden or cramped. Filters, team slots, army picker, alignment alerts, and intel all have dedicated space. The battle screen shows both teams side by side with SVG circle health indicators that drain from green → gold → red.

---

## Technical

- **Single HTML file** — no dependencies, no build step, no server required
- **Zero external requests** — works fully offline
- **GitHub Pages ready** — push and enable Pages on `main`

### Run locally

```bash
git clone https://github.com/yourusername/herodraft.git
cd herodraft
open index.html   # or drag the file into your browser
```

### Deploy to GitHub Pages

1. Push to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Live at `https://yourusername.github.io/herodraft/`

---

## Roadmap

- [ ] Win/loss record across sessions
- [ ] More heroes (Witcher, Dune, Matrix universes)
- [ ] Animated attack flashes in battle
- [ ] Hero detail panel during battle

---

## Credits

Built as a single-file browser game. All characters are fictional property of their respective creators — this is a fan project with no commercial use.
