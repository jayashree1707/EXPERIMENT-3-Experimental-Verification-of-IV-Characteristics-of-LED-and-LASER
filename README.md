
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

---

## 📚 THEORY

- **LEDs and LASER diodes** are commonly used sources in optical communication systems for both digital and analog transmission.
- A **linear electrical-to-optical converter** is essential for intensity modulation and high-quality analog transmission.
- LEDs exhibit a **linear optical output** with respect to forward current within a specific operating range.

---

## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM
<img width="1118" height="674" alt="ocn" src="https://github.com/user-attachments/assets/6755f686-d7a7-4ce3-9479-2e7e9bc2c3d5" />



---

## 📊 TABULATION

### LED Forward Characteristics

| Forward Voltage Vf (V) | Forward Current If (mA) |
|------------------------|-------------------------|
|          0             |           0             |
|          1.42          |           0.011         |
|          1.46          |           0.025         |
|          1.48          |           0.038         |
|          1.5           |           0.076         |
|          1.52          |           0.16          |
---

## 📈 MODEL GRAPH
<img width="578" height="502" alt="gr" src="https://github.com/user-attachments/assets/14d2a25b-da1b-4e01-a8b0-9281c6355a6b" />

## OUTPUT GRAPH:
![G](https://github.com/user-attachments/assets/caeda819-180b-4f30-b70e-a2925813be81)


---

## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
