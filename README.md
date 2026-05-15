# 🚌 Grama-Yatri — Improved Edition
**Student:** Shilpa R | **USN:** 1AM22CS182

## What's Improved
| Area | Improvement |
|---|---|
| ETA | Stale pings (>3 hrs) filtered out — no wrong ETAs |
| ETA | Auto-refreshes every 30 seconds even without new pings |
| Firebase | `limitToLast(50)` on pings — saves data bandwidth |
| Firebase | Old pings (>4 hrs) auto-deleted to keep DB lean |
| UI | Loading spinner while routes fetch |
| UI | Your stop highlighted with "← You" label on timeline |
| UI | Prominent ETA card at top of tracking screen |
| UI | Snackbar confirmation after each ping |
| UI | Animated screen transitions (slide left/right) |
| UI | Animated alert banner appearance |
| UI | Quick suggestion buttons in alert dialog |
| UI | Bus emoji 🚌 shown on current stop dot |
| Theme | Full M3 colour palette with containers + dark mode |
| Build | Parallel Gradle builds + caching enabled |

## Setup
1. Open the `GramaYatri` folder in Android Studio
2. Sync Gradle
3. Replace `app/google-services.json` with your Firebase config
4. Enable Firebase Realtime Database
5. Run ▶️
