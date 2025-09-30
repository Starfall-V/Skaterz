# Zombie Skater - GBA Style Endless Runner

A retro-styled 2D endless runner game featuring a skateboarding zombie character. Built with modern web technologies while maintaining authentic Game Boy Advance aesthetics.

## 🎮 Game Features

- **Retro GBA Aesthetic**: 640x960 resolution with pixelated graphics and authentic 16-bit style
- **Dual Character System**: Play as Kev or Stacy, each with unique zombie sprites
- **Infinite Runner**: Endless city street with progressive difficulty and speed increases
- **STAR Collection ($STAR)**: Collect stars to purchase customizations, new characters, game modes, and extra lives
- **Touch Controls**: Tap to jump, swipe up for aerial tricks
- **Leaderboard System**: Database-backed high score tracking with automatic submission
- **Dynamic Soundtrack**: Alternating background music tracks with on-screen artist credits

## 🛠 Tech Stack

### Frontend
- **Framework**: React 18.3.1 with TypeScript 5.6.3
- **Game Engine**: Phaser 3.90.0 for HTML5 canvas rendering
- **Build Tool**: Vite 5.4.19 with hot module replacement
- **Styling**: Tailwind CSS 3.4.14 with custom GBA styling
- **UI Components**: Radix UI primitives with custom themes

### Backend
- **Runtime**: Node.js with Express 4.21.2
- **Database**: PostgreSQL with Drizzle ORM 0.39.1
- **Session Management**: Express sessions with PostgreSQL store
- **Development**: TSX for TypeScript execution

### Game Technology
- **Physics**: Phaser Arcade Physics for collision detection
- **Graphics**: Canvas-based rendering with nearest-neighbor scaling
- **Audio**: Howler.js 2.2.4 for sound effects and music
- **Input**: Unified keyboard, mouse, and touch controls

### Hedera Powered (Configured)
- **Hedera Network**: Receive STAR and unlock additional characters with NFTs you hold
- **Wallet Connect**: Configured Wallet Connect to securely connect your Hedera Wallet

## 🎯 Game Controls

### Desktop
- **Space** or **↑ Arrow**: Jump
- **Space/↑ Again (in air)**: Double Jump (costs stamina)
- **Mouse Click**: Jump
- **J Key (while airborne)**: Perform trick for combo points

### Mobile
- **Tap Screen**: Jump
- **Tap Again (in air)**: Double Jump (costs stamina)
- **Swipe Up (while airborne)**: Perform trick for combo points

## 🎨 Game Mechanics

### Core Gameplay
- **Objective**: Dodge obstacles, crush enemies, and collect $STAR tokens
- **Progressive Difficulty**: Game speed increases as you score more points
- **Survival Focus**: Manage health, stamina, and lives to achieve high scores

### Combat & Movement
- **Enemy Stomping**: Jump on enemies to defeat them and score points
- **Double Jump**: Use stamina to perform a second jump in mid-air
- **Aerial Tricks**: J key (desktop) or swipe up (mobile) while airborne to perform tricks
- **Combo System**: Combine tricks and enemy kills (3+ actions) for bonus stars

### Resource Management
- **Health Bar**: Take damage from obstacles and enemies, restore with sandwiches
- **Stamina Bar**: Required for double jumps and tricks, regenerates over time
- **Life Counter**: Start with 3 lives, earn more at star milestones
- **Star Economy**: Collect stars to unlock features and gain extra lives

### Power-Ups & Items
- **Sandwiches**: Restore 20 health points (with warning arrow indicator)
- **Energy Drinks**: Full stamina restore, temporary invulnerability, and speed boost
- **Single Stars**: Worth 1 star each with collection sound effect
- **Star Clusters**: Worth 10 stars each with special sound effect

### Scoring System
- **Base Points**: 10 points per second survived, 50 points per enemy defeated
- **Combo Multipliers**: x3 to x10 multiplier for successful combo chains
- **Star Bonuses**: Combos convert score points into bonus stars
- **Leaderboard**: Automatic score submission as "Player 1"

---

Built with 💚 for the retro gaming community by SLIME + Starfall V
