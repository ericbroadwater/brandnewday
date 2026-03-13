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
- **Concern:** The existing CNC machines represent a significant electrical load. Before adding new equipment, a load analysis is required to determine remaining capacity. The Makino MAG 3.EX alone may draw 60-100A.

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

**Preliminary recommendation: Generally agree with suggested location, with adjustments.**

Rationale:
- Clustering CNC machines together makes sense for shared infrastructure (compressed air, coolant, DI water, chip management)
- Proximity to existing CNC zone enables a unified thermal control enclosure covering all precision machines
- Close to raw material storage — critical for thermal equilibrium of stock before machining
- Close to Q.C. Lab for quick inspection turnaround

**Proposed adjustments:**
- Ensure minimum 36" clearance on all sides, with expanded clearance on PH 150 pallet load/unload side
- Orient machine for optimal rigging path from building entry
- Verify slab adequacy at this specific location; may need isolated machine pad
- Plan for chip conveyor routing to a central chip collection point
- Co-locate raw material storage within the same thermal zone — material must stabilize to room temperature before machining to maintain 5-micron tolerances

### TVAC 1 Placement Assessment

**Preliminary recommendation: [TO BE FINALIZED]**

Key considerations:
- Proximity to exterior wall preferred for LN2 piping runs and vacuum pump exhaust
- Need clear rigging path for chamber installation
- Need space for door to fully open and test article loading
- Must not block egress routes

### TVAC 2 Placement Assessment

**Preliminary recommendation: Consider relocating closer to an exterior wall.**

Concerns with current suggested location:
- Deep interior placement near the kitchen and occupied areas raises LN2 safety concerns
- Longer LN2 piping runs increase cost and thermal losses
- Vacuum pump exhaust routing more complex from interior
- In an O2 depletion event, an interior location is harder to ventilate

**Alternative locations to evaluate:**
- [TBD — need to assess available space along exterior walls]

### ⚠️ Open Item
- The "yellow highlighted" area on the layout appears to represent the new/unused build-out zone — this needs confirmation from the production team.

---

## 5. Infrastructure Design

### 5.1 Electrical

**New Load Being Added:**

| Equipment | Circuit | Notes |
|---|---|---|
| CNC 1 | 30A / 480V / 3-phase | Standard industrial CNC circuit |
| TVAC 1 | 80A / 208V / 1-phase | Likely requires 480V-to-208V step-down transformer |
| TVAC 2 | 80A / 208V / 1-phase | Likely requires 480V-to-208V step-down transformer |

**Total New Load:** ~190A equivalent (varies with duty cycle and power factor)

**Concern:** Building has 500A @ 480V total service. Existing machines (8+ CNC machines, compressors, HVAC, lighting, etc.) likely consume 250-350A+. Adding 190A of new load may push us near or over capacity.

**Action Required:**
- Obtain existing panel schedule and perform full electrical load calculation
- Engage licensed electrician for load study
- If over capacity: budget for utility service upgrade ($15K–$40K+ per industry estimates)
- Recommend pulling oversized conduit and leaving spare breaker positions for future equipment additions — cheaper to do now than retrofit later
- All circuits in rigid metallic conduit (RMC) or intermediate metallic conduit (IMC) per industrial standards
- Transformer(s) needed for 480V → 208V conversion for TVAC circuits

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

**⚠️ HIGH-PRIORITY CONCERN**

**The Issue:**
- Building is on Pier 70 — a historic waterfront pier
- 4" concrete slab is relatively thin for precision machinery
- Pier substructure (likely timber piles and fill) may not provide the vibration isolation and settlement stability required for 5-micron CNC machining
- Heavy TVAC chambers add concentrated point loads

**Proposed Actions:**
1. **Structural/geotechnical assessment** — Engage a licensed structural engineer to evaluate:
   - Slab thickness and reinforcement at proposed machine locations
   - Subgrade/substructure conditions (what's under the slab?)
   - Floor flatness and levelness
   - Point load capacity for each machine
   - Vibration characteristics (ambient vibration survey recommended)
2. **Potential Remediation:**
   - Isolated machine foundations (independent concrete pads decoupled from the building slab)
   - Vibration-dampening machine mounts (elastomeric or pneumatic isolators)
   - Epoxy grout for precision leveling
   - For extreme cases: micro-piled foundations beneath machine pads
3. **Budget Impact:** Foundation work is a major cost variable — could range from $10K (minor grouting and leveling) to $60K+ (isolated pads with vibration isolation)

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

**Risk:** The building's 500A/480V service may not have enough remaining capacity to support the new equipment, especially given 8+ existing CNC machines and building systems already on the panel.

**Impact:** HIGH — Could delay the entire project if a utility service upgrade is required (long lead time, high cost, utility company coordination).

**Mitigation:**
- Perform electrical load study immediately (Week 1 priority)
- Engage with PG&E early if upgrade may be needed
- Design new circuits with energy-efficient practices (VFDs, power factor correction)
- Phase equipment startup to avoid simultaneous peak demand
- Budget contingency for service upgrade ($15K–$40K)

### Risk #2: Foundation / Structural Inadequacy at Pier 70

**Risk:** The 4" concrete slab on a historic pier may not provide adequate vibration isolation, settlement stability, or point-load capacity for 5-micron CNC machining and heavy TVAC chambers.

**Impact:** HIGH — Could require extensive and expensive remediation (isolated pads, micro-piles), and if discovered late, would cause major schedule delays.

**Mitigation:**
- Commission structural/geotechnical assessment before any other work begins
- Include vibration survey (ambient measurement) at proposed machine locations
- Budget for worst-case foundation work in contingency
- Design machine mounting systems with adjustable leveling and vibration isolation as standard
- Identify backup machine locations if preferred locations have structural issues

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
| | | |
| | | |

---

*This document is a living working file. Please annotate, comment, and update as new information becomes available. All sections marked with ⚠️ or [TBD] require resolution before the final presentation can be completed.*
