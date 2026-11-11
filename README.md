# PvPMods 1.0.0 (Fase 1)

Mod de cliente para Minecraft Java **1.21.11** (Fabric, Java 21). Solo funciones informativas, visuales y locales.

## Compilar
- **Local:** `./gradlew build` -> `build/libs/PvPMods-1.0.0.jar`
- **GitHub Actions (sin PC):** sube este repo a GitHub; en *Actions -> build -> Artifacts* descargas `PvPMods-jar`.

## Uso
- Abrir menu: **Right Shift** (configurable en Controles) o Mods -> PvPMods -> engranaje (Mod Menu opcional).
- Config: `config/pvpmods/` (`config.json`, `profiles/*.json`, `imports/`, `exports/`).

## Incluido en la Fase 1
Sistema de modulos/ajustes, config JSON con perfiles (crear, cargar, borrar, importar, exportar), validacion de valores,
autoguardado, GUI (barra lateral, buscador, toggles, sliders, color hex con vista previa, Save/Cancel/Defaults),
HUD: FPS, Ping, CPS, Coordenadas, Reloj (posicion, tamano, opacidad, colores, fondo, borde, sombra).
