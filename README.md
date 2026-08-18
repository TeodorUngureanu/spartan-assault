# Spartan Assault

Spartan Assault is a browser-based RPG with a Spartan theme, built as a full-stack web application. Players create a character, customize it, gear it up, and take it into battle — against monsters (dungeon) as well as other players (arena/PvP).

## Features

- **Authentication** — registration and login with username/password (passwords hashed with bcrypt).
- **Character creation** — gender and origin selection (north / south / east / west) on first login.
- **Character stats** — level, experience, health, strength, agility, stamina, charisma, and gold.
- **Equipment** — helmet, chestplate, gloves, boots, shield, and weapon, each with its own upgrade level and bonuses.
- **Inventory** — collected items, with automatically calculated minimum/maximum value.
- **Combat** — dungeon and arena (PvP) systems, with a history of wins, losses, draws, damage dealt/taken, and gold won/lost.
- **Weaponsmith** — weapon shop with rotating stock, automatically refreshed at a fixed interval.
- **Guilds, market, crafting, equipment upgrades, training, and leaderboards (top players/guilds)** — additional game modules.
- **Canvas-based UI** — HTML5 Canvas rendering for the main game screen.

## Tech stack

**Backend**
- Node.js + Express.js
- EJS (server-side template engine)
- Passport.js (authentication, local strategy)
- bcrypt (password hashing)
- MySQL, accessed through an ORM (node-orm2)

**Frontend**
- HTML5 Canvas for the game interface
- CSS for rendering graphical elements
- jQuery for client-side interactions

**Architecture**
- A monolithic, server-rendered application with simple REST-style (JSON) routes for the game's dynamic data (stats, equipment, inventory, shop, etc.), consumed by the canvas UI via AJAX.

## Design

<img width="480" height="240" alt="spartan assault 1" src="https://github.com/user-attachments/assets/484aa289-1ac3-47d5-81e5-4073d24042f8" />
<img width="480" height="240" alt="spartan assault 2" src="https://github.com/user-attachments/assets/5e2e4f61-368d-4f8c-b0e2-b693e3045528" />
<img width="480" height="240" alt="spartan assault 3" src="https://github.com/user-attachments/assets/7a6ac569-7c61-41f8-b7c7-11ad7b5b3c66" />
<img width="480" height="255" alt="spartan assault 4" src="https://github.com/user-attachments/assets/93124c97-f3f9-4e61-b4fd-072fe1493fe7" />
<img width="480" height="253" alt="spartan assault 5" src="https://github.com/user-attachments/assets/09069e3d-9e45-49d1-8959-8d5871607f35" />
<img width="480" height="255" alt="spartan assault 6" src="https://github.com/user-attachments/assets/2c83c166-ff28-480a-84a9-13dd552b7c2f" />
<img width="480" height="255" alt="spartan assault 7" src="https://github.com/user-attachments/assets/da222538-061c-4529-ab75-2e44b11accf6" />
