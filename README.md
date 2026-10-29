# ElevenRift Hub ⚡

> **Unified Solana Web3 Gaming Hub, Cross-Game Profiles, Item Marketplace & Clan Tournaments.**

ElevenRift is a premier gaming ecosystem built on **Solana**. One single ElevenRift account connects players seamlessly across all partnered titles (including the competitive 5v5 shooter *Sun City*), sharing player profiles, on-chain item inventories, friends, global chat, and SOL balances.

---

## 🌟 Key Features

- **Unified Cross-Game Profile:** Sign in once with passkeys or Web3 wallets. Your username, avatar, and SOL balances seamlessly synchronize across every ElevenRift title.
- **Cross-Game Item Economy & Market:** Trade skins, weapons, armor, and cosmetics directly with other players on the integrated market with instant Solana finality.
- **Clans & Competitive Leagues:** Form or join clans, compete in seasonal tournaments, climb leaderboards, and share clan rewards.
- **Featured Games:**
  - **Sun City:** Fast-paced 5v5 tactical shooter built on Solana mechanics. Custom weapons, skins, and high-stakes ranked matches.
- **Fast & Gasless Microtransactions:** Optimized for Solana's lightning speed and sub-cent fees.

---

## 🚀 Getting Started

### Local Development

Serve the application locally using Python or Node.js:

```bash
# Using Python
python -m http.server 3000

# Or using Node.js serve
npx serve -l 3000
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
├── index.html            # ElevenRift Landing & Discovery
├── games.html            # Games Catalogue
├── market.html           # Cross-Game Item Marketplace
├── clans.html            # Clan Hub & Leaderboards
├── support.html          # Support & Knowledgebase
├── login.html            # Passkey & Web3 Authentication
├── games/
│   └── sun-city.html     # Sun City Showcase & Details
├── api/                  # Avatars, game art, item images, clan media
├── _next/                # Next.js optimized assets (JS chunks, CSS, fonts)
├── logo-mark.svg         # ElevenRift Logo Mark
└── vercel.json           # Clean URL rewrites & hosting configuration
```

---

## 🛡️ License

MIT License © 2026 ElevenRift. Built on Solana.
