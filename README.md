# Wacky Hub.

Gen 1 / Legacy Version Released On : Jul 12, 2026

Gen 2 / Current Version Released On : Jul 23, 2026

A Roblox script hub by RoboSubZero2.


Two versions are maintained in this repo:

- **Wacky Hub Rayfield Gen 1 (SOURCE)** — legacy version, no longer updated.
- **Wacky Hub Rayfield Gen 2 (SOURCE)** — actively maintained, gets new features and updates.

---

## Gen 1 (legacy)

Built on the original [Rayfield](https://docs.sirius.menu/rayfield). No longer updated — kept for reference and as a fallback.

**Home**
- Welcome message + account label
- Show Profile Picture toggle
- Destroy UI button
- Server Info — Ping, Players, Place ID, Job ID labels, with a Copy Job ID button

**Local Player**
- Walkspeed Override
- Jump Power Override
- Gravity Override
- Fast Proximity Prompts
- Fly — toggle or `F` keybind, with a Fly Speed slider
- Noclip — Toggle or `N` keybind.
- Anti-Fling — toggle with a Max Velocity slider

**Camera**
- FOV Changer
- Freecam — toggle or `C` keybind, with a Freecam Speed slider
- *ESP section:* ESP, Tracers, Team Color ESP

**Scripts**
- Infinity Yield
- Better Save Instance
- Rejoin Same Server / Join New Server buttons
- *Utility Scripts:* Dark Dex++, UNC Test, Dark Dex
- _Fun Scripts:_ First Person Toggle

**Lighting** 
- Fullbright
- Disable / No Fog

**Teleportation**
- Select Player dropdown + Teleport to Player (auto-refreshes as players join/leave)

**Settings**
- Enable Keybinds — master switch for the `F` / `C` keybinds
- *Fun:* Explode Selected Part — harmless visual explosion with camera shake


Images

<img width="495" height="469" alt="Screenshot 2026-07-23 152754" src="https://github.com/user-attachments/assets/f1df1db9-157f-4c09-b51a-7141d7c8dffd" />


---

## Gen 2 (current)

Built on [Rayfield Gen 2](https://docs.sirius.menu/rayfield-gen2).


Created On : Jul 23, 2026

**Home**
- Account — shows your login info; tap it for a toast with your avatar
- Show Profile Picture — floating profile picture overlay
- Destroy UI — with confirmation popup
- Server Info — live Ping stat, plus a popup with Job ID, Place ID, and player count
- Interface — FPS stat with a Show FPS Counter toggle and anti Afk

**Local Player**
- Walkspeed Override
- Jump Power Override
- Gravity Override
- Fast Proximity Prompts
- Fly — toggle or `F` keybind, with a Fly Speed slider
- Noclip Toggle or `N` Keybind.
- Anti-Fling — toggle with a Max Velocity slider
- *Camera section:* FOV Changer, Freecam (toggle or `C` keybind) with a Freecam Speed slider
- *ESP section:* ESP, Tracers, Team Color ESP

**Scripts**
- Infinity Yield
- Better Save Instance
- Rejoin Server / Server Hop — pick same-server rejoin or a fresh server, with a toast
- *Utility Scripts:* Dark Dex++, UNC Test, Dark Dex
- **Fun Scripts:** First Person toggle
  
**Teleportation**
- Select Player dropdown + Teleport to Player (auto-refreshes as players join/leave)

**Lighting**
- Fullbright Toggle
- Disable / No Fog Toggle

**Settings**
- Enable Keybinds — master switch for the `F` / `C` keybinds
- *Fun:* Explode Selected Part — harmless visual explosion with camera shake

Images

<img width="457" height="485" alt="Screenshot 2026-07-23 152540" src="https://github.com/user-attachments/assets/3de149be-f224-4d70-a66f-f37cbbb61fbb" />


<img width="441" height="275" alt="Screenshot 2026-07-23 152546" src="https://github.com/user-attachments/assets/75715950-6c10-4ad4-987c-bfbe2c75beb0" />

---

## Loading the script

**Gen 1 (legacy):**
```lua
loadstring(game:HttpGet('https://raw.githubusercontent.com/fisticuffz/Wacky-Hub/refs/heads/Source/Wacky%20Hub%20Rayfield%20Gen%201%20(SOURCE)'))()
```

**Gen 2:**
```lua
loadstring(game:HttpGet('https://raw.githubusercontent.com/fisticuffz/Wacky-Hub/refs/heads/Source/Wacky%20Hub%20Rayfield%20Gen%202%20(SOURCE)'))()
```
