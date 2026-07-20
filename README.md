# Air Combat Radar & Missile Guidance Sim

A browser-based air-to-air combat simulation built with Three.js. Fly, get radar locks, and fire guided missiles at AI targets.

## Features

- **Radar modes:** Search, TWS (Track-While-Scan), and STT (Single-Target Track), with azimuth/range limits and a scope display.
- **Missiles:**
  - **AIM-7M** — semi-active radar homing, requires a continuous STT lock to guide.
  - **AIM-120** — active radar homing with midcourse datalink updates and an autonomous terminal (pitbull) phase.
- **Guidance:** Proportional navigation (LOS-rate based) blended with a bearing-error correction term and lead-point prediction, so missiles properly intercept off-boresight and maneuvering targets instead of trailing behind them.
- **HUD:** Weapon status, target boxes, kill feed, and radar scope.
- **Missile cam:** Picture-in-picture view riding the most recently fired missile, including a live tracking box on the target as seen from the missile's own camera.

## Running

Just open `index.html` in a browser — no build step or server required.

## Controls

Check in-code key bindings (movement, weapon select/fire, radar mode cycle, target cycle).
