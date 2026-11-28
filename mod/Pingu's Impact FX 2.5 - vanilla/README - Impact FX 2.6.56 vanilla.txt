Pingu's Impact FX 2.6.56 - vanilla
For stock IL-2 Great Battles, game build 20261124 (25 Nov 2026). Jungle Hawks has Impact FX built in: do not use this pack with Jungle Hawks.

Install
- JH-Installer puts this folder in MODS. Enable it in JSGME.
- With 'Pingus Better BoX AI 2 - vanilla' too: enable both packs, then enable 'Pingu's vanilla AI + FX - loader list' last. Its gbml.ini lists both plugins.

Contents
- bin/game/gbml/impactfx.dll: Impact FX 2.6.56.
- bin/game/gbml/impactfx.ini: settings. Test switches laminar_test and scorch_test are 0.
- bin/game/winmm.dll, GBML.dll, gbml.ini: GB Mod Loader 1.6.0 by Dusty.
- data/graphics/effects (pifx, air, arm, surf) and data/graphics/textures (particles, decals): the effect files.
- data/luascripts/hookargs.txt: the stock hook list plus the Impact FX effect entries 58340-58353.

Changes in 2.6.56
- Fire smoke at speed: one continuous trail instead of a chain of separate puffs.
- Sparks: fewer and smaller, at the flame/smoke edge around the engine fire.
- Close-flame distance check uses the real camera position.

Changes since 2.5.1
- Engine fire: flame ring at the cowling of radial engines, inline and underside engine flames, exhaust heat haze.
- Fuel and oil leaks: merged wakes that follow the airflow over the aircraft.
- Fuel fire: dense smoke with a flame sheet at the wing leading edge.
- Effect positions (engine, exhaust, wing tank, scorch surfaces) come from the stock aircraft models.
- Fire chance: fire_chance_pct=50 (0.5 x the 2.5.1 chance). Film particle speed: laminar_speed_pct=100.

Test status
- Offline plugin host on game build 20261124: the plugin installs (init 0). Surface profiles matched 105 aircraft, 0 unknown loose models.
- Not flown.
