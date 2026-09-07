# 🦵 OsteoSense
### AI-Powered Multimodal Smart Knee Patch for Early Osteoarthritis Risk Assessment

> **One Patch. Multiple Signals. One AI-Based Risk Profile.**

OsteoTrack is a proposed wearable, non-invasive knee-monitoring system designed to explore **early risk assessment of Osteoarthritis (OA)** using multimodal physiological sensing and Artificial Intelligence.

The system combines **Bioimpedance Spectroscopy** and **Near-Infrared Spectroscopy (NIRS)** in a compact knee-worn patch. The acquired signals are processed using an **ESP32**, transmitted wirelessly through **Bluetooth**, and analysed using an AI/ML pipeline to generate an interpretable **OA risk profile** on a mobile application.

---

## 🚨 Problem Statement

Osteoarthritis is a progressive joint disorder in which structural and biochemical changes can occur before severe symptoms become obvious.

Current assessment pathways may involve:

- Clinical examination
- Patient history
- Imaging
- Laboratory investigations when required
- Specialist consultation

These approaches can be time-consuming, expensive, or dependent on clinical infrastructure.

### The challenge

**Can we develop a portable and affordable system that can continuously/rapidly capture complementary knee-tissue signals and use AI to identify patterns associated with early OA risk?**

---

# 💡 Our Solution

**OsteoTrack** proposes a smart knee patch capable of collecting complementary physiological information from the knee region.

Instead of relying on a single measurement, OsteoTrack combines:

### 🔵 Bioimpedance — AD5933
Measures electrical impedance characteristics of tissue across frequencies.

Potentially useful features include:

- Resistance
- Reactance
- Impedance magnitude
- Phase response
- Frequency-dependent impedance patterns

### 🟢 NIRS — AS7265x
Uses optical spectral information to investigate tissue-related changes.

Potential features include:

- Spectral response
- Wavelength-dependent features
- Optical signal patterns

The complementary signals are then processed and fused before AI-based analysis.

---

# 🏗️ System Architecture

<img width="1536" height="1024" alt="OA_system architechture" src="https://github.com/user-attachments/assets/78a10bb9-308f-4dbf-8139-db6a45d3290d" />
                     ↓
          Risk Score + Key Insights
