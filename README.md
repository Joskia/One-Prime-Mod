# PCZFusionMod (OnePrime)

*[Español](#español) | [English](#english)*

---

## Español

Mod para **Plants vs. Zombies** (versión `com.LanPiaoPiao.PlantsVsZombiesES`, ejecutada sobre BepInEx IL2CPP en Android vía FusionCore) que otorga sol infinito y elimina el cooldown de cartas y herramientas.

- **GUID:** `Joskia_Prime`
- **Nombre:** `OnePrime`
- **Versión:** `1.0.0`
- **Framework:** BepInEx (IL2CPP) + Harmony
- **Target:** `netstandard2.0`

### Funciones

Todas las opciones vienen **activadas por defecto** (el mod no tiene panel de configuración en juego; se ajustan editando el archivo de config).

| Opción | Config key | Descripción |
|---|---|---|
| Sol infinito | `InfiniteSun` | Al plantar, en vez de gastar sol, el costo de la carta se suma al sol disponible. |
| Sin cooldown de cartas | `NoCooldown` | Las cartas del panel quedan siempre listas para usar. |
| Sin cooldown del guante | `NoGloveCooldown` | Atajo 2 siempre disponible. |
| Sin cooldown del martillo | `NoHammerCooldown` | Atajo 3 siempre disponible. |
| Sin cooldown de la carreta | `NoWheelCooldown` | Atajo 4 siempre disponible. |

La configuración se guarda en `BepInEx/config/Joskia_Prime.cfg` tras el primer arranque, y puede editarse ahí manualmente.

### Instalación

1. Tener el juego parcheado con BepInEx IL2CPP (vía FusionCore u otro loader compatible).
2. Copiar `PCZFusionMod.dll` a `BepInEx/plugins/`.
3. Iniciar el juego; el mod se carga automáticamente y genera su archivo de configuración.

### Advertencia

Este mod modifica la economía interna del juego (sol y cooldowns) con fines de uso personal/offline. No se recomienda su uso en modos con progresión online o comparativa entre jugadores.

---

## English

Mod for **Plants vs. Zombies** (`com.LanPiaoPiao.PlantsVsZombiesES` build, running on BepInEx IL2CPP on Android via FusionCore) that grants infinite sun and removes card/tool cooldowns.

- **GUID:** `Joskia_Prime`
- **Name:** `OnePrime`
- **Version:** `1.0.0`
- **Framework:** BepInEx (IL2CPP) + Harmony
- **Target:** `netstandard2.0`

### Features

All options are **enabled by default** (the mod has no in-game config panel; settings are adjusted by editing the config file).

| Option | Config key | Description |
|---|---|---|
| Infinite sun | `InfiniteSun` | When planting, instead of spending sun, the card's cost is added back to your sun total. |
| No card cooldown | `NoCooldown` | Cards on the panel are always ready to use. |
| No glove cooldown | `NoGloveCooldown` | Shortcut 2 is always available. |
| No hammer cooldown | `NoHammerCooldown` | Shortcut 3 is always available. |
| No wheelbarrow cooldown | `NoWheelCooldown` | Shortcut 4 is always available. |

Configuration is saved to `BepInEx/config/Joskia_Prime.cfg` after the first launch, and can be edited there manually.

### Installation

1. Have the game patched with BepInEx IL2CPP (via FusionCore or another compatible loader).
2. Copy `PCZFusionMod.dll` to `BepInEx/plugins/`.
3. Launch the game; the mod loads automatically and generates its config file.

### Disclaimer

This mod alters the game's internal economy (sun and cooldowns) for personal/offline use. It is not recommended for online or player-vs-player progression modes.
