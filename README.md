 🚀 Cyber Arena: Space Combat

> **Cyber Guardian Pilot: Defending the Internet Galaxy**  
> A cybersecurity education game for children aged 7–14, built in Unity 2D with WebGL export.

---

## 📖 About the Project

**Cyber Arena** is a top-down 2D space shooter that teaches cybersecurity concepts through gameplay. Players take on the role of the **Cyber Guardian Pilot**, defending the Internet Galaxy from three types of digital threats:

| Level | Enemy | Cybersecurity Topic |
|-------|-------|---------------------|
| Level 1 — Password Attack | Weak-Password Asteroids | Password Safety (NCSC Three Random Words) |
| Level 2 — Phishing Invasion | Phishing Scam Ships | Phishing Awareness |
| Level 3 — Privacy Protection | Hacker Drones | Online Privacy & PII Protection |

The **read-clue-then-shoot** mechanic ensures children engage with real cybersecurity content before every action — making learning active, not passive.

**Academic basis:** NCSC · NSPCC · Childnet · UK Online Safety Act 2023

---

## 🎮 How to Play

- **WASD** — Move your ship
- **Spacebar** — Fire laser
- **Read the Cyber Clue panel** (bottom strip) before shooting
- Destroy the correct targets, protect the safe ones
- 3 lives per level — wrong shots cost a life!

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Unity 2D (LTS) | Game engine |
| WebGL Export | Browser-based play, no install required |
| C# | Game scripting |
| GitHub | Version control & collaboration |
| Trello | Agile Kanban board |

---

## 👥 Team — Group Sagiv

| Name | Role |
|------|------|
| Ishwar | Project Lead & Developer |
| Sumit | Game Logic Developer |
| Fatima | Researcher & Documentation |
| Jigyasha | Designer & Content Writer |

---

## 🌿 Branch Strategy

See [`BRANCH_STRATEGY.md`](./BRANCH_STRATEGY.md) for the full branching guide.

| Branch | Purpose |
|--------|---------|
| `main` | Stable, playable releases only |
| `develop` | Integration branch — all features merge here first |
| `feature/*` | Individual feature development |
| `bugfix/*` | Bug fixes branching from `develop` |
| `hotfix/*` | Critical fixes branching directly from `main` |

---

## 🚀 Getting Started

### Prerequisites
- Unity 2022 LTS or later
- Git (with Git LFS recommended for large assets)

### Clone the repo
```bash
git clone https://github.com/YOUR_ORG/cyber-arena-space-combat.git
cd cyber-arena-space-combat
```

### Open in Unity
1. Launch **Unity Hub**
2. Click **Open** → select the cloned project folder
3. Wait for Unity to import assets
4. Open `Assets/Scenes/MainMenu.unity` to start

### Build for WebGL
1. Go to **File → Build Settings**
2. Select **WebGL** platform
3. Click **Switch Platform**, then **Build**
4. Output folder: `/WebGLBuild/` (gitignored — do not commit)

---

## 📁 Project Structure

```
Assets/
├── Scenes/           # MainMenu, Level1, Level2, Level3, GameOver
├── Scripts/          # All C# game scripts
│   ├── Player/       # PlayerMovement, PlayerShooter
│   ├── Enemies/      # EnemySpawner, EnemyBehaviour, EnemyData
│   ├── UI/           # ScoreManager, LivesManager, CyberCluePanel
│   └── Core/         # GameManager, LevelLoader
├── Prefabs/          # Player ship, enemy types, bullet, UI panels
├── Sprites/          # All 2D art assets
├── Audio/            # SFX and background music
└── Fonts/            # UI typography
```

---

## 📋 Methodology

This project follows **Agile Scrum** with 2-week sprints, managed via a Trello Kanban board. Team roles are assigned using the **Belbin Team Roles** framework.

---

## 📚 References

- NCSC Password Guidance 2024
- NCSC Phishing Guidance 2024
- NSPCC Share Aware Report 2023
- Childnet Digital Literacy Framework
- UK Online Safety Act 2023
- Ofcom Children and Parents Media Use and Attitudes Report 2024

---

## 📄 Licence

This project is developed for educational purposes as part of an academic submission by Group Sagiv (May 2026). All cybersecurity content follows NCSC and NSPCC guidelines.
