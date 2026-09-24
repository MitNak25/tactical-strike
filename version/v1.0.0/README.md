# Tactical Strike V1.0 Prototype

## Included

- Main menu and lobby flow
- Counter-Terrorist and Terrorist faction selection
- Top-down Canvas combat
- Keyboard movement and mouse aiming
- Bot opponents
- Obstacles and projectile collisions
- Health and ammunition HUD
- Reloading with `R`
- Buy menu with `B`
- Four weapon choices
- Round timer and scoreboard
- Kill feed and synthesized audio

## Controls

- Move: `WASD` or arrow keys
- Aim: mouse movement
- Fire: left mouse button
- Reload: `R`
- Buy menu: `B`
- Menu: `Escape`

## Known prototype limitations

- Settings controls are visual placeholders and are not wired into gameplay yet.
- Weapon prices are displayed but credits are not implemented yet.
- The browser must support Canvas 2D and Web Audio API.
- Desktop keyboard and mouse input are recommended.

## Run locally

```bash
python3 -m http.server 8000
```

Open `version/tactical_strike_V1.0 -Release.html` through the local server.
