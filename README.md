# TFT Card Counting

A card counting and probability tracker for Teamfight Tactics (TFT).

Note: This is the public version. API keys and private configuration are not included.

---

## What is TFT Card Counting?

Teamfight Tactics uses a shared card pool, and knowing what is left in it dramatically improves decision-making. This tool tracks which units have been played across the lobby and calculates the remaining probability of hitting specific units on your next roll.

---

## Features

- Card pool tracking to monitor which units have been removed from the shared pool
- Hit probability calculator showing your odds of finding a specific unit at your current shop level
- Real-time state tracking as the game progresses
- TFT-accurate pool sizes based on current set data

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | JavaScript |
| Data | TFT Game Data (public) |
| APIs | Riot Games API (not included in public version) |

---

## Getting Started

```bash
git clone https://github.com/Arminderf-Singh/TFT-Card-Counting-Public.git
cd TFT-Card-Counting-Public
npm install
npm start
```

To use live game data, you will need a Riot Games API key from [developer.riotgames.com](https://developer.riotgames.com). Add it to a `.env` file:

```env
RIOT_API_KEY=your_key_here
```

---

## TFT Pool Sizes (Reference)

| Cost | Pool Size per Unit |
|------|-------------------|
| 1-cost | 29 |
| 2-cost | 22 |
| 3-cost | 18 |
| 4-cost | 12 |
| 5-cost | 10 |

---

## License

MIT
