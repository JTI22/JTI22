<div align="center">

<img src="hero.svg" width="100%" alt="Jayan Tasnim — computing × flight"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3200&pause=1400&color=38BDF8&center=true&vCenter=true&width=560&lines=Learning-based+models+for+things+that+fly;Uncertainty-aware+ML+%C2%B7+aerodynamics;Embedded+autonomy+for+UAVs+and+robots" alt="Typing SVG"/>

<a href="https://www.linkedin.com/in/jayan-tasnim-181218375/"><img src="https://img.shields.io/badge/LinkedIn-0B1220?style=for-the-badge&logo=linkedin&logoColor=38BDF8" alt="LinkedIn"/></a>
<a href="mailto:jayantasnim@gmail.com"><img src="https://img.shields.io/badge/Email-0B1220?style=for-the-badge&logo=gmail&logoColor=38BDF8" alt="Email"/></a>
<a href="https://orcid.org/0009-0005-4438-6886"><img src="https://img.shields.io/badge/ORCID-0B1220?style=for-the-badge&logo=orcid&logoColor=38BDF8" alt="ORCID"/></a>

</div>

---

## About

I'm a Computer Science and Engineering student in Dhaka. I like problems where software has to be trusted with something physical — an aircraft, a drone, a robot.

My work sits between machine learning and flight: models that know when they are unsure, embedded systems that react in real time, and results that are easy to explain.

- **Focus** — aerodynamic surrogates · uncertainty & safety · UAV autonomy · embedded systems · explainable AI
- **Now** — federated & explainable AI thesis · a learned aero surrogate with a safety fallback · NASA Space Apps 2026
- **Next** — a master's in aerospace engineering

## Research

### Federated Generative AI and Explainable AI for Resilient IoT Botnet Detection

![Thesis](https://img.shields.io/badge/Undergraduate_Thesis-2026-0B1220?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-0B1220?style=flat-square&logo=pytorch&logoColor=38BDF8)
![Federated](https://img.shields.io/badge/Federated_Learning-0B1220?style=flat-square)
![XAI](https://img.shields.io/badge/SHAP_%C2%B7_LIME-0B1220?style=flat-square)

A CNN-BiGRU detector trained with Federated Averaging across nine IoT device clients on the full N-BaIoT dataset, reaching `99.94%` accuracy without sharing raw traffic. A TVAE-based, drift-aware aggregation keeps it stable under label drift, and SHAP and LIME explain each decision.

## Projects

<table>
<tr>
<td colspan="2" valign="top">

### ✈️ [Confidence-Aware Fallback for a Learned Aerodynamic Surrogate](https://github.com/JTI22/confidence-aware-aero-surrogate-fallback)

![MATLAB](https://img.shields.io/badge/MATLAB-0B1220?style=flat-square)
![Simulink](https://img.shields.io/badge/Simulink-0B1220?style=flat-square)
![XFOIL](https://img.shields.io/badge/XFOIL-0B1220?style=flat-square)
![Ongoing](https://img.shields.io/badge/ongoing-0B1220?style=flat-square)

A Gaussian Process surrogate of NACA 0012 aerodynamics, trained on XFOIL data. When the model is unsure, a confidence gate hands control to a lookup table. Tested in a closed-loop `6-DOF Simulink` model under gust and trim-runaway faults near stall.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛩️ [UAV Collision Advisory](https://github.com/JTI22/uav-collision-advisory-telemetry)

![C](https://img.shields.io/badge/C-0B1220?style=flat-square&logo=c&logoColor=38BDF8)
![STM32](https://img.shields.io/badge/STM32-0B1220?style=flat-square&logo=stmicroelectronics&logoColor=38BDF8)
![Python](https://img.shields.io/badge/Python-0B1220?style=flat-square&logo=python&logoColor=38BDF8)

`Time-to-collision` advisory and blind-spot detection on a simulated STM32F103 with UAV flight physics, plus a live Python telemetry dashboard.

</td>
<td width="50%" valign="top">

### 🔥 Flame in Freefall

![NASA](https://img.shields.io/badge/NASA_Space_Apps-2026-0B1220?style=flat-square&logo=nasa&logoColor=38BDF8)
![ML](https://img.shields.io/badge/Machine_Learning-0B1220?style=flat-square)

An AI dashboard for microgravity combustion data: why flames turn into spheres in orbit, and what it means for spacecraft fire safety. `Team lead`.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 [Medical Delivery Robot](https://github.com/JTI22/Capstone_Code)

![ESP32](https://img.shields.io/badge/ESP32-0B1220?style=flat-square&logo=espressif&logoColor=38BDF8)
![C++](https://img.shields.io/badge/C++-0B1220?style=flat-square&logo=cplusplus&logoColor=38BDF8)
![RFID](https://img.shields.io/badge/RFID-0B1220?style=flat-square)

An ESP32 line-following robot that carries supplies between stations. Ultrasonic sensing stops it before obstacles, and `RFID` tags mark each stop.

</td>
<td width="50%" valign="top">

### 📡 AeroGuard Sentinel

![Robotics](https://img.shields.io/badge/Robotics-0B1220?style=flat-square)
![Tracking](https://img.shields.io/badge/Tracking-0B1220?style=flat-square)

A simulated air-defence robot that scans the sky, detects aerial targets and keeps them in track.

</td>
</tr>
</table>

## Coursework

<table>
<tr>
<td width="50%" valign="top">

**Modelling & Mathematics**

`CSE 405` Numerical & Mathematical Analysis<br/>
`MTH 201` Vector Geometry & Linear Algebra<br/>
`MTH 103` Calculus I & II<br/>
`MTH 203` Probability & Statistics<br/>
`CSE 105` Discrete Mathematics

</td>
<td width="50%" valign="top">

**Autonomy & Intelligent Systems**

`CSE 437` Robotics + Lab<br/>
`CSE 413` Machine Learning & Deep Learning + Lab<br/>
`CSE 401` Operating Systems + Lab<br/>
`CSE 311` Data Communication & Networks + Lab<br/>
`CSE 317` Computer & Cyber Security

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Embedded & Electronics**

`CSE 315` Microprocessors & Microcontrollers + Lab<br/>
`CSE 303` Computer Architecture & Organization<br/>
`CSE 209` Digital Logic Design + Lab<br/>
`EEE 201` Electronic Devices & Circuits + Lab<br/>
`EEE 101` Electrical Circuits + Lab

</td>
<td width="50%" valign="top">

**Physics & Computing Core**

`PHY 301` Modern & Quantum Physics<br/>
`PHY 101` Physics for Computer Science + Lab<br/>
`CSE 207` Data Structures & Algorithms I–II<br/>
`CSE 301` Object-Oriented Programming I–II<br/>
`CSE 313` Software Engineering + Lab

</td>
</tr>
</table>

## Toolkit

<table>
<tr>
<td width="50%" valign="top" align="center">

**Machine Learning**

<img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn&theme=dark"/>

`NumPy` `Pandas` `XGBoost` `SHAP` `LIME`

</td>
<td width="50%" valign="top" align="center">

**Aero & Simulation**

<img src="https://skillicons.dev/icons?i=matlab&theme=dark"/>

`Simulink` `Aerospace Blockset` `XFOIL`

</td>
</tr>
<tr>
<td width="50%" valign="top" align="center">

**Embedded & Systems**

<img src="https://skillicons.dev/icons?i=c,cpp,arduino&theme=dark"/>

`STM32` `ESP32` `PICSimLab` `UART`

</td>
<td width="50%" valign="top" align="center">

**Build & Write**

<img src="https://skillicons.dev/icons?i=django,html,css,git,latex&theme=dark"/>

`Streamlit` `Bootstrap` `Packet Tracer`

</td>
</tr>
</table>

## GitHub Activity

<div align="center">

<img height="170" src="https://streak-stats.demolab.com/?user=JTI22&hide_border=true&background=0B1220&stroke=1E293B&ring=38BDF8&fire=F2A65A&currStreakLabel=38BDF8&sideLabels=C9D4E3&currStreakNum=E6EDF6&sideNums=E6EDF6&dates=7D8DA6" alt="Streak"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JTI22&layout=compact&hide_border=true&bg_color=0B1220&title_color=38BDF8&text_color=C9D4E3&exclude_repo=Portfolio,JTPortfolio,MyBooksProjectPractise&langs_count=6" alt="Top languages"/>

<br/><br/>

<sub><i>Software you can trust with things that fly.</i></sub>

</div>
