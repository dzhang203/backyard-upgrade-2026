# Gazebo Flooring — Design Decisions (Locked)

## Summary

- **Gazebo:** Purple Leaf 10' × 16' Hardtop Gazebo (aluminum frame)
- **Material:** 2 ft × 2 ft large-format porcelain pavers, 2 cm thick, dry-laid on compacted aggregate base, tight continuous joints with polymeric sand (rectified edges for near-seamless look)
- **Dimensions:** **18 ft × 12 ft** paver field — centered under the 10×16 roof with ~1 ft of paver extending beyond the roof on all four sides
- **Surrounding material:** Smooth 1" Lynn Creek river rock on all four sides (three open sides + the 1.5-ft fence-side gap)
- **Corner treatment:** Four 2 ft × 4 ft cut-outs at the corner post locations, each containing a concrete post footing and an adjacent subsurface dry well for rain chain drainage (see `rainwater_drainage.md`)

---

## 1. Why 18×12 (not 16×10 or 18×10)

### Step-off margin with loose river rock

Loose 1" smooth river rock is an unusually unstable border. A paver field that extends 1 ft beyond the roof on all sides addresses three effects:

1. **Ankle/balance transition.** Smooth rounded rock rolls underfoot. A 1-ft paver margin means your first step off is still on stable surface before the rock starts.
2. **Furniture footing.** Chair legs and side tables placed near a roof-matching paver edge routinely end up with one leg on rock. A 1-ft perimeter keeps the furniture zone on stable paver.
3. **Rock migration.** Loose river rock drifts toward any low-point edge indefinitely. A wider perimeter keeps the migration zone away from the primary seating area.

### Wind-driven rain

Purple Leaf has no eave overhang (internal drainage to corner posts). Without geometry-based protection, wind-driven rain wets the outer 6–18" inside the roof footprint in typical winter storms, and 3–5 ft in strong storms. Extending the floor 1 ft beyond the roof on the long sides absorbs this margin.

### Why not 18×10

18×10 adds margin only on the 10-ft ends, not the long sides where wind-driven rain actually lands. 18×12 adds margin on all four sides including the weather-exposed long sides, for ~20 sq ft additional area (~12.5% more material than 18×10, ~35% more than 16×10).

### Layout

With 2×2 pavers, 18×12 = 9×6 pavers. No cuts needed.

---

## 2. Why Pavers (not tiles)

The choice is between 2 cm porcelain pavers dry-laid on compacted aggregate base vs. 1 cm porcelain tiles wet-laid on a poured concrete slab. Both are porcelain — same material, same manufacturers — so the comparison is between installation systems, not products.

**Reasons for pavers, in priority order:**

1. **No concrete slab → no slab failure modes.** Slabs crack from shrinkage, settlement, and root pressure, and cracks propagate through bonded tile. A paver system has no slab. This is the single biggest long-term robustness difference.
2. **Repairability is categorically different.** Individual pavers lift out with a suction cup and pry bar. Tile repair requires grinding grout, breaking tile, re-bedding, re-grouting, and color-matching — a day's work with imperfect results. Over 20–30 years, small repairs will happen.
3. **Installation-risk asymmetry.** Tile quality depends on skilled wet-install craft at every layer (slab pour, decoupling membrane, thinset, grout), and defects are permanent. Paver quality depends on earthwork (base depth, compaction, grade), which is easier to specify, verify, and recover from.
4. **No grout to maintain.** Polymeric sand joints are DIY-refreshable every 5–10 years. Grout discolors, cracks, needs sealing and eventual regrouting.
5. **Ground movement tolerance.** Individual pavers absorb minor subgrade movement independently. A bonded tile-on-slab system is rigid; movement becomes a crack.

**What pavers don't give you:** Interior-grade seamlessness. With 2×2 rectified-edge pavers on minimum joints, the paver look gets most of the way there, but not all the way. If continuous appearance is the top priority over everything else, tiles would win that axis alone — but none of the other factors favor them here.

---

## 3. Grading and Drainage

Surface slope ~1% (⅛" per foot) across the paver field. Fence side is the high side. Surface flow directs toward the river-rock perimeter on one of the three open sides.

Concentrated drainage at the four corner posts is handled by rain chains terminating into subsurface dry wells — see `rainwater_drainage.md` for the full spec. The river rock perimeter on three open sides serves as a large permeable overflow zone.

Because pavers can be lifted and re-bedded, localized settlement or slope drift over years can be corrected without demolition. Slope precision at install is important but not one-shot.

---

## 4. Contractor Specs

### Paver base

- 4–6" compacted open-graded aggregate base
- Geotextile fabric between subgrade and base
- 1–1.5" bedding layer (#8 stone or coarse sand)
- Polymeric sand in joints
- Contractor to specify compaction method and final-grade tolerance in writing
- **Note:** the paver base spec is different from the dry well fill (see drainage doc). The two zones meet at the cut-out walls but must not intermix — the dry well's geotextile forms the vertical separation.

### Edge restraint

Mandatory around the full perimeter of the paver field (where it meets river rock on all four sides) and around each corner cut-out. Options: hidden steel edging (cleanest), concrete toe (most durable), or buried soldier-course paver.

### Corner cut-outs

Four 2 ft × 4 ft cut-outs at the corner post locations, aligned with the paver grid (removes two adjacent 2×2 pavers per corner). Each cut-out contains:

- A 12" dia × 24–36" deep concrete post footing in one 2×2 cell (with Purple-Leaf-compatible anchor hardware)
- A 2×2×2.5–3 ft subsurface dry well in the adjacent cell (geotextile-lined, #57 stone-filled, capped with decorative stone or grate)
- The rain chain terminating into the dry well

For the two fence-side corners, orient cut-outs so the dry well cell is on the *yard-interior* side of the post (keeping dry wells ~4.25–6.25 ft from fence).

### Paver product

- 2 ft × 2 ft format, 2 cm thickness, rectified edges (for tight continuous joints)
- Outdoor-rated porcelain with DCOF ≥ 0.42 (wet exterior slip safety)
- Color/finish to coordinate with the Lynn Creek river-rock surround

---

## 5. Open Items

- **Confirm main-patio material.** If the main patio uses the same 2 cm porcelain paver, consider one unified paver field rather than a distinct gazebo rectangle — simpler drainage, no material seam.
- **Percolation test** at each corner before finalizing dry well sizing. See `rainwater_drainage.md` §"Soil Percolation."
- **Stormwater compliance.** Confirm whether a paver system (with subsurface dry wells) is treated more favorably than poured concrete under San Mateo's impervious-area rules — may affect permit review.
- **Orientation.** Which long side of the gazebo faces prevailing storm wind? Informs whether curtains on that side are worth adding.
