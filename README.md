<h1 align="center">Hi 👋, I'm Suneel Kumar Patel</h1>
<h3 align="center">Analog & Mixed-Signal IC Design Engineer @ Anedge Semiconductor Pvt. Ltd</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=650&lines=LDO+%7C+Bandgap+Reference+%7C+Op-Amp+Design;Charge+Pump+%7C+Current+Mirror+%7C+SAR+ADC;Cadence+Virtuoso+%7C+Spectre+%7C+GF+90nm+%2F+TSMC+180nm;%C2%B12+Years+in+CMOS+Analog+IC+Design" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=skp404&label=Profile%20Views&color=58A6FF&style=flat" alt="skp404" />
  <img src="https://img.shields.io/badge/Experience-~2%20Years-brightgreen?style=flat" />
  <img src="https://img.shields.io/badge/Location-Satna%2C%20M.P.-blueviolet?style=flat" />
</p>

---

### 🔬 About Me

- 🎯 **Analog Circuit Designer** at Anedge Semiconductor, working on CMOS analog IC design since Jan 2025
- 🧩 Currently designing the **DAC sub-block of an 8-bit low-power SAR ADC** — evaluating R-2R, binary-weighted, resistor-string, and weighted-capacitor architectures
- ⚡ Designed and verified **LDOs, Bandgap References, Op-Amps, Charge Pumps, Current Mirrors, and Constant-gm Bias circuits** across **GF 90nm** and **TSMC 180nm**
- 🛠️ Daily driver: **Cadence Virtuoso (ADE L/XL) + Spectre** for schematic, simulation, and sign-off
- 📈 Strong focus on **DC/AC/Transient, Stability (STB), PSRR, Monte Carlo, and full PVT corner analysis**
- 🐍 Automate simulation sweeps and result parsing with **Python & Shell scripting**
- 🔭 Next up: digital background calibration & linearity improvement techniques for SAR ADCs
- 💬 Ask me about: LDOs, Bandgap References, Op-Amp compensation, Charge Pumps, Current Mirrors, and SAR ADC DAC architectures

---

### 🧰 Tools & Technologies

<p align="left">
  <img src="https://img.shields.io/badge/Cadence%20Virtuoso-FF6600?style=for-the-badge&logo=cadence&logoColor=white" />
  <img src="https://img.shields.io/badge/Spectre-1F6FEB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/GF%2090nm-333333?style=for-the-badge" />
  <img src="https://img.shields.io/badge/TSMC%20180nm-333333?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SPICE-00599C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LTspice-0F5FA6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SIMetrix-6A5ACD?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Shell%20Scripting-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
</p>

---

### 🧠 Core Design Expertise

<table>
<tr><td valign="top" width="50%">

**Analog Building Blocks**
`LDO Design` `Bandgap Reference (BGR)` `Operational Amplifier` `Op-Amp Design` `Charge Pump Design` `Current Mirror` `Constant-gm Bias` `Biasing Circuit Design` `CMOS Inverter`

**Mixed-Signal / Data Converters**
`SAR ADC` `R-2R Ladder DAC` `Segmented DAC` `Resistor String DAC` `Weighted Capacitor DAC` `Binary Weighted DAC`

</td><td valign="top" width="50%">

**Simulation & Verification**
`DC Analysis` `AC Analysis` `Transient Analysis` `Stability (STB)` `PSRR` `Monte Carlo Analysis` `PVT Corner Analysis` `Mismatch Analysis`

**EDA Tools & Process**
`Cadence Virtuoso` `ADE L/XL` `Spectre` `SPICE` `SIMetrix` `LTspice` `Synopsys Tools` `GF 90nm` `TSMC 180nm`

</td></tr>
</table>

---

### 🚀 Project Experience

<details>
<summary><b>🔋 Bandgap Reference (BGR) Design — TSMC 180nm</b></summary>
<br>

- Designed standard **1.2V BGR** using PTAT and CTAT voltage cancellation for stability across temperature and process variation
- Designed a low-power **Sub-1V (800mV) BGR** in current-mode architecture — PTAT/CTAT currents summed through a precision resistor network
- Implemented always-active startup circuitry to eliminate metastable locking
- Optimized resistor ratios and device sizing to minimize temperature coefficient
- Improved line regulation and temperature stability via current matching
- ✅ Verified with Monte Carlo, transient, temperature sweep (−40°C to 125°C), and full PVT corner analysis

</details>

<details>
<summary><b>⚡ Low Dropout Regulator (LDO) Design — GF 90nm</b></summary>
<br>

- Designed LDO targeting **high PSRR, low quiescent current**, and robust transient response
- Designed and optimized compensation network for stable phase margin across full load range
- Optimized pass transistor sizing to reduce overshoot/undershoot during load transients
- Performed DC load regulation, line regulation, STB, and PSRR analysis
- Migrated and re-optimized design from **TSMC 180nm → GF 90nm**; characterized short-channel and mismatch effects
- ✅ Conducted extensive PVT corner and Monte Carlo analysis for statistical sign-off

</details>

<details>
<summary><b>📐 Two-Stage CMOS Operational Amplifier</b></summary>
<br>

- Designed a two-stage Miller-compensated CMOS op-amp:

  | Parameter | Value |
  |---|---|
  | Gain | > 40 dB |
  | Phase Margin | > 60° |
  | Slew Rate | 30 V/µs |
  | PSRR | −60 dB |
  | Load Cap | 1 pF |
  | ICMR(+) / ICMR(−) | 0.9 V / 0.6 V |

- Implemented Miller compensation for phase margin improvement and unity-gain stability
- Optimized differential pair and second-stage sizing for gain-bandwidth and slew rate
- ✅ Verified via AC, DC, transient, stability, and corner simulations; robustness confirmed with Monte Carlo

</details>

<details>
<summary><b>🔌 Charge Pump Design — TSMC 180nm</b></summary>
<br>

- Designed a multi-stage capacitor-based charge pump for voltage-boosting applications
- Optimized transistor sizing to minimize switch resistance and improve charge transfer efficiency
- Implemented level shifter and buck switching for proper gate drive across supply domains
- Reduced output ripple through optimized clocking scheme and capacitor dimensioning
- ✅ Verified transient response, efficiency, and output ripple across PVT corners

</details>

<details>
<summary><b>🎛️ Biasing Circuits — Current Mirror & Constant-gm — GF 90nm</b></summary>
<br>

- Designed basic, cascode, and low-voltage cascode current mirrors — optimized for output resistance and swing
- Designed a **beta-multiplier / constant-gm bias circuit** generating a stable 10 µA reference
- Implemented startup circuitry for the constant-gm loop for reliable initialization across PVT
- Reduced current mismatch from channel length modulation via device sizing optimization
- ✅ Verified DC accuracy, output swing, mismatch behavior, and PVT robustness via Monte Carlo

</details>

<details>
<summary><b>📊 SAR ADC Sub-block — DAC Design (Active Project, Mixed-Signal)</b></summary>
<br>

- Working on an **8-bit low-power SAR ADC**; responsible for DAC sub-block design and verification
- Designed and analyzed **R-2R Ladder, Binary Weighted Resistor, Resistor String, and Weighted Capacitor DAC** architectures
- Studied **DNL/INL trade-offs** across architectures
- Optimized resistor matching and switching architecture for improved linearity and monotonicity
- Evaluated speed, area, power, and resolution trade-offs for low-power ADC target spec
- ✅ Verified output accuracy via DC/transient simulation; corner and mismatch analysis for robustness

</details>

<details>
<summary><b>🔲 CMOS Inverter Design — Digital-Analog Interface</b></summary>
<br>

- Designed a CMOS inverter with balanced rise/fall delay via optimized PMOS/NMOS sizing
- Analyzed voltage transfer characteristics (VTC), noise margins, and switching threshold
- Studied fan-in/fan-out effects and propagation delay behavior
- ✅ Verified noise margins and switching performance across PVT corners

</details>

---

### 💼 Work Experience

| Period | Role | Company | Type |
|---|---|---|---|
| Jan 2025 – Present | Analog Circuit Designer | Anedge Semiconductor Pvt. Ltd | Full-Time |
| Jun 2023 – Sep 2023 | Analog Electronics Intern | Anedge Semiconductor Pvt. Ltd | Internship |

### 🎓 Education

| Institution | Qualification | Year / Score |
|---|---|---|
| Govt. Engineering College, Rewa (M.P.) | B.Tech – ECE | 2024 · 6.66 CGPA |
| Government Excellence School, Rewa (M.P.) | Higher Secondary (XII) | 2020 · 86% |
| Government Excellence School, Rewa (M.P.) | High School (X) | 2018 · 92% |

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=skp404&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=skp404&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=skp404&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=skp404&theme=tokyo-night&hide_border=true" alt="Activity Graph" />
</p>

---

### 🌐 Connect with Me

<p align="left">
  <a href="https://github.com/skp404" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/REPLACE-ME" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:suneelpatel1254@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

> 📝 Replace `REPLACE-ME` in the LinkedIn link with your actual profile handle before publishing.

---

<p align="center"><i>"Great chips aren't just designed — they're characterized, verified, and refined."</i></p>
