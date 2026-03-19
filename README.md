# EXP-6-SIMULATION-OF-SOLAR-PV-SYSTEM-UNDER-PARTIAL-SHADED-CONDITION

## Aim
To simulate a solar powered system using MATLAB and obtain the I-V and P-V characteristics under partial shading condition.

---

## Software Used
- MATLAB (2021 or above)
- Simulink

---

## Modelling Parameters

| S.No | Parameter              | Value             |
|------|------------------------|-------------------|
| 1    | Maximum Voltage (Vm)   | 42.8 V            |
| 2    | Maximum Current (Im)   | 5.84 A            |
| 3    | Open Circuit Voltage   | 50.93 V           |
| 4    | Short Circuit Current  | 6.2 A             |
| 5    | Maximum Power          | 250 W             |
| 6    | Cells per Module       | 72                |
| 7    | Series Modules         | 4                 |
| 8    | Irradiance             | 300–1000 W/m²     |
| 9    | Temperature            | 25°C to 35°C      |

---

## Theory
Partial shading occurs when some parts of a solar panel receive less sunlight than others. This reduces the overall output of the PV system.

Solar cells in a module are connected in series. When shading occurs:
- Current reduces in shaded cells
- Power output decreases
- Hotspots may occur

Bypass diodes are used to reduce these effects:
- Connected in parallel with cell groups
- Conduct when shading occurs
- Allow current to bypass shaded cells

This helps maintain output power and prevents damage.

## Circuit Diagram
<img width="1918" height="985" alt="image" src="https://github.com/user-attachments/assets/f2f10cba-d9e9-4978-bb05-b7f91e0ef6d4" />

## Procedure
1. Open MATLAB.
2. Open Simulink Library Browser.
3. Add components:
   - Solar panel, voltage source
   - Measurement blocks
   - Diode, demux, scope
4. Connect all components as per the circuit diagram.
5. Set parameters as given.
6. Run simulation.
7. Record voltage, current, and power.
8. Plot I-V and P-V characteristics.

---

## Tabulation

| Vm (V) | Im (A) | Pm (W) |
|--------|--------|--------|
| 175    | 3.0    | 525    |
| 120    | 4.5    | 540    |
---
## Output Waveform
<img width="1841" height="810" alt="image" src="https://github.com/user-attachments/assets/695a597a-cdab-4a54-8c85-a0a27841db46" />
<img width="1883" height="833" alt="image" src="https://github.com/user-attachments/assets/ecb9eb18-85ce-4f4d-8009-b7f0e6f9682d" />


## Result
The I-V and P-V characteristics of the solar PV system under partial shading condition were successfully obtained using MATLAB.
