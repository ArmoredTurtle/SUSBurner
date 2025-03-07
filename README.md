# SUSBurner

Suspiciously small StealthBurner. Probably for ants.

![susB (7)](https://github.com/user-attachments/assets/b60f8e9c-bf1f-48be-b630-7ca737befefd)

### Work in Progress

This is very much a work in progress toolhead. Don't complain when thing inevitably change and are no longer compatible.

- 80% scaled Stealthburner that fit's the tiny Vorons like the V0 (more information below)
- 4020 for Part-cooling (like from the Afterburner) and 3010 for Hotend-cooling
- CW2 extruder with adapted internals to for the small formfactor _now legacy_
- SUS-HGX extruder is not the suggested extruder
- Full size nozzle LEDs - same as for his big brother
- Full size logo LED
- Filament cutter based on standard FilamATrix/Filametrix cutters
- Pre-extruder sensor

### Current supported Hotends
*All hotends are currently in testing*  
- "TZ Rapido"
- Rapido
- Rapido UHF
- Dragon UHF
- Voron Revo

## Bill of Materials

| Item | Quantity | Note | Link |
| ---- | -------- | ---- | ---- |
| BTT EBB36 | 1 | Any EBB36 style board should be compatible | [Amazon](https://amzn.to/4hsPKvT) <br/> [KB-3D](https://kb-3d.com/store/controllers-displays-drivers/787-bigtreetech-ebb36-ebb42-v12-can-bus-expansion-board-multiple-styles-1674360588875.html) |
| RGBW LED PCB (WS2812) | 3 | | [AliExpress](https://s.click.aliexpress.com/e/_omOmtH3) <br/> [Amazon](https://amzn.to/4aRcGSS) |
| D2F (without lever) | 1 | D2F-L will work, just remove the lever | [Amazon](https://amzn.to/3WW2GBZ) <br/> [KB-3D](https://kb-3d.com/store/omron/173-omron-d2f-5l-snap-action-micro-switch-limit-switch-1634505070092.html) |
| D2F-L (with lever) | 1 | X End Stop, optional if using sensorless homing | [Amazon](https://amzn.to/3WW2GBZ) <br/> [KB-3D](https://kb-3d.com/store/omron/173-omron-d2f-5l-snap-action-micro-switch-limit-switch-1634505070092.html) |
| Nema 14 Pancake Stepper 10t | 1 | | [Amazon](https://amzn.to/4gu9Qo8) <br/> [KB-3D](https://kb-3d.com/store/stepper-motors-servos/460-ldo-nema-14-high-temp-stepper-motor-36sth20-1004ahg-1640706867164.html) |
| HGX V2 Gear Kit | 1 | | USA: [Pulsar3D](https://pulsar-3d.com/products/hgx-v2-gears) <br/> [AliExpress](https://s.click.aliexpress.com/e/_opnfM9c) |
| 3010 Axial Fan | 1 | | [Amazon](https://amzn.to/415YS3H) <br/> [KB-3D](https://kb-3d.com/store/fans/571-3010-ball-bearing-cooling-fan-24v-axial-1654721311496.html) |
| 4020 Blower Fan | 1 | K1 4020 is a 12,000 RPM fan. Only need the 4020 | [Amazon](https://amzn.to/4bxKapz) <br/> [AliExpress](https://s.click.aliexpress.com/e/_oD0Tzlo) |
| Loctite or Vibratite | 1 | Loctite Blue 242 or Vibra-TITE VC-3 | [Amazon Loctite](https://amzn.to/4hO0Fjt) <br/> [Amazon Vibratite](https://amzn.to/4aRcWkO) |
| 5.5mm Ball Bearing | 1 | | [Amazon](https://amzn.to/4hMpwnG) | 
| #4 Hobby Blade | 1 | These will need to be trimmed to the appropriate length after purchase, about 26mm | [Amazon #4](https://amzn.to/3EvpYIB) |
| ECAS04 Fitting | 1 | | [Amazon](https://amzn.to/4jO8Eih) <br/> [KB-3D](https://kb-3d.com/store/inserts-fasteners-adhesives/707-push-fit-embedded-bowden-fitting-coupler-175-ecas04-1667064368065.html) |
| 4x0.5x25 Compression Spring | 1 | | [Amazon](https://a.co/d/dXcP1B4) |
| M3 Threaded Heatset insert | 34 | 'Voron Spec' - M3x4x5 | [Amazon](https://amzn.to/415ZRRr) |
| M2x10 Self Tapping Screw | 3 | | |
| M2x16 SHCS | 1 | | |
| M3 Hex Nut | 3 | | |
| M3x8 BHCS | 4 | | |
| M3x16 BHCS | 1 | | |
| M3x6 SHCS | 12 | | |
| M3x8 SHCS | 8 | | |
| M3x10 SHCS | 2 | | |
| M3x12 SHCS | 3 | | |
| M3x18 SHCS | 2 | | |
| M3x20 SHCS | 3 | | |
| M3x35 SHCS | 2 | | |

### Acknowledgements

- Voron Design team for the [StealthBurner](https://github.com/VoronDesign/Voron-Stealthburner)
- Kevinakasam for the [WTH-Burner](https://github.com/kevinakasam/WTH-Burner)
- Armored Turtle/Thunderkeys for [FilamATrix](https://github.com/thunderkeys/FilamATrix)
- MapleLeafMakers inspired [EBB36 Mount](https://github.com/MapleLeafMakers/EBB36-DragonBurner)
