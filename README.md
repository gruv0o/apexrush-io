# ApexRush

## Manage Your Formula Team. Dominate The Championship.

---

## What Is ApexRush?

ApexRush is a **web-based formula racing team management game**. You create your team, manage your budget, upgrade your car, compete in races, and climb the championship ladder.

It's the perfect blend of **strategy** and **racing simulation**.

---

## The Experience

**In ApexRush, you:**

- **Build Your Ecurie** - Create your Formula team from scratch
- **Manage Your Budget** - Every decision counts
- **Upgrade Your Car** - Develop engine, chassis, brakes, gearbox
- **Race & Compete** - Real-time racing with AI opponents
- **Make Tactical Decisions** - Control pace, manage tire wear, call pit stops
- **Progress Through Seasons** - Unlock new circuits, drivers, upgrades
- **Save Your Career** - Play offline, anytime

---

## How It Works

### The Game Loop

```
Your Decision
     |
     v
Race Simulation (Real Physics)
     |
     v
Live 3D Racing (Babylon.js)
     |
     v
Results & Progression
```

### In A Race

- **60 FPS rendering** with 3D circuit and cars
- **Real-time physics** - tires wear, fuel consumption, performance degradation
- **Live decisions** - change pace, call pit stops, manage strategy
- **AI opponents** - 20+ competitive drivers racing alongside you
- **Dynamic results** - every decision impacts your position

---

## Technology Stack

| Tech | Purpose |
|------|---------|
| **TypeScript** | Type-safe, scalable code |
| **React** | Responsive UI & dashboards |
| **Babylon.js** | Real-time 3D racing visualization |
| **Zustand** | Global state management |
| **IndexedDB** | Save careers locally in browser |
| **Tailwind v4** | Modern responsive design |
| **Vite** | Ultra-fast development & builds |

---

## Game Features (MVP)

### Before The Race
- Team creation & management
- Driver hiring & morale
- Car upgrades & customization
- Budget planning
- Season calendar view

### During The Race
- Real-time 3D visualization
- Live leaderboard
- Tire & fuel management HUD
- Pit stop strategy controls
- Pace adjustment (slow/normal/attack)

### After The Race
- Detailed results & stats
- Driver XP & progression
- Points & championship standings
- Upgrade options
- Career saves

---

## The Vision

ApexRush is built on **clean architecture**:

- **Separated Concerns** - Logic is independent from rendering
- **Single Source of Truth** - Global state management (Zustand)
- **Scalable Foundation** - Easy to add features without breaking existing code
- **Performance First** - Optimized game loop, smooth 60 FPS

This means:
- Fast development iterations
- Easy to maintain & extend
- No technical debt
- Professional codebase

---

## Development Roadmap

| Phase | Duration | Focus |
|-------|----------|-------|
| 1 | Week 1 | Core types, store, basic UI |
| 2 | Week 2 | 3D visualization (circuit + cars) |
| 3 | Week 3 | Race simulation engine |
| 4 | Week 4 | Tactical gameplay (tires, pit stops) |
| 5 | Week 5 | Career progression & seasons |
| 6 | Week 6 | Polish, save/load, optimization |

**Launch Target:** 6 weeks to playable MVP

---

## Why ApexRush?

- **No Online Required** - Play offline, browser-based
- **Infinite Replayability** - Unique career paths every playthrough
- **Strategy + Skill** - Not just clicking buttons, real tactical decisions
- **Beautiful 3D** - Watch your team race in real-time
- **Satisfying Progression** - See your team grow stronger each season
- **Accessible** - Simple to learn, deep to master

---

## Technical Highlights

**Clean Architecture:**
- Types -> Store -> Logic -> Rendering (strict separation)
- No coupling between simulation and display
- Logic runs at 30 Hz, rendering at 60 FPS

**Performance:**
- Optimized game loop
- Efficient state updates
- 60 FPS smooth racing

**Scalability:**
- Easy to add new features
- Modular code structure
- Type-safe development

**Browser Native:**
- Pure web technology
- Offline saves (IndexedDB)
- No backend required

---

## The Challenge

Build a **feature-complete formula management game** in **6 weeks** with a **clean, scalable architecture** that's:

- Easy to understand
- Efficient to develop
- Professional quality
- Infinitely expandable

---

## Let's Build This

**Start here:** Follow the development guide in the project README

**Core principle:** Logic -> Store -> UI (never the other way around)

**Goal:** Launch a polished MVP that's fun, fast, and future-proof

---

## Resources

- **Code:** Stackblitz / GitHub
- **Docs:** Complete architecture guide included
- **Tech Docs:** TypeScript, React, Babylon.js, Zustand, Tailwind
- **Updates:** Track progress week by week

---

## Ready?

This is ApexRush. A modern, clean, professional formula management game.

Let's build something awesome.

**Start with Phase 1: Core Types & Store**