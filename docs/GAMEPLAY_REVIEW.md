# Gameplay review — V1.0 Prototype

## Reviewed controls

The current build implements the following input paths:

- `WASD` and arrow keys move the player.
- Mouse movement controls the player angle.
- Left-click fires one projectile.
- `R` reloads after a 1.5 second delay.
- `B` opens and closes the buy menu.
- `Escape` closes the buy menu or returns to the main menu.
- The lobby buttons select the player faction.

## Findings recorded for the roadmap

The build is playable as a desktop prototype. The following systems should be treated as planned improvements rather than fully implemented features:

1. The sensitivity, bot difficulty, and volume settings currently change no gameplay values.
2. Weapon prices are presentation-only; no money or purchase validation exists.
3. The buy-zone label is displayed, but opening the shop is not restricted to a spatial buy zone.
4. Projectile and movement speed are frame-based rather than delta-time based, so very different frame rates can change game feel.
5. Some Canvas drawing colors use CSS variable strings; explicit Canvas color values would be more reliable across browsers.
6. The external menu background image requires an internet connection. An optimized local asset would make releases more dependable.
7. `window.close()` is normally blocked by browsers when the page was not opened by script, so the Exit button may do nothing.
8. Mobile/touch controls are not implemented; keyboard and mouse are the supported input devices.

These findings are documented intentionally so the README remains accurate and the next version can address them one by one.
