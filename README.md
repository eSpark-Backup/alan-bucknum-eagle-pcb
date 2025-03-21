# Eagle PCB Design Optimization
#### Alan Bucknum

## Project Requirements
The existing Eagle files are present at [this link](https://github.com/eSpark-Consultants/alanbucknum-eaglepcb/tree/main/docs/Client-Files/Original-Design) (at the docs folder in the repository). The updated design files for v1.1 are also present in Design-Files folder.  Below changes are to be applied on Design-Files folder:
- The two buttons (SW1 & SW2) to be moved to the backside. Ideally SW1 & SW2 would be centered (top/bottom), and closer to the right-hand side
- The PCB length (currently 40mm) should be 20mm or less.
- Width is made as small as possible while maintaining technical accuracy and considerations.
- ~The micro-USB port to either be on one of the thin edges, or at least outside of the middle 25mm.~
- LED D9 can be fully removed.
- ~TAG-ICSP would ideally be centered (as much as possible).~
- Remove TP D7_ACCEL & TP GND.
- Remove: LDO and RCHRG Circuit.
- Remove: RFM69 & Antenna.
- Remove: Micro-USB, ICSP Pins.
- Remove: AVR MCU.
- Replace: LEDs with 3mm TH IR LEDs.
- Replace: MCU with SEEEDSTUDIO ESP32C6
- Add: Additional IR Driver.
