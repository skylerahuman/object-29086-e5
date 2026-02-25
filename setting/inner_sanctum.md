# Inner Sanctum — Complete Mechanical Engineering Spec Sheet

## Design Philosophy: Modular Remnant Architecture

The Yasaminus inner sanctum is not a ship — it's a **self-assembling computational monastery** built incrementally over 87 years at the ISCO of a quasar black hole. The architecture emerged from three constraints:

1. **Impossible to launch monolithically** — no propulsion exists for 10^12 kg single-body ISCO insertion

2. **Must survive centuries of tidal flex, radiation, and QPO stress** — modularity enables fault isolation

3. **Must enforce confessional remnant theology** — 20-person pods as independent churches prevent imperial homogenization

The result: **300 autonomous pressure-vessel pods** (20 people each) arranged in **30 circumferential toroid belts**, connected by **600,000+ MR-fluid Throat tubes** to a sacrificial outer sphere harvested from the accretion disk itself.

---

## Overall Dimensions and Mass Budget

|Parameter|Value|Rationale|
|---|---|---|
|**Outer sphere radius**|800 m|ISCO placement; maximizes sensor/shield area while fitting within tidal gradient tolerance (<0.1% differential across diameter)|
|**Inner sanctum radius**|80 m|Optimal for 1g rotation at habitable rpm; fits 30-belt stack axially|
|**Throat zone thickness**|720 m|Outer radius (800m) - inner radius (80m); contains tube trusses, thermal management, radiation baffles|
|**Total ship diameter**|1.6 km|Same as prior; visible to Roman sonar as "underwater mountain"|
|**Total mass**|~8×10^8 kg|300 pods × 500 tons + frame × 10^6 tons (CNT trusses, ablative hull) + Throat infrastructure × 2×10^8 kg|
|**Construction time**|87 years|300 pods ÷ 3.45 pods/year average (early slow, late fast as swarm scales)|
|**Feedstock source**|Accretion disk|Magnetic scoops harvest ionized Fe, Si, C from corona plasma (~10^20 kg/year available)|

---

## Inner Sanctum Structure — 300-Pod Toroidal Array

## Pod Specifications (Atomic Unit)

**Each pod is a self-contained 20-person habitat capsule:**

|Property|Value|Notes|
|---|---|---|
|**Shape**|Radial toroid slice (36° arc segment)|Cross-section: curved rectangular (1m radial × 4m axial × 16m arc)|
|**Volume**|64 m³ total|50 m³ habitable + 14 m³ systems (bulkheads, ducts)|
|**Mass**|500 tons|200 tons structure + 150 tons life support + 100 tons consumables + 50 tons crew/cargo|
|**Population**|20 people|10 reproductive adults (5M/5F) + 10 children/elderly/support|
|**Rotation radius**|50–80 m from axis|Stacked in 30 belts along axis; belt determines gravity|
|**Effective gravity**|0.6–1.0g|Depends on belt radius and ω|
|**Life support closure**|85%|Local: O₂/CO₂ (plants), water (recycler). Shared: 15% meat/micronutrients from polar farm via drone|
|**Power**|100 W/person|2 kW/pod from axis fusion tap (superconducting bus)|
|**Pressure rating**|1.2 atm internal|Earth-normal; septa rated for ±0.3 atm differential (allows pod-specific atmospheres if needed)|

**Internal layout (4m axial height, 2 floors):**

- **Ground floor (2m ceiling):**

  - Curved communal arc: 16m × 5m chord × 2m high (~160 m³ volume, but pod curvature reduces to ~80 m³ usable)

  - Vertical hydroponic rack: 10 m² (0.5 m²/person, 6 layers) — lettuce, tubers, beans

  - Mini-bioreactor: 1 m³ tank (glows pink, 0.05 m³ working volume/person aggregate) — 0.2 kg meat slurry/person/day

  - Galley printer: molecular assembler for rations (combines dried plants + meat paste + micronutrient cartridges)

  - O₂/CO₂ scrubber: Sabatier reactor (0.5 m³) + algae tanks

  - Water recycler: condensate + urine distillation (98% closure)

  - Sanitation: vacuum toilets (waste to central bioprocessor in polar belt via chute)

- **Upper floor (2m ceiling):**

  - 20 sleep capsules: 1m × 2m × 1m each, stacked 2-high in 10 columns along arc

  - Personal lockers: 0.3 m³/person

  - Terminal alcoves: 4 stations (Lares interface for logging, comms, education)

**Shift staggering:** 4 shifts × 5 people (on-duty, sleep, agri/maintenance, recreation). Only 4–6 people awake simultaneously in communal space — reduces crowding perception.

---

## Belt Specifications (10 Pods per Belt)

**Toroidal belt = ring of 10 pods at fixed radius:**

|Property|Value|Notes|
|---|---|---|
|**Pods per belt**|10|36° × 10 = 360° complete toroid|
|**Belt population**|200 people|10 pods × 20|
|**Belt mass**|5,000 tons|Distributed evenly; tidal-resonant loading|
|**Inter-pod septa**|0.5 m thick|Electromagnetic latches + MR dampers; absorb tidal flex ±2 cm|
|**Septa material**|Layered: 20 cm carbon composite + 20 cm ablative foam + 10 cm lead-boron (radiation)|Opaque; no cross-pod views|
|**Central spine corridor**|1 m wide, runs along inner toroid edge|Used for drone resupply (1×/month/pod); human transit rare (1–2×/year)|
|**Rotation synchronization**|All 10 pods phase-locked via EM torque coils|±0.01 rpm tolerance; prevents shear stress at septa|
|**Circumference at radius**|~300–500 m|Depends on belt position (50–80 m radius)|

**Belt gravity by radius (ω = 3.34 rpm at 80m for 1g):**

|Belt #|Radius (m)|ω (rpm)|Effective g|Population|Primary Use|
|---|---|---|---|---|---|
|1–5 (polar high)|50|2.5|0.35g|1,000|Meat farm, bulk agri, medical low-g|
|6–10|58|2.8|0.5g|1,000|Agri processing, workshops|
|11–20 (mid)|66–74|3.0–3.2|0.7–0.9g|2,000|General quarters, families, Surt's Belt 7 (72m, 0.92g)|
|21–28 (equator)|76–80|3.3–3.4|0.95–1.0g|1,600|Elite, computational clergy, leadership|
|29–30 (polar low)|50 (opposite pole)|2.5|0.35g|400|Lares interface, Throat hubs|

### Total: 30 belts × 200 = 6,000 people

---

## Axial Core Structure (0–50m Radius)

**The non-habitable mechanical spine:**

|Component|Location|Volume|Purpose|
|---|---|---|---|
|**Lares computational core**|0–20 m radius|33,500 m³|Whole-brain emulation processors; quantum/optical hybrid; zero-g optimal for coolant flow|
|**Fusion power taps**|10 m radius ring|1,000 m³|12× compact tokamak modules (500 MW total); waste heat → life support thermal|
|**Throat docking collars**|40–50 m radius, polar caps|50,000 m³|300 pod Throat terminations + 60,000 outer frame anchors; low-g cargo transfer|
|**Central axis light tube**|0–5 m radius, 120 m length|9,000 m³|Fusion-driven plasma lamp (simulates daylight, 20-hr cycle); diffused via fiber to pod ceilings|
|**Coolant manifold**|5–15 m radius|10,000 m³|Liquid sodium loops (carries heat from Lares/fusion to radiators in outer sphere)|
|**Emergency refuge**|25 m radius spherical cavity|65,000 m³|Zero-g safe room (radiation shielded); capacity 500 people for 30 days if pods fail|

**Rotation:** Core rotates with sanctum at belt-average ω (~2.9 rpm) to minimize gyroscopic torque. Lares processors gimballed on magnetic bearings (maintain zero-g regardless of spin).

---

## Life Support — Hybrid Local-Centralized

## Local (Per Pod, 85% Closure)

|Resource|Local System|Output/Person/Day|Tech|
|---|---|---|---|
|**O₂**|Hydroponics + scrubber|1.0 kg|Plants (60%) + electrolysis (40%)|
|**CO₂ removal**|Sabatier + plants|1.2 kg|Methane vented to space (1×/week/pod via spine duct)|
|**Water**|Condensate + urine recycler|15 kg|98% closure; 2% makeup from polar ice (comet-captured reserves)|
|**Food (plant)**|Vertical hydro rack|1.8 kg wet|Lettuce, potatoes, soybeans (monotonous, vitamin-supplemented)|

## Centralized (Polar Belts 1–5, Shared)

|Resource|Facility|Output|Distribution|
|---|---|---|---|
|**Meat protein**|10 polar pods = meat farm (50 m³ bioreactor/pod)|0.9 kg/person/day|Autonomous drones via chutes (1×/month delivery)|
|**Micronutrients**|Chemical synthesis (polar industrial)|Vitamin packs|Monthly resupply|
|**Emergency O₂**|Cryogenic reserve (polar)|30-day buffer|Central tanks, spine-distributed|
|**Waste bioprocessing**|Central digester (Belt 3)|Methane (vented), compost (returned)|Chute collection 1×/week|

**Meat farm details (Belt 1–5 pods):**

- **Total bioreactor volume:** 10 pods × 50 m³ = 500 m³ working volume (+ 25 m³ seed/backup tanks)

- **Cell line:** Genetically optimized bovine myoblasts (110 g/L density, 72-hr doubling time)

- **Harvest cycle:** Continuous perfusion, partial harvest every 3 days (1/3 volume removed, replaced with fresh medium)

- **Sensory signature:** Pink-orange glow (LED stimulation for cell growth); 5–8 Hz thrum during centrifuge harvest (felt ship-wide)

- **Workforce:** 200 people (Belts 1–5) maintain farm — they never descend to equatorial belts
