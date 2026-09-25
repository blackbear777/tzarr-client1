# TZARR Client — Minecraft 26.2

A small Fabric client project for **private/local testing and development**.

### Included
- **ESP** — client-side glow highlighting for nearby living entities.
- **Aim Assist** — gently rotates toward the nearest visible player inside a configurable FOV/range.
- **High CPS** — configurable left-click repeat while the physical left mouse button is held.
- **Keybinds** — F8 ESP, F9 Aim Assist, F10 High CPS.
- **Config** — `~/.minecraft/config/tzarr-client.properties`.

### Build
Minecraft 26.2 uses Java 25 according to the current Fabric docs.

Windows:
```bat
gradlew.bat build
```

Output:
`build/libs/tzarr-client-0.1.0.jar`

### Notes
This is intentionally a compact source project so you can extend it. Test it in a private world/server where you have permission. Server-side anti-cheat rules can prohibit client automation.
