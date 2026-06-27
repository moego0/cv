# Hardware Laboratory & Workshop — Mohamed Ahmed Abdelraouf

Details of the custom prototyping workshop, kinematics, firmware config, and PCB electrochemistry lab.

---

## 1. Custom-Built FDM 3D Printer
Mohamed assembled a custom CoreXY FDM 3D printer from individual structural parts to support casing and mechanical prototype fabrication.
- **Kinematics**: CoreXY configuration. Stationary X/Y stepper motors eliminate printing axis inertia, allowing high-speed movement without quality loss.
- **Z-Axis**: Dual leadscrews driven by independent Z steppers to eliminate bed sag.
- **Hotend / Extruder**: Direct-drive dual-gear extruder paired with an all-metal hotend. Enables printing high-tolerance flexible filaments (TPU).
- **Firmware**: Marlin 2.0. Optimized TMC2209 stepper driver UART configurations, enabling silent stealthChop motor execution and sensorless homing.

---

## 2. PCB Electrochemistry & Fabrication Lab
To avoid single-sided copper boundaries and wire jumpers, Mohamed set up a home chemical bath to plate double-sided through-hole vias.
- **Mechanical Step**: A custom CNC mill drills via layouts and component coordinates onto dual-layer copper laminates.
- **Sensitization Bath**: The boards are submerged in a palladium chloride / stannous chloride solution. Palladium molecules deposit onto the inner plastic walls of the holes to form metal seed clusters.
- **Electroless Deposition**: Placed in an alkaline copper formaldehyde bath. This deposits a thin (1-2 micron) layer of copper onto the sensitized hole walls.
- **Electrolytic Plating**: Placed in a copper sulfate acid bath. Subscribing electric currents triggers electrolysis, thickening the traces and holes to standard 35-micron (1 oz) copper.
