# 📡 Microstrip Patch Antenna with DGS (5.2 GHz)

## 📌 Overview
This project presents the design and simulation of a **5.2 GHz microstrip patch antenna** enhanced using a **Defected Ground Structure (DGS)**.

The antenna is designed for **WLAN applications** and simulated using **Ansys HFSS (FEM-based)** to evaluate performance parameters like return loss, VSWR, gain, and impedance.

---

## 🎯 Objectives
- Design a microstrip patch antenna operating at **5.2 GHz**
- Improve performance using **Defected Ground Structure (DGS)**
- Simulate antenna using **Ansys HFSS**
- Analyze:
  - Return Loss (S11)
  - VSWR
  - Gain
  - Impedance matching

---

## ⚙️ Antenna Design

### 📐 Configuration
- Type: Rectangular Microstrip Patch
- Substrate: FR4 (εr = 4.4)
- Thickness: 1.6 mm
- Feeding: Microstrip line (50Ω lumped port)
- Ground: Defected Ground Structure (rectangular slot)

### 📏 Dimensions
| Component | Size |
|----------|------|
| Substrate | 27 mm × 27 mm |
| Patch | 12.5 mm × 12.5 mm |
| Feed Line | 2 mm × 8 mm |
| DGS Slot | 10 mm × 1 mm |
| Air Box | 80 × 80 × 40 mm |

---

## 🧪 Simulation Setup
- Software: Ansys HFSS
- Method: Finite Element Method (FEM)
- Frequency Range: 1 GHz – 10 GHz
- Boundary: Radiation (Air Box)
- Port: 50Ω Lumped Port

---

## 📊 Results

### 🔹 Return Loss (S11)
- **-28.2 dB at 5.2 GHz**
- Indicates excellent impedance matching

### 🔹 VSWR
- **1.06 at 5.2 GHz**
- Near ideal (≈1)

### 🔹 Gain
- **1.77 dBi**
- Broadside radiation

### 🔹 Bandwidth
- ~270 MHz (~5.2%)

### 🔹 Impedance
- ≈ 51 + j1.5 Ω

---

## 🚀 Key Features
- Enhanced performance using DGS
- Multiband operation:
  - 5.2 GHz (primary)
  - 7.8 GHz & 9.2 GHz (secondary)
- Compact and low-cost design
- Suitable for WLAN applications

---

## 📈 Why DGS?
Defected Ground Structure:
- Improves impedance matching
- Enhances bandwidth
- Alters current distribution
- Enables multiband behavior

---

## 🔧 Simulation Steps
1. Create substrate  
2. Design patch  
3. Add feed line  
4. Create ground plane  
5. Introduce DGS  
6. Assign port  
7. Add air box  
8. Run simulation  

---

## 📦 Applications
- WLAN (IEEE 802.11a/n/ac)
- RF & Microwave systems
- Multiband wireless communication

---

## 🔮 Future Scope
- Gain improvement using antenna arrays
- Bandwidth enhancement via optimized DGS
- Fabrication and measurement
- Circular polarization design

---

## 👨‍💻 Author
**Haneesh Reddy Devajji**  
Electronics & Communication Engineering  

---