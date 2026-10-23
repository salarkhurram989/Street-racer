# STREET RACER — SALARX RACING

A polished, lightweight arcade street-racing game built for phones, tablets and desktop browsers.

## What changed

STREET RACER now uses a canvas-based racing renderer instead of emoji cars and a basic DOM road. The game has a complete progression loop, responsive controls, dynamic environments and a refreshed premium UI while keeping the project dependency-free.

## Features

- Cinematic STREET RACER / SALARX RACING menu
- Canvas-rendered cars, traffic, road, scenery, lighting and effects
- 7 cars: Starter, Street GT, Supercar, Hypercar, Muscle, JDM and Track Car
- Car unlock levels, prices and individual performance stats
- Garage with car selection and paint customization
- Shop for cars and visual items
- Permanent performance upgrades for top speed, acceleration, handling, braking and nitro
- Endless Race, Time Trial, Traffic Challenge, Speed Challenge and Distance Challenge
- Dynamic city, highway, tunnel and industrial environments
- Day, sunset, night, rain and fog conditions
- Rain particles, speed effects, headlights, shadows and nitro flames
- Traffic with varied speeds and occasional lane changes
- Collision-safe traffic spawning
- Nitro boost with recharge and visual effects
- Missions with coin and XP rewards
- Player levels, XP, coins, best score and best distance
- LocalStorage progression that survives refreshes
- Lightweight Web Audio button/engine-style feedback
- Sound and performance settings
- Responsive phone/tablet/desktop layout
- PWA install support with versioned offline caching
- No external libraries or large asset downloads

## Controls

### Desktop
- Arrow Left / A — steer left
- Arrow Right / D — steer right
- Arrow Down / S — brake
- Space / N — nitro

### Mobile
Use the four large on-screen buttons for left, right, brake and nitro.

## PWA

The manifest is configured for standalone installation and includes local icons. The service worker uses a versioned cache and removes older SALARX caches when a new version activates, reducing stale Street Racer / SALAR OS builds.

## Files

- `index.html` — complete game, renderer, UI and progression
- `manifest.json` — PWA metadata and icons
- `sw.js` — offline caching and cache migration
- `icon-192.svg` — install icon
- `icon-512.svg` — install icon

## Run

Open the GitHub Pages site in a modern browser, or serve the repository from a local web server. PWA installation and service-worker features require HTTPS (GitHub Pages qualifies).

## Branding

**STREET RACER**  
**SALARX RACING**

The old **SALAR OS** branding is not used by the game.

## Author

**Salar** — GitHub: `salarkhurram989`


## 3D Drive Mode

Launch the additional Three.js 3D driving experience from the main menu using **3D DRIVE**. It includes a chase camera, procedural sports car, city road, traffic, acceleration, steering, braking, nitro, distance tracking, and a locally saved best distance. The original SALARX racing game, garage, upgrades, missions, and progression remain available from the main menu.


## Additional game: Car-driving — Endless 3D

Launch **ENDLESS 3D** from the SALARX home menu, or open it directly:

- **[Play Endless 3D Drive](https://salarkhurram989.github.io/Street-racer/endless-drive.html)**
- [Source file](https://github.com/salarkhurram989/Street-racer/blob/main/endless-drive.html)

This is the separate Car-driving game integrated as its own page. It includes multiple driving modes, traffic and difficulty settings, weather presets, vehicle selection and tuning, nitro/boost, keyboard and touch controls, and browser-local progress. Cash, level, best distance, owned cars, upgrades, customization, settings and records save automatically on this device. During a drive, the current session is autosaved about every five seconds; if you refresh or reopen the page, you can choose to resume the saved drive. Use **Save progress** in Drive Settings for a manual save. Progress is stored in this browser on this device (not cloud-synced), and uses a separate storage key from the original STREET RACER game, so the existing garage and progression remain separate.

The original STREET RACER remains the main SALARX game, and the existing **3D DRIVE** mode is still available too.


### Endless 3D Drive controls and vehicle condition

- **Accelerate:** W / Up Arrow; **Brake:** S / Down Arrow; **Steer:** A/D or Left/Right Arrow.
- **Nitro:** hold **N** or **Shift** while accelerating. The boost meter drains during use and recharges when released; the dedicated on-screen Nitro button works on touch devices.
- **Cameras:** use Drive Settings → Camera to choose Chase, Hood, or Cockpit. Press **C** to cycle cameras during a drive.
- **Horn:** H; **Handbrake:** Space; **Pause:** Esc.
- **Vehicle condition:** collisions reduce condition when Collision Damage is enabled. Damage is saved locally between runs. Open the Garage and use **Repair** to restore condition; the garage confirms the coin cost before charging.
- **Progress storage:** vehicle condition and drive progress are saved in this browser on this device, not synced to the cloud.
