# Web-Game

## Status: ✅ Landing Page COMPLETE | 🎮 Game Core 80% | Questions Next

### 1. Setup ✅
- [✅] Target: Untitled-2.html (visible/loaded)
- [✅] Three.js v0.167.1 CDN + robust fallback
- [✅] HTML structure (landing/game/HUD/popups/levels)

### 2. 3D Village Landing ✅ 
- [✅] Fallback 2D: Sky/7 buildings/7 glowing walking chars (hover works)
- [✅] Popup: name/type/ability/desc on hover
- [✅] Click → Level Select (10 colored difficulty)
- [✅] 3D Three.js village objects added (CDN + fallback; 2D/cards remain if WebGL is blocked)

### 3. Level Select & Game ✅
- [✅] 10 Levels 🟢→🔴 
- [✅] Platformer: WASD/Space, camera follow, platforms
- [✅] HUD: Char/Level/Score/Health bar (fall damage)
- [ ] Per-char differences
- [ ] Enemies/collectibles

### 4. Personality Questions ⏳ NEXT
- [ ] Random mid-game popup
- [ ] Wrong = health-25/die if 0
- [ ] Correct = bonus

### 5. Final Polish ⏳
- [ ] Full Untitled-2 integration (enemies/firewalls/etc)
- [ ] Win screen L10
- [ ] Per-char level tweaks

**Live:** http://localhost:3000/Untitled-2.html (hover circles → popup → levels → play!)

## BUG FIXES - IN PROGRESS

### Issues Fixed:
- [ ] Character display in cell grid - NOT FULLY SHOWN
- [ ] Dark/Light mode theme switch - NEEDED
- [ ] Background visibility - TOO DARK

### Implementation Notes:
1. Canvas height increased from 92px to 110px
2. Vertical centering adjusted from translate(38,64) to translate(38,70)
3. Theme switch button added to home and game UI
4. Background colors adjusted for better visibility
