# EXPERIMENT NO. 5 – ZENER DIODE AS VOLTAGE REGULATOR

| **Name:** | AJISHRAJ.B | **Reg. No.:** | 26018348 |
|---|---|---|---|
| **Date:** |25/11/2026 | **Batch / Section:** | 26ODJ108|

---

## AIM

To study the Zener diode as a voltage regulator and to obtain its line regulation and load regulation characteristics.

## APPARATUS REQUIRED

| S. No. | Name of the apparatus | Range | Quantity |
|:---:|:---:|:---:|:---:|
| 1 | Zener diode | 1N4735A | 1 |
| 2 | Resistors | 1 kΩ, 10 kΩ | 1 each |
| 3 | Regulated power supply | (0–30) V DC | 1 |
| 4 | Breadboard | — | 1 |
| 5 | Digital ammeter | (0–200) mA | 1 |
| 6 | Digital voltmeter | (0–20) V DC | 1 |
| 7 | Decade resistance box (load RL) | — | 1 |
| 8 | Connecting wires | — | As required |
| 9 | Simulation software | Proteus Design Suite | 1 |

## THEORY

A Zener diode is a heavily doped p-n junction diode, specially made to operate in the breakdown region. When reverse biased beyond a particular voltage, called the Zener breakdown voltage (Vz), it starts conducting heavily. Once it conducts, it maintains an almost constant voltage across its terminals whatever the current through it, i.e. it has a very low dynamic resistance. A series resistor Rs is connected to limit the current, since a high current can permanently damage the device.

In a Zener voltage regulator, the Zener diode is connected in reverse bias in parallel with the load, and the series resistor Rs is connected between the supply and the load. Any change in input voltage or load current changes the Zener current, while the output voltage across the load stays nearly constant at Vz.

**Line regulation:** the ability of the regulator to keep the output voltage constant when the input voltage varies, with the load kept constant.

**Load regulation:** the ability of the regulator to keep the output voltage constant when the load resistance (load current) varies, with the input voltage kept constant.

## PRECAUTIONS

1. While doing the experiment, do not exceed the ratings of the Zener diode; this may damage the diode.
2. Connect the voltmeter and ammeter in correct polarities as shown in the circuit diagram.
3. Do not switch ON the power supply unless the circuit connections have been checked as per the circuit diagram.

## PROCEDURE

### A. Line regulation

1. Connections are made as per the line regulation circuit diagram, with a fixed load resistance RL.
2. Vary the regulated power supply (input) voltage Vin in steps.
3. For each input voltage, note the output voltage Vo across the load and tabulate the readings.
4. Plot a graph of input voltage Vin (x-axis) versus output voltage Vo (y-axis).

### B. Load regulation

1. Connections are made as per the load regulation circuit diagram.
2. Set the input voltage Vin to a constant value above the Zener voltage.
3. Note the no-load output voltage VNL with the load disconnected.
4. Connect the load and vary the load resistance RL in steps; note the output voltage Vo for each value and tabulate the readings.
5. Plot a graph of load resistance RL (x-axis) versus output voltage Vo (y-axis).

## CIRCUIT DIAGRAM

### A. Line regulation

*[ Insert the line regulation circuit diagram here ]*
<img width="1032" height="656" alt="Screenshot 2026-11-22 221637" src="https://github.com/user-attachments/assets/36265ade-6f77-4c97-ba1f-788f872e8169" />

**Figure 1:** Zener voltage regulator – line regulation

### B. Load regulation

*[ Insert the load regulation circuit diagram here ]*
<img width="1026" height="630" alt="Screenshot 2026-11-22 221654" src="https://github.com/user-attachments/assets/6ecb247a-a348-41da-8099-0f63b5b69ed5" />

**Figure 2:** Zener voltage regulator – load regulation

## SIMULATION USING PROTEUS

Build the Zener regulator circuit in Proteus using the 1N4735A, the series resistor and the load. Vary the input voltage (line regulation) and the load resistance (load regulation), and paste screenshots showing the meter readings.

### A. Line regulation – simulation

*[ Paste the Proteus line regulation simulation screenshot here ]*
<img width="1041" height="667" alt="Screenshot 2026-11-22 221709" src="https://github.com/user-attachments/assets/7ad3f0f4-2b1a-4ae6-8e3a-515c02465a56" />



<img width="1018" height="622" alt="Screenshot 2026-11-22 221805" src="https://github.com/user-attachments/assets/07d87b53-872a-4965-841e-cc2af5864c7b" />


**Figure 3:** Proteus simulation – line regulation

### B. Load regulation – simulation

*[ Paste the Proteus load regulation simulation screenshot here ]*

<img width="1025" height="627" alt="Screenshot 2026-11-22 221833" src="https://github.com/user-attachments/assets/8ab0fbc4-714a-4fde-b181-62df2f6d3d52" />



<img width="1017" height="646" alt="Screenshot 2026-11-22 221904" src="https://github.com/user-attachments/assets/5f37e956-220b-40ce-b62f-c8f61feee052" />

**Figure 4:** Proteus simulation – load regulation

## TABULATION

### A. Line regulation (RL = 2000 Ω, constant)

| S. No. | Input voltage Vin (V) | Output voltage Vo (V) |
|:---:|:---:|:---:|
| 1  | 30  | 10.10 |
| 2  | 40  | 10.12 |
| 3  | 50  | 10.14 |
| 4  | 60  | 10.16 |
| 5  | 70  | 10.18 |
| 6  | 80  | 10.20 |
| 7  | 90  | 10.22 |
| 8  | 100 | 10.24 |
| 9  | 110 | 10.26 |
| 10 | 120 | 10.28 |
### B. Load regulation (Vin = 30 V, constant)

| S. No. | Load resistance RL (Ω) | Output voltage Vo (V) |
|:---:|:---:|:---:|
| 1 | 100 | 9.80 |
| 2 | 200 | 9.85 |
| 3 | 300 | 9.89 |
| 4 | 400 | 9.92 |
| 5 | 500 | 9.95 |
| 6 | 600 | 9.98 |
| 7 | 700 | 10.00|
| 8 | 800 | 10.03|
| 9 | 900 | 10.05|
| 10 | 1000 |10.08| 

## FORMULAE

- **% Line regulation = (ΔVo / ΔVin) × 100**
- **% Load regulation = (VNL − VFL) / VFL × 100**
- **Series resistance Rs = (Vin − Vz) / (Iz + IL)**

ΔVo – change in output voltage; ΔVin – change in input voltage; VNL – no-load output voltage; VFL – full-load output voltage; Vz – Zener voltage; Iz – Zener current; IL – load current.

## MODEL GRAPH

### A. Line regulation (Vin vs Vo)

*[ Paste / draw the line regulation graph here ]*
<img width="1030" height="603" alt="Screenshot 2026-11-22 221929" src="https://github.com/user-attachments/assets/02f2eab4-b69f-44ba-8878-33150bef553f" />

**Figure 5:** Line regulation characteristics

### B. Load regulation (RL vs Vo)

*[ Paste / draw the load regulation graph here ]*
<img width="1033" height="591" alt="Screenshot 2026-11-22 221943" src="https://github.com/user-attachments/assets/e09c50b5-0d12-4108-936b-edb3f8847e21" />

**Figure 6:** Load regulation characteristics

## RESULT

Thus, the Zener diode was used as a voltage regulator, and its line regulation and load regulation characteristics were obtained.
