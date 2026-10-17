# Pet Legends 3D: Boss Hunters

A browser-based **3D** creature-battling prototype built with Three.js. The arena, player avatar, companion pets, bosses, trees, crystals and evolution effects are 3D meshes. The menus/health bars are a 2D HTML overlay, as is common in 3D games.

## Features
- 3D third-person arena with keyboard (WASD/arrow keys) and phone movement buttons
- 200 original generated pet entries, rarities and element colors
- Buy and equip pets using Nigerian naira (₦)
- Boss fights, special attacks, boss rewards, training
- Evolution stages at levels 5, 10, 15, 20, 25, 30, 35, 40, 45 and 50
- Evolution makes pets larger, adds wings/aura/spikes, and increases stats
- Local browser saving

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html` into the repository root.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Wait for GitHub to show the published URL.

## Important
- This is an early 3D browser prototype, not a commercial-quality clone of Pokémon UNITE. Its creature models are procedural low-poly 3D meshes, not professionally sculpted characters.
- It loads Three.js from jsDelivr, so the first load requires an internet connection.
- GitHub Pages hosts the static game. Online multiplayer needs a separate multiplayer server and networking code.
- Save data stays in that browser/device.
