# Hank-FPS

A first-person shooter training prototype built in **Unreal Engine 5.8** (Blueprint-only, no C++ code), extended from the UE first-person template.

## Features
- Full first-person movement: run, jump, air control, sprint and aim states
- Three weapons: **pistol**, **rifle**, **grenade launcher** (ammo & reload logic)
- Shooting-range interactables: wobble targets, jump pads, doors, and enemies
- Health / ammo pickup boxes and a kill-goal flow
- Custom "night range" visual theme (blue-cyan grid level with warm accents)

## Controls
| Action | Key |
|---|---|
| Move | WASD |
| Look | Mouse |
| Jump | Space |
| Sprint | Left Shift |
| Interact / Pick up | E |
| Shoot | Left Mouse |
| Aim | Right Mouse |
| Reload | R |

## How to run
1. Install Unreal Engine **5.8**.
2. Open `Hank-FPS.uproject` — Blueprint-only, no C++ build needed.
3. Press **Play**; the project defaults to the `Lvl_FirstPerson` map.

## Structure (main pieces)
- `Content/FirstPerson/Blueprints/` — character, weapons, HUD widgets, game mode
- `Content/LevelPrototyping/` — level building blocks: doors, jump pads, targets
- `Content/Characters/Mannequins/` — player / enemy meshes, materials & anims

> Game-design assignment prototype; gameplay logic is Blueprint-only on top of stock engine template content.
