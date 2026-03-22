[English](https://github.com/Hiroshi-Okajima), [日本語JP](https://github.com/Hiroshi-Okajima/Profile-Japanese)

# Hiroshi Okajima | 岡島 寛

## Profile

Associate Professor at Kumamoto University, Japan (熊本大学). Research field: Control engineering, Control theory — 20 years of research experience.

- Web: [www.control-theory.com](https://www.control-theory.com/en) | Blog: [blog.control-theory.com](https://blog.control-theory.com/)
- [Researchgate](https://www.researchgate.net/profile/Hiroshi-Okajima) | [Researchmap](https://researchmap.jp/read0203288?lang=en) | [ORCID](https://orcid.org/0000-0001-7621-7482) | [Google Scholar](https://scholar.google.co.jp/citations?user=UEMk-g4AAAAJ)
- YouTube: [Control Engineering Channel (10000+ subscribers, Japanese)](https://www.youtube.com/c/ControlEngineeringChannel/videos) | [English Channel](https://www.youtube.com/@ControlEngineeringCh/videos)
- X: [@control_eng_ch](https://x.com/control_eng_ch)
- MATLAB File Exchange: [H. Okajima](https://www.mathworks.com/matlabcentral/fileexchange/?q=profileid%3A12980078)
- Paper and proceedings: [My research articles](https://www.control-theory.com/en/publications)

![okajima_200](https://github.com/user-attachments/assets/c7b0db0d-0448-4589-a513-aa2870b6385f)


---

## Blog Hub Articles (Comprehensive Guides)

These hub articles provide comprehensive overviews of each research area, linking to detailed tutorials, paper explanations, and MATLAB code.

| Topic | Blog Hub Article | GitHub Repository |
|-------|-----------------|-------------------|
| **State Feedback Control** | [State Feedback Control and State-Space Design: A Comprehensive Guide](https://blog.control-theory.com/entry/state-feedback-control-eng) | [control_state_feedback](https://github.com/Hiroshi-Okajima/control_state_feedback) |
| **System Identification** | [System Identification: From Data to Dynamical Models](https://blog.control-theory.com/entry/system-identification) | [MATLAB_system_identification](https://github.com/Hiroshi-Okajima/MATLAB_system_identification) |
| **State Observer** | [State Observer and State Estimation: A Comprehensive Guide](https://blog.control-theory.com/entry/state-observer-estimation) | [MATLAB_state_observer](https://github.com/Hiroshi-Okajima/MATLAB_state_observer) |
| **Model Error Compensator** | [Model Error Compensator (MEC): Enhance the Robustness of Existing Control Systems](https://blog.control-theory.com/entry/model-error-compensator-eng) | See MEC repositories below |

---

## 1: Model Error Compensator (My main research topic)

"Model Error Compensator" is a method for adding robustness to existing control systems. A structure of "model error compensator" was proposed by us, and it has been applied to various control systems. The control objective of the model error compensator (MEC) is to minimize as much as possible the effect of the model error and the disturbance in the meaning of the input-output relation. This compensator has a simple form and is easy to apply to various types of existing control systems, such as non-linear systems, control systems with time delay, non-minimum phase systems, MIMO systems, and so on.

<img width="713" height="614" alt="image" src="https://github.com/user-attachments/assets/229323a7-5bc6-433f-9af8-4a2046132639" />

- Research page: [Model Error Compensator](https://www.control-theory.com/en/model-error-compensator)
- Blog hub: [Model Error Compensator (MEC)](https://blog.control-theory.com/entry/model-error-compensator-eng)
- [YouTube: Model Error Compensator](https://youtu.be/UbEQD22V20c?si=fTFpegjDsDgVg74e) 14min, English

### 1-1 MEC (Polytopic uncertainty, PSO + LMI design)
 - (MATLAB) https://github.com/Hiroshi-Okajima/Robust-control-MATLAB_MEC01
 - [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/Robust-control-MATLAB_MEC01)
 - (Python / Google Colab) https://github.com/Hiroshi-Okajima/python-google-colab/tree/main

### 1-2 MEC with sensor noise
- (MATLAB) https://github.com/Hiroshi-Okajima/MATLAB_MEC02_sensor_noise
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC02_sensor_noise)

### 1-3 MEC with PFC to overcome NMP zeros
- (MATLAB) https://github.com/Hiroshi-Okajima/MATLAB_MEC03_withPFC
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC03_withPFC)

### 1-4 MEC for nonlinear system
- (MATLAB) https://github.com/Hiroshi-Okajima/non_linear_control_MATLAB_MEC04
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/non_linear_control_MATLAB_MEC04)

### 1-5 Signal limitation filter
- (MATLAB) https://github.com/Hiroshi-Okajima/MATLAB_MEC05_signal_limitation_filter
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC05_signal_limitation_filter)

### 1-6 Robust vehicle control with MEC
- (MATLAB) https://github.com/Hiroshi-Okajima/Vehicle_control_MEC05
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/Vehicle_control_MEC05)
- Research page: [Vehicle Control](https://www.control-theory.com/en/vehicle-control)

---

## 2: Quantized Control (Dynamic quantizer, Delta-sigma modulator)

Dynamic quantizer is a sophisticated signal processing component implemented as a linear difference equation that converts continuous-valued control signals into discrete-valued inputs for digital systems. Unlike static quantizers that operate instantaneously, dynamic quantizers maintain internal states and utilize temporal information to achieve optimal approximation of the desired continuous system behavior.

- Research page: [Dynamic Quantizer](https://www.control-theory.com/en/dynamic-quantizer)
- (MATLAB) https://github.com/Hiroshi-Okajima/MATLAB_Dynamic_Quantizer01
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_Dynamic_Quantizer01)

---

## 3: State Observer and State Estimation

State estimation from noisy or incomplete measurements. Our research covers Luenberger observers, Kalman filters, H-infinity filters, multi-rate observers for sensors at different sampling rates, and outlier-robust (MCV) observers.

- Research page: [State Estimation](https://www.control-theory.com/en/state-estimation) | [MCV Observer](https://www.control-theory.com/en/mcv-observer)
- Blog hub: [State Observer and State Estimation: A Comprehensive Guide](https://blog.control-theory.com/entry/state-observer-estimation)
- **(MATLAB) https://github.com/Hiroshi-Okajima/MATLAB_state_observer** — Luenberger, Kalman, H∞, multi-rate, and MCV observer codes
- MATLAB File Exchange: [Multi-Rate Observer](https://jp.mathworks.com/matlabcentral/fileexchange/182941) | [MCV Observer](https://jp.mathworks.com/matlabcentral/fileexchange/182942)

---

## 4: Multi-rate System Control (Cyclic reformulation)

In practical control systems, sensors and actuators often operate at different sampling rates. Our research addresses the analysis and design of state observers, feedback controllers, Kalman filters, and system identification algorithms for multi-rate systems, formulated using cyclic reformulation and LMI optimization.

- Research page: [Multi-rate System](https://www.control-theory.com/en/multi-rate-system)
- Blog articles: [Multi-Rate Observer](https://blog.control-theory.com/entry/2026/03/04/081748) | [Multirate SysID](https://blog.control-theory.com/entry/2026/03/04/233302)
- Code Ocean: https://codeocean.com/capsule/3611894/tree/v1
- Multirate Kalman Filter: https://github.com/Hiroshi-Okajima/multirate-kalman-filter

---

## 5: System Identification

System identification methods to obtain dynamical models from input-output data. Our research covers subspace identification (N4SID), cyclic reformulation for periodically time-varying (LPTV) systems, and multirate system identification. Educational materials on classical parametric methods (ARX, ARMAX, PEM) are also provided.

- Research page: [System Identification](https://www.control-theory.com/en/system-identification)
- Blog hub: [System Identification: From Data to Dynamical Models](https://blog.control-theory.com/entry/system-identification)
- **(MATLAB) https://github.com/Hiroshi-Okajima/MATLAB_system_identification** — Basic SysID, subspace, LPTV cyclic, multirate, and parametric PEM codes

---

## 6: Vehicle Control

Application of control theory to vehicle dynamics, including direct yaw-moment control for electric vehicles, adaptive cruise control, and platoon driving of welfare vehicles.

- Research page: [Vehicle Control](https://www.control-theory.com/en/vehicle-control)

---

## Education Topics about Control Engineering

### E1: Linear Matrix Inequality (LMI)

- Research page: [Linear Matrix Inequality](https://www.control-theory.com/en/linear-matrix-inequality)
- Blog article: [LMIs and Controller Design](https://blog.control-theory.com/entry/lmi-eng)
- YouTube: [Linear Matrix Inequalities](https://youtu.be/gJT_rudgnSY?si=mrtiYnEakJWn8Y14)

　[![Linear Matrix Inequality](https://user-images.githubusercontent.com/112537733/188101141-f86dee2e-ba6a-41c3-b223-e12b2da5aef6.png)](https://youtu.be/gJT_rudgnSY?si=mrtiYnEakJWn8Y14)

  - (MATLAB) https://github.com/Hiroshi-Okajima/MATLAB_fandamental_control_LMI
  - [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_fandamental_control_LMI)

### E2: Control animation (MATLAB code → mp4)
 - (MATLAB) https://github.com/Hiroshi-Okajima/MATLAB_animation

### E3: Transfer function based control
  - (Video links for Japanese students) https://github.com/Hiroshi-Okajima/control-education01-transferfunction
  - (MATLAB Livescript) https://github.com/Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-/tree/main
  - [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-)

### E4: State-space model based control
 - Blog hub: [State Feedback Control and State-Space Design: A Comprehensive Guide](https://blog.control-theory.com/entry/state-feedback-control-eng)
 - **(MATLAB / Python) https://github.com/Hiroshi-Okajima/control_state_feedback** — State feedback, pole placement, LQR, observer-based control codes
 - (Video links for Japanese students) https://github.com/Hiroshi-Okajima/control-education02-stateequation
 - (MATLAB Livescript) https://github.com/Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-/tree/main
 - [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-)

### E5: Circuits
 - (Video links for Japanese students) https://github.com/Hiroshi-Okajima/circuits-education01

### E6: Other topics
 - 制御工学チャンネル（動画500本以上の動画ポータルサイト） https://www.portal.control-theory.com
 - 電気電子チャンネル（動画200本の動画ポータルサイト） https://www.denki.control-theory.com
 - ブログ: [制御工学ブログ](https://blog.control-theory.com)
 - Control Scratch Programming: [OKJ1980](https://scratch.mit.edu/users/OKJ1980/)
