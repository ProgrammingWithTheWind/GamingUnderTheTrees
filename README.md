# GamingUnderTheTrees
A portal for playing relaxing games and earning points to acquire NFT booster packs

Idea: 
- A portal with mini games, trying to focus on games from a non competitive perspective and more from a relaxation perspective.
- What if the portal has seasons throughout the year, every season players can earn points per day whilst playing games, and the prize is to buy NFT booster packs using points earned and also by paying BlockDAG tokens as well.
- The NFT Booster packs can be created by NFT Artists, and the NFT artists can get majority of the funds from the purchases and the admin for the portal can get a small cut as well, this will allow NFT Artists to gain visibility on through this portal.
- Each mini game played can earn certain amount of points each day
- And then NFT Artists can earn ongoing royalties as the NFT gets sold/purchased moving forward.
- Using Windsurf AI to code this project

Memory Match Game: 
memory-match.html
Type: Standalone page with embedded CSS/JS
Features:
4x4 and 6x6 board sizes
Shuffle, flip, match logic with lock during checks
Moves, matches, and timer HUD
Keyboard accessible (Tab + Enter/Space)
Restart button

Zen Trails Game:
File: 
zen-trails.html
Type: Standalone page with embedded CSS/JS
Gameplay:
Grid-based pathfinding from Start to Goal
Click adjacent tiles or use arrow keys to extend your trail
No loops, walls block movement
Undo via right-click or press U
New puzzle sizes: 6x6 or 8x8
Guaranteed solvable layouts (A* check)
Audio:
Soft ambient pad + filtered noise
Optional: toggle with “Sound: On/Off”
Gentle win chime*

NFT Booster Packs
booster-packs.html
Supply: Max 1000 total, persisted locally
Gating: Open button is disabled unless you have enough points
Cost: 100 points per pack (configurable)
Result: Random NFT artwork with rarity weighting, added to your collection
Persistence: Points, remaining supply, and your collection are saved in localStorage
How it works
Earn points by winning games.
Memory Match now awards points:
4x4: 50 points
6x6: 100 points
Open packs on the Booster Packs page when you have at least 100 points.
Each open:
Deducts 100 points
Decreases supply by 1
Grants a random artwork to your collection gallery