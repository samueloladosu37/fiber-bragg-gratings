# 🔬 Fiber Bragg Gratings (FBG) 
---

## 📘 Introduction

Fiber Bragg Gratings (FBGs) are periodic structures inscribed in the core of optical fibers that reflect specific wavelengths of light while transmitting others. These reflected wavelengths — called **Bragg wavelengths** — shift predictably in response to changes in **temperature** and **strain**, making FBGs ideal for advanced sensing applications.

This experminent demonstrates how a Bragg grating sensor can be used to detect **temperature changes** by tracking the shift in reflected wavelength as the fiber is heated.
---
## 🌍 Real-World Relevance: Why This Experiment Matters

This experiment demonstrates how **Fiber Bragg Gratings (FBGs)** — a compact optical component — serve as a foundation for **advanced sensing technologies** used in critical industries.

### 🚀 Why It Matters

FBG sensors offer several real-world advantages over traditional electrical sensors:
- **Immune to electromagnetic interference (EMI)** – suitable for high-voltage or MRI environments  
- **Passive operation** – no external power needed at the sensing point  
- **High accuracy and sensitivity** – detects sub-nanometer wavelength shifts  
- **Multiplexing capability** – multiple sensors on a single fiber  
- **Durability** – resistant to harsh conditions, corrosion, and high temperatures  

These qualities make FBGs ideal for monitoring environments where reliability and safety are non-negotiable.

---

## 🎯 Aim

To measure the temperature sensitivity of a fiber with an embedded Bragg grating by:
- Observing the Bragg wavelength shift as temperature changes
- Establishing the relationship between wavelength and temperature
- Calculating the system’s sensitivity

---

## 🔬 Methodology

1. Connect the Bragg grating fiber to a broadband light source and an optical spectrum analyzer.
2. Calibrate the analyzer by setting the center wavelength and span.
3. Measure the Bragg wavelength at room temperature.
4. Use a controlled heating system to increase the temperature in steps from **40°C to 100°C**.
5. Record the minimum attenuation band position at each step.
6. Plot the wavelength shift against temperature and analyze the results.

---

## 🛠️ Experimental Setup

- **Light Source**: Broadband optical source
- **Sensor**: Fiber with integrated Bragg grating
- **Analyzer**: Optical spectrum analyzer (OSA)
- **Control Unit**: Programmable temperature controller with heating element
- **Range**: 40°C to 100°C, in 10°C increments

![Sample Setup](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Fiber-Bragg-Grating.png/640px-Fiber-Bragg-Grating.png)

---

## 📊 Results

| Temperature (°C) | Bragg Wavelength (nm) |
|------------------|------------------------|
| 40               | 1549.550               |
| 47               | 1549.572               |
| 59               | 1549.881               |
| 70               | 1550.006               |
| 80               | 1550.223               |
| 90               | 1550.378               |
| 96               | 1550.409               |
| 100              | 1550.440               |

### 📈 Plot: Bragg Wavelength vs. Temperature

![FBG Temperature Plot](photos/plot.png)

> 📌 **Observation**: A **linear increase** in Bragg wavelength with temperature was observed.

---

## 📐 Analysis

- **Dependency**:  
  \[
  \lambda_B = 2 \cdot n_{\text{eff}} \cdot \Lambda
  \]  
  As temperature rises, both the effective refractive index and grating period increase → Bragg wavelength increases.

- **System Sensitivity**:  
  Minimum observed shift: **0.001 nm/°C**

---

## 🧬 Types of Bragg Gratings

| Type | Description | Applications |
|------|-------------|--------------|
| **Uniform FBG** | Constant period and modulation | Standard temperature/strain sensing |
| **Chirped FBG** | Varying period | Dispersion compensation |
| **Tilted (Blazed) FBG** | Angled gratings coupling to cladding modes | Mode filtering, biosensing |
| **Phase-Shifted FBG** | Local π-phase shift | Narrowband filters, laser stabilization |
| **Superstructure FBG** | Modulated envelope | Multi-wavelength sensing |
| **Apodized FBG** | Gradual index change | Side lobe reduction in telecom |

---


---

### 🔧 Real-World Applications of FBG Sensors

| Sector                | Application Example                                                          |
|-----------------------|-------------------------------------------------------------------------------|
| 🏗️ Structural Health   | Stress and strain monitoring in bridges, tunnels, dams, and skyscrapers        |
| ⚡ Power & Energy      | Temperature sensing in transformers, switchgear, and power lines               |
| ✈️ Aerospace           | Real-time strain measurement in wings, engines, and fuselage structures        |
| 🛢️ Oil & Gas           | Downhole temperature and pressure monitoring in extreme drilling conditions    |
| 🏥 Medical Technology  | Non-metallic, EMI-safe sensing in MRI environments, surgical tools, and catheters |
| 🚄 Transportation      | Rail track movement and thermal expansion detection in tunnels and metros      |
| Data Center Infrastruture| Temperature monitoring in server racks, environment monitoring    |

---

## 📁 Project Files

- `lab2.pdf` – Lab report and raw data  
- `photos/plot.png` – Bragg wavelength vs. temperature graph  
- `manual.pdf` – Fiber Bragg Grating theory (PL)  
- `README.md` – This file  

---

## 📚 References

- Lee, B. (2003). Review of the present status of optical fiber sensors. *Optical Fiber Technology*.  
- Vengsarkar et al. (1994). Dual-technique sensor for simultaneous strain and temperature measurement.  
- Karpienko et al. (2014). Refractive index determination using Fabry–Perot interferometer.  
- Zawawi & O'Keeffe (2013). Intensity-modulated fiber optic sensors: A review.  
- Kaczmarek, Z. (2008). *Światłowodowe czujniki i przetworniki pomiarowe*.

