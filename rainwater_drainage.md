# Gazebo Rainwater Drainage — Design Notes

**Gazebo:** Purple Leaf 10' × 16' Hardtop Gazebo (aluminum frame, galvanized steel double roof)
**Flooring:** 18' × 12' porcelain paver field (see `gazebo_flooring.md`)
**Approach:** Rain chains at each corner post terminating into subsurface dry wells. Surface slope (~1%) and river-rock perimeter as secondary / overflow drainage.
**Reference image:** `reference_resources/gazebo_rainwater_drainage.png`

---

## How the Purple Leaf Roof Drains

The Purple Leaf uses an **internal drainage system**, not open-eave drip. Rain channels through the double-roof panels to the four corners and exits through a hole at the **top of each corner column** (~9 ft above grade). The eave perimeter is dry.

**Implication:** No moisture exposure to the fence from roof drip. All drainage concentrates at four point sources.

---

## The Two Problems to Solve

1. **The 9-ft free fall.** Untreated, water exits the corner hole and free-falls ~9 ft to a hard surface — forceful splash, spray on furniture, erosion of adjacent materials.
2. **Concentrated point delivery.** Four corners = four quarter-roof point sources. Each must absorb its share without pooling or splashing. The pavers are mostly impermeable (tight joints), so water can't just sheet to a permeable edge — it must be managed *at* each post.

---

## Rainfall Volume (Sizing Reference)

Roof footprint = 160 sq ft. Per-corner runoff = 25% of total:

| Rain intensity | Total roof | Per corner |
|---|---|---|
| Light (0.1"/hr) | 0.1 gal/min | 0.02 gal/min |
| Moderate (0.25"/hr, typical) | 0.25 gal/min | 0.06 gal/min |
| Heavy (1"/hr, winter storm) | 1.0 gal/min | 0.25 gal/min |
| Very heavy (2"/hr, rare) | 2.0 gal/min | 0.5 gal/min |

Per-storm totals per corner: ~5–15 gal for a typical Bay Area winter storm, 30+ gal for an atmospheric-river event.

---

## Solution — Four Cooperating Elements

1. **Cup-style rain chain** at each corner — breaks the 9-ft free fall into a controlled cascade.
2. **Subsurface dry well** at each corner — receives water from the chain and infiltrates it into the subgrade.
3. **Gentle paver slope (~1%)** — handles broader surface rainfall and any dry-well overflow.
4. **Loose river-rock perimeter** on three sides — permeable overflow edge.

---

### 1. Rain Chain

Cup-style (not link-style) — cups contain water better at roof-drain flow rates. Attaches to the corner-column drain hole, hangs to paver level, terminates **into** the dry well through the cap. A small anchor weight at the bottom keeps the chain plumb so water enters the pit rather than splashing at the aggregate surface.

Four chains needed. Budget $30–$80 each. Copper patinas; aluminum/steel stays neutral grey.

---

### 2. Subsurface Dry Well (Infiltration Pit)

**Size: 2 ft × 2 ft × 2.5–3 ft deep per corner.**

Sizing math: 2×2×2.5 = 10 ft³ of #57 stone with ~40% voids → ~4 ft³ / ~30 gal storage per corner *with zero percolation*. Handles a full 2"/hr storm-hour per corner as pure storage; with any real infiltration, drains between storms.

**Construction (bottom to top):**
1. Excavate 2×2 ft hole, 2.5–3 ft deep, through the future paver base into native subgrade.
2. Line all sides and bottom with non-woven geotextile fabric. Critical — prevents soil fines from clogging the aggregate long-term.
3. Fill with open-graded #57 stone (clean 1/2"–1" crushed, no fines). Do NOT use bedding sand or closed-graded base rock.
4. Fold geotextile over the top at paver-base level.
5. Cap with one of: decorative stone flush with paver surface (most common; matches river-rock aesthetic), metal grate, or a removable porcelain paver.

**Relationship to the concrete post footing.** Each corner post needs a concrete pier (~12" dia × 24–36" deep, with anchor hardware) to resist uplift and lateral wind loads. The pier and the dry well are **adjacent, not concentric** — they share one paver cut-out but occupy separate cells within it.

**Paver base stability.** A loose-aggregate pit next to compacted paver base is fine if the boundary is controlled:
- Dry well stays contained within the cut-out footprint — no lateral undermining of surrounding base.
- Geotextile forms a vertical barrier between dry-well aggregate and paver-base aggregate at the cut-out wall.
- Edge restraint runs around the cut-out perimeter.
- Subgrade under the paver base gets normal compaction; subgrade under the dry well does not (over-compaction kills infiltration).

**Overflow path.** If a dry well fills in an extreme storm: water backs up to the cap, flows across the paver surface under ~1% grade, and spills into the river-rock perimeter — a large-volume permeable zone.

**Mosquitoes.** A properly draining dry well empties in hours, well under the 7–10 days needed for mosquito development. Not a risk unless soil drainage is very poor (another reason to perc-test).

---

### 3. Paver Surface Slope (~1%)

⅛" per foot across the paver field. Gentler than a tile-on-slab system (which needs 1–2%) because pavers have two drainage paths and settlement is recoverable.

**Fence-side rule:** The paver surface must not slope toward the fence. Fence side is the high side (or at worst neutral). Slope directs any surface flow toward a river-rock edge on one of the three open sides — contractor picks which based on the overall site plan.

---

### 4. River-Rock Perimeter

1" Lynn Creek smooth river rock surrounds the paver field on three sides. The rock itself is permeable — any water reaching the paver edge on an open side spills directly in and infiltrates. This is the **biggest simplification** versus a typical install: permeable overflow is co-located with the paver field, not at a distant landscape edge.

---

## Soil Percolation — The Unknown Variable

Dry wells only work if the subgrade absorbs water. San Mateo soils vary by neighborhood (sandy loam to bay-margin clay). **Run a simple perc test before finalizing dry well depth:**

1. Dig a 12" × 12" × 12" test hole near a corner location.
2. Pre-saturate: fill with water, let drain overnight.
3. Refill to the 12" mark. Measure the drop rate.

Interpretation:
- **>2 in/hr:** Excellent. Baseline sizing is conservative.
- **1–2 in/hr:** Good. 2×2×2.5 is well-sized.
- **0.5–1 in/hr:** Marginal. Go to 2×2×3 ft or deeper.
- **<0.5 in/hr:** Poor. Consider perforated pipe connecting the four wells to an infiltration gallery, or a French drain overflow to a lower landscape area.

If no perc test is possible, default to 2×2×3 ft.

---

## Paver Cut-outs at Corner Posts — Summary

At each corner, a **2 ft × 4 ft cut-out** (two adjacent 2×2 pavers removed) aligned with the paver grid:

- Outer 2×2 cell: concrete pier + aluminum post anchor
- Inner 2×2 cell: dry well + rain chain terminus + decorative stone cap

For the two fence-side corners, orient the cut-out so the dry-well cell is **yard-interior of the post** (keeps dry wells 4.25–6.25 ft from the fence, not 2–4 ft).

Edge restraint runs the full cut-out perimeter.

---

## Full System Flow

```
Rain → double roof → internal gutters → corner drain hole (~9 ft)
  → cup-style rain chain (cascade to ground)
  → terminates into dry well cap
  → percolates through #57 stone
  → infiltrates into native subgrade

Overflow path (extreme storms only):
  dry well fills → backs up to paver surface → ~1% slope →
  river-rock perimeter → subgrade
```

---

## Fence-Adjacent Corners — Notes

Fence-side corner posts are ~3'4" from the fence (3 ft roof clearance + post offset). Dry wells for those corners are positioned on the yard-interior side of the post, keeping excavation ~4.25–6.25 ft from the fence. Water enters the subgrade below the dry well, not along a surface path — essentially no water reaches the fence or its footings.

Subgrade moisture dissipates laterally well within 4+ ft of separation. If a perc test shows very slow infiltration, consider a shallow French drain along the fence side as belt-and-suspenders. In normal soil it's unnecessary.

---

## Contractor Spec Summary

1. **Perc test** at each of the four corner locations; report in/hr per corner.
2. **Cut-outs:** four 2×4 ft at corner post locations, aligned to paver grid, edge restraint around full perimeter of each.
3. **Post footings:** 12" dia × 24–36" deep concrete piers in one cell of each cut-out; Purple-Leaf-compatible anchor hardware; top flush with finished grade.
4. **Dry wells:** 2×2×2.5–3 ft deep (deeper if perc is slow) in the adjacent cell; geotextile-lined; #57 stone fill; fabric folded over top; decorative stone or grate cap.
5. **Rain chains:** four cup-style, terminating into the dry well caps with anchor weights.
6. **Paver base:** 4–6" compacted open-graded base, 1–1.5" bedding, 2 cm porcelain pavers, polymeric sand joints. Base stops at cut-out walls; geotextile forms vertical separation.
7. **Slope:** ~1% across the paver field, fence side high, surface flow directed to a river-rock edge.
8. **Edge restraint:** full outer paver perimeter + full perimeter of each cut-out.

---

## Sources

- [This Old House — How to Install a Rain Chain](https://www.thisoldhouse.com/gutters/21016136/how-to-install-a-rain-chain)
- [Gutter Supply — Rain Chain Styles](https://www.guttersupply.com/rain-chains)
- [Purple Leaf 10×16 Hardtop Gazebo — Amazon listing](https://www.amazon.com/PURPLE-LEAF-Galvanized-Curtains-Nettings/dp/B0GT2SKP2K)
- [EPA — Soak/Infiltration Stormwater BMPs](https://www.epa.gov/soakwaystormwater)
- [Building Advisor — Dry Well Sizing and Construction](https://buildingadvisor.com/exterior/drywells/)
- [UMN Extension — Soils and Drainage (perc test)](https://extension.umn.edu/landscape-design/soils-and-drainage)
