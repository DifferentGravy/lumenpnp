# LumenPnP v4.1.0 — 3D Print Checklist

Generated from `bom.csv` (43 distinct parts, **82 required pieces**, ~1 kg filament).

**STLs are not in this repo.** Download `LumenPnP-STLs-v4.1.0.zip` from the
[v4.1.0 release](https://github.com/opulo-inc/lumenpnp/releases/tag/v4.1.0).

## Printer settings

| Setting | Standard | Gantry parts |
|---|---|---|
| Material | PLA | PLA |
| Nozzle | **0.4 mm — required** | 0.4 mm |
| Layer height | 0.2 mm | 0.2 mm |
| Shells / perimeters | 4 | 4 |
| Infill | 20% (tri or hex) | **30%** |
| Top/bottom layers | 5 / 5 | 5 / 5 |
| Supports | Usually not needed | Usually not needed |

Build volume must be at least 180 × 180 × 180 mm. A nozzle larger than 0.4 mm
will not resolve fine features and parts will not fit.

## Before the full run

- [ ] Print one small test part and confirm M3 hardware + extrusion slots fit

Tolerance fit is the common failure here. Cheaper to find out now than after 1 kg.

---

## Group 1 — Standard PLA, any colour (65 pcs)

20% infill.

- [ ] `extrusion-cable-clip` × 16
- [ ] `board-support` × 8
- [ ] `belt-clamp` × 6
- [ ] `board-mount-static` × 4
- [ ] `peek-cable-clamp` × 3
- [ ] `belt-tension-arm` × 3
- [ ] `back-leg` × 2
- [ ] `back-leg-extension` × 2
- [ ] `front-leg-extension` × 2
- [ ] `blade12` × 2
- [ ] `blade13` × 2
- [ ] `front-left-leg` × 1
- [ ] `front-right-leg` × 1
- [ ] `nozzle-rack` × 1
- [ ] `datum-board-mount` × 1
- [ ] `bottom-camera-mount` × 1
- [ ] `bottom-camera-cover` × 1
- [ ] `static-camera-foot` × 1
- [ ] `aux-staging-plate-foot` × 1
- [ ] `x-motor-mount` × 1
- [ ] `control-box` × 1
- [ ] `control-box-lid` × 1
- [ ] `squaring-bracket` × 1
- [ ] `y-limit-striker` × 1
- [ ] `cable-splay` × 1
- [ ] `8mm-strip-feeder` × 1

## Group 2 — Gantry, any colour, 30% infill (7 pcs)

These carry the moving mass.

- [ ] `z-gantry` × 2
- [ ] `x-gantry-front` × 1
- [ ] `x-gantry-back` × 1
- [ ] `x-idler-mount` × 1
- [ ] `y-gantry-left` × 1
- [ ] `y-gantry-right` × 1

## Group 3 — White PLA (2 pcs)

Colour is functional: these act as light diffusers.

- [ ] `top-light-mount` × 1
- [ ] `bottom-light-mount` × 1

## Group 4 — Dark PLA (2 pcs)

Blocks stray overhead light from interfering with bottom vision.

- [ ] `nozzle-camera-mask` × 2

## Group 5 — Red PLA (1 pc)

- [ ] `z-gantry-backplate-left` × 1 — 30% infill

## Group 6 — Blue PLA (1 pc)

Red/blue distinguishes the two nozzles.

- [ ] `z-gantry-backplate-right` × 1 — 30% infill

## Group 7 — PETG (4 pcs)

The only parts that require PETG — they need the flex to clamp a PCB.

- [ ] `board-mount-dynamic` × 4

---

## Optional — strip feeders

Print only the tape widths you actually use. Each takes
2× M3×10 mm ultra-low-profile button head screws + 2× M3 wing nuts.

- [ ] `12mm-strip-feeder` × ___
- [ ] `16mm-strip-feeder` × ___
- [ ] `24mm-strip-feeder` × ___
- [ ] `32mm-strip-feeder` × ___
- [ ] `adj-strip-feeder` × ___ — 2-piece, adjustable, 32 mm+ (4 screws + 4 wing nuts)
