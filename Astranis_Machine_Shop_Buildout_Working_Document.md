# Astranis Machine Shop Build-Out — Project Working Document

**Project:** Facilities Build-Out for CNC & TVAC Equipment Installation  
**Facility:** Astranis Space Technologies — Pier 70, San Francisco, CA  
**Document Status:** DRAFT — Working Document for Team Alignment  
**Last Updated:** March 13, 2026  
**Prepared by:** Facilities Director  

---

## Table of Contents

1. [Project Overview](#1-project-overview)
2. [Facility Context](#2-facility-context)
3. [Equipment Specifications](#3-equipment-specifications)
4. [Machine Placement Analysis](#4-machine-placement-analysis)
5. [Infrastructure Design](#5-infrastructure-design)
6. [Safety & Compliance](#6-safety--compliance)
7. [Project Timeline](#7-project-timeline)
8. [Budget Estimate](#8-budget-estimate)
9. [Risks & Mitigation](#9-risks--mitigation)
10. [Open Questions for Leadership & Production](#10-open-questions-for-leadership--production)
11. [Assumptions](#11-assumptions)
12. [Presentation Outline](#12-presentation-outline)
13. [Change Log](#13-change-log)

---

## 1. Project Overview

### Objective

Install and commission three pieces of heavy equipment in the Astranis machine shop at Pier 70, including all supporting facility infrastructure:

| Equipment | Qty | Label | Delivery Timeline |
|---|---|---|---|
| DMG Mori DMU 40 PRO with PH 150 pallet handler | 1 | CNC 1 | 2 weeks |
| Dynavac Rigel TVAC Chamber | 2 | TVAC 1, TVAC 2 | 2 months |

### Scope Includes

- Finalize machine placement (evaluate and potentially adjust production team's suggested locations)
- Design all supporting facility infrastructure (electrical, compressed air, water, LN2, HVAC, foundations, waste management)
- Develop phased project plan with timeline and budget
- Identify top risks and mitigation strategies
- Compile critical questions and assumptions

### Deliverable

A polished leadership presentation (~45 minutes) covering all of the above, suitable for funding approval and project kickoff.

### ⚠️ Immediate Action Items (Week 1 — Before Any Other Work)

These four items are on the critical path and must be initiated immediately upon project approval:

| # | Action | Owner | Why It's Urgent |
|---|---|---|---|
| 1 | **Obtain electrical panel schedule** and engage licensed electrician for NEC load calculation | Facilities | Our load analysis suggests we're at or over 500A service capacity. If a PG&E upgrade is needed, it takes 8-12 weeks. |
| 2 | **Engage structural engineer (PE)** for slab assessment, point-load analysis, and ambient vibration survey at proposed machine locations | Facilities | Foundation design → pour → cure time is on the critical path. CNC 1 arrives in 2 weeks. |
| 3 | **Order 480V-to-208V step-down transformers** (2×, 45-75 kVA each) | Facilities / Procurement | Long-lead item required for TVAC electrical circuits. |
| 4 | **Schedule TVAC 2 placement review** with production area owners | Facilities + Production | We are recommending relocation from interior to exterior wall. Need alignment before infrastructure design proceeds. |

---

## 2. Facility Context

### Building Overview

- **Location:** Pier 70, Dogpatch neighborhood, San Francisco, CA (575 20th Street)
- **History:** Historic shipyard — formerly Union Iron Works / Bethlehem Steel. Built warships during WWI/WWII. Converted to modern manufacturing/office space.
- **Tenant:** Astranis Space Technologies — designs, manufactures, tests, and operates GEO communications satellites
- **Building Dimensions:** Approximately 137'-6" × 112'-1" (per layout)
- **Building Height:** ~50 feet tall
- **Construction:** Bare metal exterior, no wall insulation, 4" thick concrete slab throughout
- **Roof:** Four exhaust fans installed
- **Occupancy:** 10 full-time workers

### ⚠️ Critical Structural Concern — Pier Location

The facility sits on Pier 70, which is a historic waterfront industrial pier. Key concerns:

- **Substructure:** Likely timber piles and fill beneath the concrete slab — this is NOT the same as a slab-on-grade on solid ground
- **Vibration sensitivity:** CNC machines operating at 5-micron positioning accuracy are extremely sensitive to vibration, settling, and ground movement
- **Floor loading:** 4" concrete slab is relatively thin for heavy equipment; TVAC chambers and CNC machines with pallet changers are heavy
- **Seismic:** San Francisco seismic zone — equipment anchoring and foundation design must account for this
- **Action Required:** Structural/geotechnical assessment of the existing slab and substructure before finalizing machine locations and foundation design

### Existing Shop Layout

The floor is already well-populated with the following major equipment zones (all of which are FIXED — cannot be relocated):

**CNC Machines (existing):**
- DMG Mori CTX beta TC 4A (CNC lathe/mill)
- DMG Mori DMC 75 (3-axis vertical machining center)
- DMG Mori DMU 40 PRO (5-axis — separate from "CNC 1" being installed)
- Makino MAG 3.EX (large 5-axis horizontal — requires 70°F ±2°F)
- 2× HAAS VF-2 (vertical machining centers)
- 1× HAAS VF-6 (vertical machining center)
- Matsuura MX-850
- Matsuura MX-330 PC-10

**Other Major Areas:**
- Manual machining (2× manual mills, 2× manual lathes)
- Tube bending / fabrication area
- Secondary processing (tumblers, ultrasonics, lapping)
- Cleaning / Assembly area
- Hydrostatic test area
- Q.C. Lab (Mitutoyo CMM, granite table, Faro Arm, Instron UTS)
- Rework / Finishing cage
- WIP rack storage (extensive — 15+ racks throughout)
- Material / supplies storage racks
- Raw material bar rack
- Kitchen, bathrooms, elevator, electrical room, server room

### Electrical Service

- **Building Service:** 500A @ 480V
- **⚠️ Concern — Potential Showstopper:** Our preliminary load analysis (see Section 5.1 for full detail) estimates existing equipment running demand at 340–470A. Adding the three new machines brings the combined running demand to an estimated 455–610A against a 500A service. **We are likely at or over capacity.** The Makino MAG 3.EX alone has a 130 kW spindle that may draw 100-125A at typical operating loads. A formal NEC load calculation based on the actual panel schedule is required immediately (Week 1) to determine whether a utility service upgrade is needed — this is a potential schedule-critical path item.

---

## 3. Equipment Specifications

### 3.1 DMG Mori DMU 40 PRO with PH 150

**Machine Type:** 5-axis simultaneous milling center with automated pallet handling

**Key Specifications:**
- **Footprint:** 5.05 m² (~54 sq ft) for machine alone; larger with PH 150 attached
- **Machine Width:** Less than 2 meters (~6.5 ft)
- **Positioning Accuracy:** 5 µm per ISO 230-2 (this is the critical tolerance driving thermal and foundation requirements)
- **Spindle:** speedMASTER 20,000 rpm, 32 kW, 130 Nm
- **Work Envelope:** 550 × 450 × 420 mm (X/Y/Z travel)
- **B-Axis Swivel:** -35° to +110°
- **Max Table Load:** 300 kg
- **Machine Bed:** One-piece gray cast iron
- **Drives:** Direct-driven ball screws in X/Y axes
- **Cooling:** Comprehensive cooling concept for long-term thermal stability (PRO variant)
- **Control:** CELOS with Siemens or Heidenhain

**PH 150 Pallet Handler:**
- Configurations from 24 round pallets (ø148mm) to 4× 500×500mm pallets
- Up to 150 kg workpiece weight standard (expandable to 250 kg)
- Up to 300 kg transfer weight (workpiece + pallet)
- Separate setup station for simultaneous loading/unloading
- Controlled via machine control panel

**Utility Requirements (per prompt):**
- 30A / 480V three-phase power supply
- 1 cfm compressed air

**Additional Infrastructure Needs Identified:**
- DI water supply (preferred over city water for coolant mixing and tool cooling)
- Coolant supply and return system
- Chip conveyor and segregated chip collection bins (separate by material: aluminum, steel, titanium, etc.)
- Tramp oil separator (either integrated or standalone skimmer/coalescer — verify with DMG Mori)
- Spill containment / drip pans
- Foundation assessment — cast iron bed is sensitive to floor movement
- Service clearance: minimum 36" on all sides, more on pallet changer load side
- **Future consideration:** Potential for Robo2Go Milling automation add-on — plan power/space accordingly

### 3.2 Dynavac Rigel TVAC Chambers (×2)

**Equipment Type:** Thermal vacuum chamber for satellite/component space simulation testing

**Key Specifications:**
- **Size Range:** 8 to 16 feet diameter/width (exact size for Astranis units TBD — confirm with procurement)
- **Geometries Available:** Cylindrical, box (cubic), and D-shaped
- **Construction:** Type 304 stainless steel
- **Leak Rate:** Tested to < 1×10⁻⁹ std/cc/sec
- **Base Pressure:** < 1×10⁻⁶ Torr
- **Pumping System:** Dry mechanical roughing pump + high vacuum cryopumps (turbomolecular pumps optional)
- **Thermal Range:** -180°C to +150°C
- **Thermal Ramp Rate:** > 1°C/minute
- **Thermal System:** Thermal Control Unit (TCU) supplies conditioned gaseous nitrogen to thermal shroud and platen
- **Platen:** Aluminum construction with 1/4-20 threaded Nitronic inserts on 4" grid
- **Controls:** LabVIEW-based on PC, 24" HD LCD monitor, embedded PLC for fail-safe operation
- **Remote Diagnostics:** Included
- **Warranty:** Standard one-year Dynavac warranty
- **Installation:** On-site installation and start-up service available from Dynavac

**Utility Requirements (per prompt, per chamber):**
- 80A / 208V single-phase power supply
- 3 gpm liquid nitrogen
- 1 cfm compressed air

**Additional Infrastructure Needs Identified:**
- LN2 bulk storage tank (exterior) — estimated 1,500–3,000 gallon capacity for 6 gpm combined consumption with reasonable delivery cycle
- Vacuum-insulated LN2 piping from exterior tank to each chamber
- LN2 pressure regulation and distribution system
- Vacuum pump exhaust routing (must vent outside or to a dedicated exhaust system)
- O2 depletion monitoring system (continuous monitors with audible/visual alarms)
- Emergency ventilation system for LN2 leak scenarios
- Dedicated electrical circuits from panel (2× 80A/208V — likely requires step-down transformer from 480V service)
- Service clearance around chambers for door operation, test article loading, pump access
- Test article loading cart/crane access path
- Safety signage, PPE station, emergency procedures posted
- **Weight:** These chambers are extremely heavy — structural assessment required for placement locations

**Available Accessories (may be needed):**
- Cryopanels, cold plates, cold fingers
- User signal and power feedthrough plates
- Thermal data acquisition system (TDAS)
- Auxiliary thermal control system (ATCS)
- Test article loading carts

---

## 4. Machine Placement Analysis

### Production Team's Suggested Locations (from layout)

| Machine | Suggested Location | Notes |
|---|---|---|
| CNC 1 | Upper-left quadrant, adjacent to existing CNC cluster | Near the existing DMG Mori machines and Makino |
| TVAC 1 | Upper-left area, near CNC zone | Large open area adjacent to electrical room |
| TVAC 2 | Center-right area, near kitchen | Interior location, significant distance from exterior walls |

### Placement Evaluation Criteria

1. **Structural adequacy** — Can the floor support the equipment at this location?
2. **Utility access** — How far are electrical, air, water, and LN2 runs?
3. **Safety setbacks** — LN2 and O2 depletion risk, egress paths, emergency ventilation
4. **Workflow** — Proximity to related operations (CNC near raw material and QC; TVAC near assembly/test)
5. **Service clearance** — Room for maintenance, loading, pallet changes, door swing
6. **Rigging path** — Can we physically get the machines into these locations?
7. **Future expansion** — Room for accessories or additional equipment
8. **Thermal zoning** — Co-location of thermally sensitive equipment and materials

### CNC 1 Placement Assessment

**Recommendation: AGREE with suggested location, with adjustments. ✅**

**Rationale — Why the upper-left CNC cluster location works:**
- Clustering CNC machines together makes sense for shared infrastructure — compressed air drops, coolant supply lines, DI water, and chip management all become more efficient when centralized rather than distributed
- Proximity to the existing CNC zone (DMG Mori machines, Makino, HAAS) enables a **unified thermal control enclosure** covering all precision machines. One enclosure is far more cost-effective than two.
- Close to raw material storage — this is critical for thermal equilibrium. Bar stock or billets brought in from outside at ambient temperature must stabilize to room temperature before machining. At 5-micron tolerances, even a few degrees of thermal differential in the workpiece will cause dimensional drift during the cut cycle.
- Close to Q.C. Lab (Mitutoyo CMM, granite table, Faro Arm) for quick inspection turnaround — reduces WIP transport distance
- Close to existing electrical room — shorter conduit runs for the 30A/480V circuit

**Proposed adjustments:**
- **Service clearance:** Ensure minimum 36" clearance on all sides per DMG Mori installation requirements. Expand to **48" minimum on the PH 150 pallet load/unload side** — operators will need room for pallet staging carts, and the PH 150 setup station needs unobstructed access. If Robo2Go automation is added in the future, this clearance becomes even more critical.
- **Machine orientation:** Orient the machine so the chip conveyor discharge routes to a central chip collection point without crossing pedestrian traffic paths. The operator-facing side (control panel + PH 150 setup station) should face toward the main aisle for ergonomic access.
- **Foundation:** Verify slab adequacy at this specific location (see Section 5.7). The DMU 40 PRO's one-piece gray cast iron bed requires a dead-flat, vibration-free surface. May need an isolated machine pad decoupled from the building slab.
- **Chip management zone:** Designate floor space adjacent to CNC 1 (and the broader CNC cluster) for **segregated chip collection bins** — separate bins for each material type (aluminum, steel, stainless, titanium). Mixed chips contaminate recycling streams and can cause quality issues. Color-code and label bins clearly.
- **Material co-location:** Raw material storage (bar rack, billets, pre-cut blanks) **must be inside the same thermally controlled zone** as the CNC machines. Material stored at a different temperature will expand or contract mid-process, making 5-micron tolerances unachievable.
- **Future-proofing:** Pull oversized conduit and leave spare electrical capacity at the machine location for potential Robo2Go Milling automation add-on. Cheaper to install now than retrofit later.

### TVAC 1 Placement Assessment

**Recommendation: AGREE with suggested location — workable with caveats. ✅**

**Rationale — Why the upper-left area near the electrical room works:**
- **Proximity to exterior wall** is a strong positive — this enables shorter LN2 piping runs from the exterior bulk tank, easier vacuum pump exhaust routing directly through the wall, and better ventilation options in an O2 depletion scenario
- **Adjacent to electrical room** — beneficial for the 80A/208V circuit and step-down transformer installation. Shorter conduit runs reduce cost and voltage drop.
- **Large open area** — appears to have sufficient footprint for a Rigel-class chamber (8-16 ft) plus service clearance on all sides
- **Within the yellow build-out zone** — does not conflict with existing fixed equipment

**Key requirements for this location:**
- **Door swing clearance:** The Rigel chamber has a full-opening door. For a 10-12 ft diameter chamber, the door swing radius could be 5-6 ft or more. Confirm exact model dimensions with procurement and ensure no obstructions within the door arc.
- **Test article loading path:** Need a clear, straight path from the assembly/test area to TVAC 1 for loading cart or crane access. Test articles (satellite components/subsystems) on loading carts require smooth, unobstructed floor.
- **Vacuum pump location:** Roughing pumps and cryopumps are typically floor-mounted adjacent to the chamber. Allow 6-8 ft on the pump side for pump skid, exhaust piping, and maintenance access.
- **LN2 piping penetration:** Identify the wall penetration point for vacuum-insulated piping from the exterior bulk tank. This wall penetration should be as close to TVAC 1 as possible.
- **Structural assessment:** TVAC chambers are extremely heavy — a Rigel in the 10-12 ft range may weigh 10,000-20,000+ lbs. Point-load analysis required at this specific location (see Section 5.7).
- **Egress:** Confirm that the chamber does not block any required egress routes from the electrical room or other occupied spaces.

### TVAC 2 Placement Assessment

**Recommendation: RELOCATE — move closer to an exterior wall. ⚠️ This is our strongest pushback on the production team's plan.**

**Problems with the current suggested location (center-right, near kitchen):**

1. **LN2 Safety — this is the primary concern.** The suggested location places a major cryogenic system in the most populated interior area of the building, adjacent to the kitchen and occupied workspaces. Liquid nitrogen expands 695:1 when vaporizing. In a leak event at this interior location:
   - Oxygen is displaced in the area farthest from exterior walls and ventilation
   - The kitchen and nearby workbenches are occupied areas — personnel exposure risk is highest here
   - Emergency ventilation is most difficult to achieve at the building's interior
   - N2 gas initially pools at floor level before mixing — seated workers at desks/benches are at greatest risk

2. **Infrastructure cost.** Vacuum-insulated LN2 piping is expensive (~$150-300/linear foot installed). The run from an exterior bulk tank to the building's center is significantly longer than to an exterior wall location. Every additional foot of piping adds cost and introduces more joints that could develop leaks over time. Thermal losses in longer piping runs also increase LN2 consumption.

3. **Vacuum pump exhaust routing.** Roughing pump exhaust must be vented to the exterior. From the center of the building, this requires a long exhaust run — either overhead or at floor level — routed around existing equipment. This adds cost, complexity, and potential maintenance issues.

4. **Rigging complexity.** Getting a chamber that is potentially 8-16 ft in diameter into a tight interior location surrounded by existing equipment, the kitchen, WIP racks, and work benches is a logistical challenge. The rigging path must thread through the occupied shop floor without disrupting fixed equipment.

**Proposed alternative — relocate TVAC 2 to an exterior wall location:**

- **Preferred:** Along the same wall as TVAC 1 (upper-left / left wall) if space permits. This creates a **unified TVAC zone** with enormous advantages:
  - Single LN2 piping trunk line from the exterior tank that branches to both chambers — dramatically reduces piping cost
  - Shared O2 monitoring system and safety infrastructure (PPE station, emergency procedures, ventilation)
  - Shared vacuum pump exhaust routing through the same wall section
  - Single safety zone to manage rather than two separate zones on opposite sides of the building
  - Simplified operator workflow — TVAC technicians work in one area rather than walking across the shop

- **Alternative:** Along the lower/south exterior wall if the left wall lacks sufficient space. This is less ideal (longer LN2 piping, separate safety zone) but still far preferable to the interior location.

**Anticipated production team pushback and response:**
- *"We want TVAC 2 near assembly/test for workflow."* — Understood, but the safety, infrastructure cost ($30K-$50K+ in additional piping and exhaust routing), and rigging logistics strongly favor an exterior wall location. Test article transport distance is a minor inconvenience compared to the risks and costs of an interior cryogenic installation. A clear aisle with a loading cart solves the workflow concern.

**⚠️ Action Required:** Schedule a placement review meeting with production area owners to discuss TVAC 2 relocation. Bring this analysis. If production insists on the interior location, we need to formally document the additional cost, safety requirements, and risk acceptance.

### Open Items — Placement

- **Yellow highlighted area on layout:** This appears to represent the designated new/unused build-out zone. Boundaries need confirmation from the production team before finalizing any placement.
- **Rigging path:** Building entry points (roll-up doors), door dimensions, and clear height must be confirmed for all three machines. The TVAC chambers (potentially 8-16 ft diameter) may require disassembly or a special entry path.
- **TVAC exact model/size:** The specific Rigel configuration ordered (8 ft, 10 ft, 12 ft, 16 ft?) must be confirmed with procurement — this drives floor space, structural loading, door swing clearance, and rigging requirements for both chambers.

---

## 5. Infrastructure Design

### 5.1 Electrical

**⚠️ POTENTIAL SHOWSTOPPER — Requires immediate investigation**

#### New Load Being Added

| Equipment | Circuit | Notes |
|---|---|---|
| CNC 1 | 30A / 480V / 3-phase | Standard industrial CNC circuit |
| TVAC 1 | 80A / 208V / 1-phase | Requires 480V-to-208V step-down transformer |
| TVAC 2 | 80A / 208V / 1-phase | Requires 480V-to-208V step-down transformer |

#### Existing Equipment — Estimated Electrical Load Analysis

The following estimates are based on manufacturer specifications and industry-standard demand factors. **These are estimates only — actual panel schedule must be obtained for a formal NEC load calculation.**

| Equipment | Spindle Power (kW) | Est. Breaker Size (A @ 480V) | Est. Running Load at 50-60% Demand (A) |
|---|---|---|---|
| **Makino MAG 3.EX** | 130 kW | 200A | 100–125A |
| **DMG Mori CTX beta TC 4A** | ~35 kW (main) + 22 kW (mill) | 60–80A | 35–50A |
| **DMG Mori DMC 75** | ~25–35 kW | 50–60A | 25–35A |
| **DMG Mori DMU 40 PRO** (existing) | 32 kW | 40–50A | 25–30A |
| **HAAS VF-2 #1** | ~15 kW | 40–50A | 20–25A |
| **HAAS VF-2 #2** | ~15 kW | 40–50A | 20–25A |
| **HAAS VF-6** | ~22 kW | 60–80A | 30–40A |
| **Matsuura MX-850** | ~22–30 kW | 40–60A | 20–35A |
| **Matsuura MX-330 PC-10** | ~15–22 kW | 30–40A | 15–25A |
| **Building Systems** (lighting, HVAC, compressor, office, server room) | — | — | 50–80A |
| | | | |
| **Subtotal — Existing Equipment** | | **~560–670A connected** | **~340–470A running** |

**Note on connected vs. running load:** Connected load (breaker total) always exceeds service size — that is normal. NEC allows demand factors because not all machines run at peak simultaneously. What matters is the **demand load** — the realistic running load at any given time.

#### New Equipment Load

| Equipment | Circuit | Est. Running Load (A equivalent @ 480V) |
|---|---|---|
| CNC 1 (DMU 40 PRO + PH 150) | 30A / 480V / 3-phase | 15–20A |
| TVAC 1 | 80A / 208V / 1-phase (via transformer) | 50–60A equivalent |
| TVAC 2 | 80A / 208V / 1-phase (via transformer) | 50–60A equivalent |
| | | |
| **Subtotal — New Equipment** | | **115–140A running** |

#### Combined Load Assessment

| Load Category | Low Estimate (A) | High Estimate (A) |
|---|---|---|
| Existing equipment running demand | 340 | 470 |
| New equipment running demand | 115 | 140 |
| **Combined running demand** | **455** | **610** |
| **Building service capacity** | **500A** | **500A** |

**⚠️ Assessment: We are at or over capacity.** Even with conservative demand factors, the combined running load of 455–610A against a 500A service puts us in the danger zone. If the Makino is running a heavy cut while both TVACs are in operation and other machines are active, we will exceed service capacity.

#### Recommended Actions (Priority Order)

1. **IMMEDIATE (Week 1):** Obtain the actual electrical panel schedule from the existing installation. Our estimates could be off by ±20%. We need real numbers.
2. **IMMEDIATE (Week 1):** Engage a licensed electrician to perform a formal NEC Article 220 load calculation based on the actual panel schedule plus the new equipment.
3. **IMMEDIATE (Week 1):** If the load study confirms we're near or over capacity, engage with PG&E to begin the utility service upgrade process. **PG&E service upgrades can take 8–12 weeks** to schedule and complete — this becomes a critical path item that could delay the entire project.
4. **Order transformers early:** The TVAC circuits require 480V-to-208V step-down transformers. These are a long-lead procurement item — order in Week 1 upon project approval.
5. **Design for future capacity:** Pull oversized conduit and leave spare breaker positions at the panel for future equipment additions. This is dramatically cheaper to do now ($2K-$5K incremental) than to retrofit later ($15K-$30K).
6. **Consider load management:** If a service upgrade is not feasible on schedule, evaluate electrical interlocking or load shedding — e.g., prevent both TVACs from starting simultaneously, or interlock TVAC startup with Makino peak demand.
7. **Install demand monitoring:** Regardless of outcome, install a real-time power monitoring system on the main service. This gives us ongoing visibility into actual demand and prevents surprise overloads.

#### Budget Impact

- If existing service is adequate: **$30K–$45K** (transformers, circuits, conduit, panel work)
- If service upgrade required (500A → 800A or 1000A): **$45K–$65K+** (add PG&E upgrade, new main panel, larger feeders)
- Transformer procurement (2× 480V-to-208V, ~45-75 kVA each): **$8K–$15K** (included in above totals)

### 5.2 Compressed Air

**New Demand:** 3 cfm total (1 cfm per machine)

- Relatively small incremental load
- Confirm existing compressor system capacity and current utilization
- Route new air drops to each machine location
- Include filters, regulators, and lubricators (FRL units) at each drop
- CNC machines typically require clean, dry air — verify dew point and filtration requirements
- Budget for piping extensions; compressor upgrade unlikely unless system is already at capacity

### 5.3 Water / DI Water

- CNC 1 requires water for coolant mixing and potentially for through-spindle coolant
- DI (deionized) water is preferred over city water — prevents mineral buildup in coolant system and on precision surfaces
- Existing DI filter is shown on layout near the hydrostatic test area — confirm capacity to serve additional equipment
- If insufficient, install a dedicated DI system or larger unit for the CNC zone
- Route water supply lines to CNC 1 location
- Include drain provisions for coolant system maintenance

### 5.4 Liquid Nitrogen (LN2) System

This is one of the largest infrastructure items on the project.

**Demand:**
- 2 chambers × 3 gpm = 6 gpm peak LN2 flow
- Usage pattern TBD (continuous vs. intermittent test cycles) — this affects bulk tank sizing

**Proposed System:**
- **Exterior Bulk Tank:** 1,500 – 3,000 gallon vacuum-insulated cryogenic storage tank
  - Located outside the building on a dedicated concrete pad
  - Sized for approximately 1-week delivery cycle (adjust based on actual consumption profile)
  - Must comply with CGA, NFPA, and local fire code for setback distances from building, property lines, and ignition sources
  - Delivery truck access required — confirm turnaround space for LN2 tanker
- **Distribution Piping:** Vacuum-insulated pipe from exterior tank to each TVAC chamber location
  - Phase separator and pressure regulation at distribution point
  - Individual isolation valves at each chamber
  - Relief valves on all sections where LN2 can be trapped between two valves
- **Safety Systems (see Section 6)**

### 5.5 HVAC / Thermal Control

**Requirements:**
- Makino MAG 3.EX: **70°F ±2°F** (hard requirement from prompt)
- DMU 40 PRO (CNC 1): 5-micron positioning accuracy — thermal stability is critical. Recommend same ±2°F standard.
- Raw material storage: **Must be co-located in the same conditioned space** as the CNC machines. Material brought in from outside at ambient temperature will expand or contract during machining, causing dimensional drift at these tolerances.

**Challenge:**
- Building is bare metal with no insulation and 50 feet tall — enormous volume to condition
- San Francisco microclimate at Pier 70 (fog, sun, wind off the bay) creates temperature swings
- TVAC chambers introduce localized thermal loads (both hot and cold cycling)

**Proposed Approach:**
- **Option A (Preferred):** Create a thermally controlled enclosure/zone around the entire CNC cluster and adjacent material storage. Insulated walls/ceiling within the larger building, with dedicated precision HVAC units maintaining ±2°F. This is more cost-effective than conditioning the entire 50-foot-tall building.
- **Option B:** Full building insulation + HVAC. More expensive, but benefits all operations.
- **Decision Point:** Need leadership input on scope and budget tolerance

**Budget Impact:** This is one of the largest variable cost items ($50K–$120K+)

### 5.6 CNC Support Systems — Coolant, Chips, Waste

**Coolant System:**
- Water-soluble coolant mixing station (DI water + coolant concentrate)
- Coolant supply and return plumbing to CNC 1
- Coolant tank/sump at machine (likely integrated with DMU 40 PRO)
- Spent coolant collection drums with secondary containment
- Tramp oil separator — keeps way oil and hydraulic oil out of the coolant
  - Check if DMU 40 PRO has integrated skimmer; if not, need standalone coalescing separator
  - Different styles available: belt skimmers, disk skimmers, coalescers — select based on coolant type and flow

**Chip Management:**
- Chip conveyor (likely integrated with machine — confirm)
- **Segregated chip collection bins** — critical requirement:
  - Separate bins for each material type (aluminum, steel, stainless, titanium, etc.)
  - Mixed chips contaminate recycling and can cause quality issues
  - Label and color-code bins
  - Designate floor space near CNC zone for chip bins
- Chip handling PPE (gloves, eye protection — chips are sharp and may be hot)

**Spill Containment:**
- Spill kits staged at CNC zone and at each TVAC location
- Secondary containment under coolant drums/tanks
- Floor drains: verify if existing; if so, confirm they do NOT connect to storm drain (environmental violation)

### 5.7 Foundations & Structural

**⚠️ HIGH-PRIORITY CONCERN — On the critical path for the entire project**

#### The Problem

This building sits on Pier 70 — a historic waterfront pier originally constructed for shipbuilding (Union Iron Works / Bethlehem Steel). The pier's substructure is fundamentally different from a standard industrial slab-on-grade on solid ground.

**What we know:**
- 4" concrete slab throughout the building
- Pier substructure is likely timber piles and/or concrete piles driven into bay mud, with fill material and a concrete cap
- Building was originally designed for heavy industrial use (shipbuilding), which is a potential positive — the slab may be more robust than the 4" specification suggests in certain areas
- We are installing a CNC machine that holds **5-micron positioning accuracy** and TVAC chambers that may weigh **10,000–20,000+ lbs each**

#### Why This Matters for the CNC

To put 5 microns in perspective: that is roughly **1/15th the diameter of a human hair**. At this tolerance level, the machine bed must be dead flat, dead stable, and isolated from vibration sources.

The DMU 40 PRO has a one-piece gray cast iron bed and direct-driven ball screws specifically engineered for rigidity — but that rigidity assumes the floor underneath is not moving. On a pier structure, we face:

- **Micro-settling** under concentrated loads as the subgrade compresses or shifts
- **Vibration transmission** from the waterfront environment (tidal movement, wind loading on the structure, vehicle traffic on adjacent streets/piers) and from other equipment through the structure
- **Long-term drift** in floor levelness as the pier structure ages and shifts seasonally
- **Seismic vulnerability** — San Francisco is in a high seismic zone; even minor seismic events can shift machine leveling

The Makino MAG 3.EX specification sheet confirms this concern: Makino requires environmental conditions including a **"suitable industrial floor for machine stability"** to achieve quoted accuracies. A standard 6" slab on grade is their baseline — our 4" slab on a pier is below that standard.

#### Why This Matters for the TVACs

TVAC chambers don't care about microns — but they are extremely heavy. A Rigel-class chamber in the 10-12 ft range, with pumping system, thermal control unit, and platen, could weigh 10,000–20,000+ lbs. This creates:

- **Concentrated point loads** on the slab through the chamber's support feet
- **Dynamic loading** during door operation (the full-opening door on a large chamber is heavy and shifts the center of gravity when open)
- **Potential for differential settlement** if the subgrade is not uniform at the chamber location

#### Recommended Actions

**Step 1 — Structural/Geotechnical Assessment (WEEK 1 — CRITICAL PATH)**

Engage a licensed structural engineer (PE) with experience in waterfront/pier structures or Pier 70 specifically. The scope should include:

1. **Slab evaluation** — Thickness, reinforcement schedule, condition, and load capacity at each proposed machine location. Non-destructive testing (GPR or coring) to verify actual reinforcement.
2. **Substructure assessment** — What is beneath the slab? Timber piles, concrete piles, fill, bay mud? Has it been upgraded or reinforced by previous tenants?
3. **Point-load analysis** — Can the slab support the concentrated loads from each machine at the proposed locations? Calculate safety factors.
4. **Floor flatness and levelness survey** — Measure the slab surface at proposed machine locations per ASTM E1155 (FF/FL numbers). CNC machines require flat, level surfaces.
5. **Ambient vibration survey** — Rent accelerometers and measure ambient vibration levels at proposed CNC locations over a 24-48 hour period. This captures vibration from other machines, building systems, and environmental sources (traffic, wind, tidal). Compare results to DMG Mori's installation requirements.

**Step 2 — Foundation Design (Based on Assessment Results)**

Most likely we will need one or more of the following, depending on findings:

| Solution | When Used | Est. Cost |
|---|---|---|
| **Epoxy grout leveling pads** | Slab is structurally adequate but surface is not flat/level enough | $3K–$8K |
| **Vibration-isolating machine mounts** | Ambient vibration exceeds CNC tolerance; used with or without new pads | $5K–$12K |
| **Reinforced machine pads** (for TVACs) | Slab cannot support point loads at TVAC locations; pour reinforced concrete pads on existing slab | $8K–$20K |
| **Isolated machine foundations** (for CNC) | Slab vibration or settling is unacceptable; pour independent concrete pads decoupled from building slab with vibration isolation joints | $15K–$30K |
| **Micro-piled foundations** | Worst case — subgrade is inadequate; install steel micro-piles through the slab to bearing stratum, then pour machine pad on top | $30K–$60K+ |

**Step 3 — Ongoing Monitoring**

After installation, establish a periodic leveling check schedule for the CNC machines (quarterly recommended for the first year). Precision CNC machines require periodic releveling as foundations settle.

#### The Upside

There is a potential upside to the Pier 70 history. This building was constructed for **shipbuilding** — one of the heaviest industrial uses imaginable. The original builders may have designed the slab and substructure for loads far exceeding what modern CNC machines and TVAC chambers impose. The structural assessment may reveal that the existing structure is more robust than the 4" slab specification suggests — it may have been poured thicker or with heavier reinforcement in certain bays. Historic construction drawings, if available from the Port of San Francisco or Pier 70 development archives, would be extremely valuable.

#### Budget Impact

Foundation work is the **largest cost unknown** in this project:
- **Best case:** Slab is adequate, needs only grouting and leveling — **$10K–$15K**
- **Mid case:** Need isolated CNC pad + reinforced TVAC pads — **$25K–$40K**
- **Worst case:** Need micro-piled foundations for CNC + reinforced pads for TVACs — **$50K–$60K+**

The structural assessment (estimated cost: $5K–$10K for the PE engagement) tells us which scenario we're in. This assessment is **the single highest-priority action item** on the project because:
1. Foundation design cannot begin without it
2. Foundation pour requires cure time (minimum 7-14 days to adequate strength, 28 days to full strength)
3. No machine can be placed until the foundation is ready
4. CNC 1 arrives in **2 weeks** — if we need foundation work, we are already behind

---

## 6. Safety & Compliance

### 6.1 LN2 / Oxygen Depletion Safety

Liquid nitrogen expands approximately 695:1 when vaporizing. A leak in an enclosed space can rapidly displace breathable oxygen, causing asphyxiation with no warning (N2 is odorless and colorless).

**Required Systems & Protocols:**
- Continuous O2 monitoring at each TVAC chamber location and along LN2 piping routes
  - Alarm at 19.5% O2 (OSHA action level)
  - Audible AND visual alarms
  - Recommend integration with building alarm/PA system
- Emergency ventilation — ability to rapidly increase air exchange in TVAC areas
  - Evaluate whether existing 4 roof exhaust fans are sufficient
  - May need dedicated exhaust near floor level (N2 is heavier than heated air but mixes rapidly)
- LN2 handling PPE station near chambers: cryogenic gloves, face shield, safety shoes, long-sleeve protection
- LN2 safety training for all personnel (not just TVAC operators)
- Emergency procedures posted at each TVAC location and at LN2 bulk tank
- Safety signage per OSHA and NFPA requirements
- LN2 bulk tank area: fenced/restricted access, proper setbacks from building, emergency shower/eyewash if required by local code

### 6.2 Hazardous Waste

**California Requirements:**
- Obtain **Cal/EPA Hazardous Waste Generator ID Number** (DTSC)
  - If Astranis already has one, verify it covers this facility/activity
  - If not, apply before generating any regulated waste
- Waste streams to manage:
  - Spent metalworking coolant (may be hazardous depending on formulation and contaminants)
  - Tramp oil / waste oil
  - Metal chips contaminated with coolant (may need characterization)
  - LN2-related waste: minimal, but check for any chamber cleaning chemicals or vacuum pump oil
- Proper waste labeling, storage (90-day accumulation rule), and manifested disposal
- Annual hazardous waste reporting to DTSC

### 6.3 Permits

**Expected Permits Required:**
- **Building Permit** — City of San Francisco Department of Building Inspection (DBI) for equipment installation, structural modifications, and electrical work
- **Electrical Permit** — Required for all new circuits, panel modifications, transformer installation
- **Mechanical Permit** — Potentially required for HVAC modifications, compressed air, LN2 piping
- **Fire Department Review** — LN2 storage and cryogenic systems may trigger SFFD review
- **Historical/Environmental** — Pier 70 is a historic site; confirm whether any modifications require historic preservation review
- **Air Quality / BAAQMD** — Bay Area Air Quality Management District — confirm whether TVAC vacuum pump exhaust or any process emissions require a permit
- **DTSC** — Hazardous waste generator registration (see above)

**Action Required:** Engage with SF DBI early to identify all required permits and review timelines — SF permitting can be slow and this may be a schedule-critical path item.

### 6.4 Shipping, Receiving & Rigging Access

- Confirm building entry points: roll-up doors, door dimensions, clear height
- Confirm that equipment can physically fit through building openings
  - Rigel TVAC chambers (8–16 ft diameter) — may require disassembly or special entry path
  - CNC 1 with PH 150 — relatively compact but still requires forklift/crane for placement
- Verify floor can support temporary concentrated loads during rigging (equipment + rigging equipment)
- Plan staging area for equipment that arrives before site is ready
- Confirm truck access for LN2 tanker deliveries (turning radius, overhead clearance, pad location)

---

## 7. Project Timeline

### Phase Overview

The project has two parallel workstreams driven by equipment delivery dates:

**Track A — CNC 1 (2-week delivery)**
- This is the aggressive path. Site prep must begin immediately.
- If site is not ready at delivery, machine must be staged (covered, climate-controlled) until installation can occur.

**Track B — TVAC 1 & 2 (2-month delivery)**
- More lead time, but infrastructure is more complex (LN2 system, electrical transformers, safety systems)
- Long-lead items (bulk LN2 tank, vacuum-insulated piping, transformers) should be ordered immediately

### Proposed Phasing

| Phase | Duration | Activities |
|---|---|---|
| **Phase 0: Engineering & Permitting** | Weeks 1–3 | Structural assessment, electrical load study, detailed engineering drawings, permit applications, long-lead procurement (LN2 tank, transformers, HVAC units) |
| **Phase 1: Site Prep — CNC Zone** | Weeks 2–4 | Foundation work (if needed), electrical rough-in for CNC 1, compressed air extension, DI water routing, coolant system prep |
| **Phase 2: CNC 1 Installation** | Weeks 3–4 | Rigging, placement, leveling, utility connections, DMG Mori commissioning |
| **Phase 3: Site Prep — TVAC Zone** | Weeks 3–8 | Foundation work, electrical (transformers + circuits), LN2 bulk tank pad and installation, LN2 piping, vacuum pump exhaust, O2 monitoring system |
| **Phase 4: HVAC / Thermal Enclosure** | Weeks 4–8 | Build thermal enclosure around CNC zone (can parallel TVAC prep) |
| **Phase 5: TVAC Installation** | Weeks 8–10 | Rigging, placement, LN2 hookup, electrical connections, vacuum system commissioning, Dynavac startup service |
| **Phase 6: Commissioning & Validation** | Weeks 10–12 | Full system testing, safety system validation, O2 monitor calibration, operator training, as-built documentation |

**Critical Path Items:**
- Structural assessment → foundation design → foundation pour → cure time → machine placement
- Permit approval timeline (SF can be unpredictable)
- LN2 bulk tank procurement and delivery lead time
- Transformer procurement

### Labor Requirements

| Trade | Estimated Duration | Notes |
|---|---|---|
| Structural Engineer (PE) | 1–2 weeks | Assessment, foundation design, stamped drawings |
| Electrician (licensed) | 3–4 weeks (intermittent) | Panel work, conduit, circuits, transformer install |
| Plumber / Pipefitter | 2–3 weeks | Compressed air, DI water, coolant lines |
| Cryogenic Contractor | 2–3 weeks | LN2 tank install, vacuum-insulated piping, controls |
| HVAC Contractor | 2–4 weeks | Thermal enclosure, precision HVAC units |
| Concrete / Foundation | 1–2 weeks | Machine pads if needed (plus cure time) |
| Rigging Crew | 3–5 days total | CNC 1 placement + TVAC 1 & 2 placement (separate mobilizations) |
| Fire Alarm / Safety Systems | 1 week | O2 monitors, alarms, signage |
| General Contractor / Coordination | Throughout | Overall project management, scheduling, inspections |

---

## 8. Budget Estimate

**Estimate Basis:** Mid-level accuracy. Rolled up by category. Based on industry benchmarks, equipment specifications, and San Francisco labor/material costs. Does NOT include the cost of the machines themselves (assumed already procured).

| Category | Low Estimate | High Estimate | Notes |
|---|---|---|---|
| **Site Prep & Foundations** | $25,000 | $60,000 | Highly variable — depends on structural assessment results |
| **Rigging & Equipment Placement** | $15,000 | $35,000 | 3 machines, 2 mobilizations, crane rental if needed |
| **Electrical** | $30,000 | $65,000 | Includes transformers for 208V, conduit, circuits, panel work. Higher end if service upgrade needed. |
| **Compressed Air** | $8,000 | $20,000 | Piping extensions, FRL units. Higher if compressor upgrade needed. |
| **DI Water / Plumbing** | $5,000 | $15,000 | DI system upgrade, water lines to CNC zone, drain provisions |
| **LN2 System** | $80,000 | $150,000 | Bulk tank, vacuum-insulated piping, controls, O2 monitoring, concrete pad |
| **HVAC / Thermal Control** | $50,000 | $120,000 | Highest variability — depends on enclosure scope vs. full building |
| **Coolant, Chip & Waste Systems** | $10,000 | $25,000 | Coolant mixing station, chip bins, tramp oil separator, containment |
| **Safety & Compliance** | $8,000 | $20,000 | Spill kits, signage, PPE stations, HazWaste registration, fire review |
| **Permits & Engineering** | $15,000 | $35,000 | Structural PE, MEP engineering, SF building/electrical/mechanical permits |
| **Contingency (15%)** | $37,000 | $82,000 | Standard contingency for industrial construction projects |
| | | | |
| **TOTAL ESTIMATED RANGE** | **$283,000** | **$627,000** | |

**Key Budget Drivers (what moves us from low to high):**
1. Foundation work — minor grouting vs. isolated pads with vibration isolation
2. HVAC scope — localized enclosure vs. larger-scale thermal control
3. Electrical — adequate existing capacity vs. utility service upgrade required
4. LN2 system — smaller tank with simpler piping vs. large tank with complex distribution

---

## 9. Risks & Mitigation

### Risk #1: Electrical Capacity Insufficient

**Risk:** Our preliminary load analysis estimates combined running demand at 455–610A against a 500A/480V building service. The existing 8+ CNC machines (particularly the 130 kW Makino MAG 3.EX), building systems, and compressors likely consume 340–470A before the new equipment is added. Adding the new CNC and two TVACs pushes us to or beyond service capacity.

**Impact:** HIGH — If a utility service upgrade is required, PG&E scheduling alone can take 8–12 weeks. Combined with equipment procurement (new main panel, larger feeders, transformer), this could delay the entire project by 2–3 months. Estimated cost of a service upgrade: $15K–$40K+.

**Mitigation:**
- **IMMEDIATE:** Obtain actual panel schedule and perform formal NEC Article 220 load calculation (Week 1)
- Engage with PG&E proactively — even before the load study is complete, initiate a conversation about potential upgrade timelines
- Design new circuits with energy-efficient practices (VFDs, power factor correction)
- Evaluate load shedding / electrical interlocking as a contingency if service upgrade cannot be completed on schedule (e.g., prevent both TVACs from starting simultaneously with Makino at peak demand)
- Pull oversized conduit and leave spare breaker positions for future growth — this is dramatically cheaper now than retrofit later
- Budget contingency for service upgrade in all project scenarios

### Risk #2: Foundation / Structural Inadequacy at Pier 70

**Risk:** The building sits on a historic waterfront pier with a 4" concrete slab over what is likely timber piles and fill — not slab-on-grade on solid ground. The DMU 40 PRO requires 5-micron positioning accuracy, which demands a dead-flat, vibration-free foundation. TVAC chambers weighing 10,000–20,000+ lbs create concentrated point loads the slab may not support. Ambient vibration from the waterfront environment (tidal, wind, traffic) may exceed CNC tolerance thresholds.

**Impact:** HIGH — Foundation remediation (isolated pads, micro-piles) could add $30K–$60K+ to the budget and 3–4 weeks to the schedule. If discovered late — after the CNC arrives in 2 weeks — the machine sits idle while we pour and cure foundations, at significant cost to production.

**Mitigation:**
- **IMMEDIATE:** Commission structural/geotechnical assessment in Week 1 — this is the single highest-priority action item because foundation design, pour, and cure time are on the critical path for CNC 1 installation
- Include ambient vibration survey (24-48 hours of accelerometer data) at proposed CNC locations
- Request historic construction drawings from Port of San Francisco / Pier 70 development archives — the original shipbuilding use may mean the slab is more robust than the 4" specification suggests
- Budget for worst-case foundation work in contingency ($50K–$60K)
- Design all machine mounting systems with adjustable leveling and vibration isolation as standard practice
- Identify backup machine locations in case preferred locations have structural deficiencies
- Establish post-installation leveling check schedule (quarterly for first year) to monitor for settling

### Risk #3: San Francisco Permitting Delays

**Risk:** SF building permits, electrical permits, and fire department review can take weeks to months. Historical site status of Pier 70 may add additional review requirements.

**Impact:** MEDIUM-HIGH — Permit delays directly impact project timeline, especially for the CNC 1 track (2-week delivery).

**Mitigation:**
- Submit permit applications in Week 1 — do not wait for final engineering
- Engage an expediter familiar with SF DBI processes
- Confirm whether Pier 70 has any blanket permits or streamlined review process for tenant improvements
- Identify which work can proceed without permits (planning, procurement, staging) vs. what requires permit-in-hand
- Plan for CNC 1 to be staged (stored on-site, protected) if site prep is not complete at delivery

### Additional Risks to Monitor

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| LN2 tank lead time exceeds 8 weeks | Medium | Schedule slip for TVAC | Order immediately upon project approval |
| Transformer lead time | Medium | Delays TVAC electrical | Source from stock vs. custom; order Week 1 |
| Existing compressed air at capacity | Low | Minor cost/schedule impact | Survey compressor capacity early |
| Worker safety incident during LN2 install | Low | High (injury + regulatory) | Qualified cryogenic contractor only; safety plan |
| Rigging access blocked by existing equipment | Low | Schedule impact | Survey rigging path before ordering move |

---

## 10. Open Questions for Leadership & Production

### For Leadership / Management

1. **Budget authority:** Is there a target budget ceiling, or are we building a bottom-up estimate for approval?
2. **Schedule priority:** If CNC 1 arrives before site prep is complete, is staging acceptable? Or is "running on day one" the expectation?
3. **HVAC scope decision:** Do we invest in a full thermal enclosure for the CNC zone (recommended for 5-micron work), or attempt localized solutions? This is a $50K–$120K swing.
4. **Existing permits / lease terms:** Are there any existing blanket permits, landlord restrictions, or lease provisions that govern modifications at Pier 70?
5. **Historical preservation:** Does the Pier 70 historic status impose any constraints on structural modifications or exterior equipment (LN2 tank)?

### For Production Area Owners

6. **Yellow highlighted area on layout:** Is this the designated new/unused build-out zone? Confirm boundaries.
7. **Machine placement flexibility:** How firm are the suggested locations? Are there alternative locations we should evaluate?
8. **TVAC usage pattern:** Will both chambers run simultaneously? Continuously or intermittent test cycles? This drives LN2 tank sizing and delivery frequency.
9. **CNC 1 materials:** What materials will CNC 1 primarily machine? (Drives chip segregation plan, coolant type, and thermal stability requirements)
10. **Future equipment plans:** Are any additional machines planned in the next 12–24 months? Should we size infrastructure (electrical, air, LN2) for future growth?
11. **Rigging access:** Where are the roll-up doors / equipment entry points? What is the clear height and width?
12. **Existing compressed air system:** What compressor(s) are installed, what is their CFM rating, and what is current utilization?
13. **Existing DI water system:** What is the capacity of the current DI filter shown on the layout?
14. **Shift pattern:** What hours/shifts do the 10 full-time workers operate? (Affects when hot work and noisy construction can occur)

### For Safety / EHS

15. **Existing HazWaste ID:** Does Astranis already have a Cal/EPA Hazardous Waste Generator ID number?
16. **Existing EHS program for cryogenics:** Is this the first LN2 installation, or is there existing infrastructure/training?
17. **Fire suppression:** What fire suppression system is installed? Will it need modification for the new equipment zones?
18. **Floor drains:** Are there existing floor drains in the machine shop? Where do they discharge? (Critical for spill containment planning)

### For Engineering / Facilities

19. **Electrical panel schedule:** Can we obtain the existing panel schedule to perform a load analysis?
20. **Tramp oil separator:** Does the DMU 40 PRO come with an integrated tramp oil separator, or do we need a standalone unit?
21. **Accessories / PH 150 footprint:** Confirm the exact footprint of the DMU 40 PRO + PH 150 together, including service clearances per DMG Mori's installation guide.
22. **TVAC exact size:** Confirm the specific Rigel model/size ordered (8 ft, 10 ft, 12 ft, 16 ft?) — this drives floor space, structural loading, and door swing clearance.

---

## 11. Assumptions

### Provided Assumptions (from prompt)

- 500A @ 480V electrical service to the building
- Building construction is bare metal exterior with no wall insulation, 4" thick concrete slab throughout
- Building is roughly 50 feet tall with four exhaust fans on the roof
- Each TVAC chamber requires: 80A/208V single phase, 3 gpm LN2, 1 cfm compressed air
- Each CNC machine requires: 30A/480V three phase, 1 cfm compressed air
- Makino MAG 3.EX requires 70°F ±2°F temperature range
- 10 people work in the building full time

### Our Additional Assumptions

- All existing equipment and layout items (except the 3 new machines) are **fixed in place** and cannot be relocated
- The machines (CNC 1, TVAC 1, TVAC 2) have been procured / are on order — this project covers installation infrastructure only
- Astranis has (or will designate) a project manager to coordinate between facilities, production, and contractors
- Standard San Francisco union labor rates and prevailing wage may apply (depending on project value and lease terms)
- No overhead crane is available in the building (rigging will use forklifts, dollies, or rented crane)
- Building has standard industrial compressed air system in place (to be verified)
- DI water system exists on-site (to be verified for capacity)
- LN2 will be sourced from a commercial gas supplier (e.g., Airgas, Linde, Air Liquide) with bulk tanker delivery
- San Francisco permitting timeline assumed at 4–6 weeks (could be longer for historical site review)
- No asbestos, lead paint, or other environmental hazards present in the work areas (historic building — should be confirmed)

---

## 12. Presentation Outline

**Target:** ~18 slides, 45-minute presentation, polished for leadership audience

| Slide # | Title | Content | Time |
|---|---|---|---|
| 1 | Title Slide | Project name, Astranis branding, date, presenter | 0.5 min |
| 2 | Executive Summary | Scope, timeline, budget range, 3 key decisions needed | 2 min |
| 3 | Facility Context | Pier 70 overview, building constraints, what we're working with | 3 min |
| 4 | Current Layout Overview | Annotated floor plan showing existing equipment and proposed locations | 3 min |
| 5 | Machine Placement: CNC 1 | Proposed location, rationale, adjustments, clearance diagram | 3 min |
| 6 | Machine Placement: TVAC 1 & 2 | Proposed locations, rationale, safety considerations, any relocation recommendations | 3 min |
| 7 | Infrastructure: Electrical | Load analysis, panel upgrades, circuit routing, transformer needs, future capacity | 3 min |
| 8 | Infrastructure: Compressed Air & Water | Air system, DI water routing, capacity check | 2 min |
| 9 | Infrastructure: LN2 System | Bulk tank design, piping, safety systems, O2 monitoring | 3 min |
| 10 | Infrastructure: Thermal/HVAC | Climate-controlled CNC zone, material co-location, Makino ±2°F, options A vs B | 3 min |
| 11 | Infrastructure: CNC Support Systems | Coolant, chip management, tramp oil, waste streams, DI water | 2 min |
| 12 | Infrastructure: Foundations & Structural | Slab assessment, vibration isolation, Pier 70 concerns | 2 min |
| 13 | Safety & Compliance | HazWaste ID, spill containment, LN2 safety, permits, Cal/OSHA | 2 min |
| 14 | Project Timeline | Gantt chart, two parallel tracks, critical path, labor requirements | 3 min |
| 15 | Budget Summary | Rolled up by category with ranges | 3 min |
| 16 | Risk #1: Electrical Capacity | Description, impact, mitigation | 2 min |
| 17 | Risk #2: Foundation/Structural + Risk #3: Permitting | Combined or split depending on flow | 2 min |
| 18 | Questions, Assumptions & Next Steps | Consolidated question list, key assumptions, decisions needed from leadership | 3 min |

**Total: ~45 minutes** (includes buffer for discussion — risk and budget slides tend to generate questions)

---

## 13. Change Log

| Date | Author | Change Description |
|---|---|---|
| 2026-03-13 | Facilities Director | Initial draft — compiled from research and planning discussions |
| 2026-03-13 | Facilities Director | **Major update:** Added detailed machine placement recommendations (CNC 1 approved with adjustments, TVAC 1 approved, TVAC 2 relocation recommended). Added full electrical load analysis with per-machine breakdown showing 455-610A demand vs 500A service — flagged as potential showstopper. Added comprehensive foundation/structural analysis for Pier 70 pier substructure including vibration concerns, remediation options with cost estimates, and critical path implications. Added Immediate Action Items section. |
| | | |

---

*This document is a living working file. Please annotate, comment, and update as new information becomes available. All sections marked with ⚠️ or [TBD] require resolution before the final presentation can be completed.*
