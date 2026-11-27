# M701 · Unsorted

Ward-Beck Systems M701, 1978|11. Wiki page: [M701 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M701.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 12 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 0 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 0 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 0 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 3 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [2 topics](FORUM.md): what owners and technicians said about it.

<!-- /module data -->

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

Not on Google Drive yet: `1978 - 701-02-101 - M701B INTERCOM PRE-AMPLIFIER SCHEMATIC - DRN MRW - ENG MRW - ISS 12.jpg`, `1978 - 701-02-101 - M701B INTERCOM PRE-AMPLIFIER SCHEMATIC - DRN MRW - ENG MRW - ISS 2.png`, `1979 - 701-01-011 - INTERCOM PREAMPLIFIER FUNCTIONAL DIAGRAM - DRN P. Mahoney - ISS 2.jpg`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- polarity assumed: 4 contacts given + / − that the drawing does not mark (e.g. P1-21 SPEAKER OUTPUT) (M703: 1977 - M703 - B 703-02-001 - INTERCOM 701, 702, 703 INPUT OUTPUT AMP PIN CONNECTIONS &amp; STRAPPING.jpg)

**Inserts:** PRE OUT / POWER AMP IN: PRE OUTPUT → POWER AMP INPUT

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +24..36 V UNREG | power |  | medium |
| 3 | MIC INPUT A | in | MIC INPUT | medium |
| 4 | MIC INPUT B | in | MIC INPUT | medium |
| 5 | MIC SHIELD | shield | MIC INPUT shield | medium |
| 6 | CARBON MIC SUPPLY STRAP | strap |  | medium |
| 7 | MIC STRAP | strap |  | medium |
| 8 | PRE OUTPUT A | insert_send | PRE OUTPUT | medium |
| 10 | COMMON (-C) | ground |  | medium |
| 13 | +24..36 V UNREG | power |  | medium |
| 16 | POWER AMP INPUT SHIELD | shield | POWER AMP INPUT shield | medium |
| 17 | POWER AMP INPUT A | insert_return | POWER AMP INPUT | medium |
| 18 | POWER AMP INPUT B | insert_return | POWER AMP INPUT | medium |
| 19 | MUTE | control_in | MUTE | medium |
| 21 | SPEAKER OUTPUT | out | SPEAKER OUTPUT + | medium |
| 22 | SPEAKER OUTPUT RETURN / GROUND | ground | SPEAKER OUTPUT - | medium |
| A | +24..36 V UNREG | power |  | medium |
| C | MIC STRAP | strap |  | medium |
| D | MIC STRAP | strap |  | medium |
| E | MIC STRAP | strap |  | medium |
| F | CARBON MIC SUPPLY STRAP | strap |  | medium |
| H | MIC STRAP | strap |  | medium |
| J | PRE OUTPUT B | insert_send | PRE OUTPUT | medium |
| L | COMMON (-C) | ground |  | medium |
| P | +24..36 V UNREG | power |  | medium |
| T | POWER AMP INPUT SHIELD | shield | POWER AMP INPUT shield | medium |
| U | POWER AMP INPUT A | insert_return | POWER AMP INPUT | medium |
| V | POWER AMP INPUT B | insert_return | POWER AMP INPUT | medium |
| W | MUTE | control_in | MUTE | medium |
| Y | SPEAKER OUTPUT | out | SPEAKER OUTPUT + | medium |
| Z | SPEAKER OUTPUT RETURN / GROUND | ground | SPEAKER OUTPUT - | medium |

**Straps:** DYNAMIC MIC (-60): P1-5 P1-6 · CARBON MIC (-30): P1-6 P1-7 · CARBON + DYNAMIC: P1-6 P1-7

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - 701-02-101 - M701B INTERCOM PRE-AMPLIFIER SCHEMATIC - DRN MRW - ENG MRW - ISS 12.kicad_sch](KICAD/1978%20-%20701-02-101%20-%20M701B%20INTERCOM%20PRE-AMPLIFIER%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%2012.kicad_sch)
- [1978 - 701-02-101 - M701B INTERCOM PRE-AMPLIFIER SCHEMATIC - DRN MRW - ENG MRW - ISS 2.kicad_sch](KICAD/1978%20-%20701-02-101%20-%20M701B%20INTERCOM%20PRE-AMPLIFIER%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%202.kicad_sch)
- [1979 - 701-01-011 - INTERCOM PREAMPLIFIER FUNCTIONAL DIAGRAM - DRN P. Mahoney - ISS 2.kicad_sch](KICAD/1979%20-%20701-01-011%20-%20INTERCOM%20PREAMPLIFIER%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20Mahoney%20-%20ISS%202.kicad_sch)
- [M701.kicad_sym](KICAD/M701.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
