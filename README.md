# CAD-Projects
Documenting my CAD projects and drawings in both SolidWorks and Fusion 360
# CAD Projects

Self-directed SolidWorks and CAD work as part of my Applied Manufacturing
Engineering studies (Automation & Robotics concentration).

---

## NEMA-17 Stepper Motor Mount L-Bracket

An L-bracket designed in SolidWorks to mount a NEMA-17 stepper motor,
with all dimensions driven by the motor's manufacturer datasheet.

### Purpose
Brackets like this hold a stepper motor to a frame or panel. The point of
the project was to design to a *real component's* constraints — every key
dimension is traceable to the NEMA-17 specification, not chosen arbitrarily.

### Design decisions (datasheet-driven)
| Feature | Value | Reason |
|---|---|---|
| Bolt pattern | 31 mm square | Matches the NEMA-17 mounting standard |
| Mounting holes | 4 × Ø3.4 mm through | Clearance fit for M3 screws (assembly + alignment) |
| Center bore | Ø23 mm | Clears the motor's Ø22 mm pilot boss (1 mm clearance) |
| Material | 6061 aluminum | Light, stiff enough for a small motor, machinable, low cost |
| Bend | R3 radius | Avoids a sharp internal corner (stress + manufacturability) |

### Verification
- Confirmed the 4-hole pattern is a 31 mm square centered on the bore
  (measured against the bore center; sketch fully defined).
- Verified bore Ø23 and holes Ø3.4 against the design intent.

### Deliverables
- 3D part model (.sldprt)
- Fully-dimensioned manufacturing drawing (.slddrw and PDF) with
  orthographic views, an isometric, and a title block.

### Known limitations
- The drawing is fully dimensioned but does **not** yet include GD&T
  (datum references / positional tolerance on the bolt pattern). GD&T is a
  current learning target; a v2 of this drawing with a positional tolerance
  on the hole pattern (bore as datum) is planned.
- Designed and verified in CAD; not yet produced on physical hardware.

<img width="1280" height="720" alt="NEMA-17 motor L Bracket drawing design" src="https://github.com/user-attachments/assets/361994d3-aa22-4195-9cb0-479c4dc834a7" />
<img width="1280" height="720" alt="NEMA-17 motor L Bracket design" src="https://github.com/user-attachments/assets/28d64d96-0449-45e0-904d-8aaa5b1c42fd" />
