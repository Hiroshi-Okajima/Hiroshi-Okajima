[English](https://github.com/Hiroshi-Okajima), [日本語JP](https://github.com/Hiroshi-Okajima/Profile-Japanese)

# Hiroshi Okajima | 岡島 寛

## Profile: 

Associate proffesor at Kumamoto University, Japan (熊本大学). Research field: Control engineering, Control theory

- [Researchgate(H.Okajima)](https://www.researchgate.net/profile/Hiroshi-Okajima), [Researchmap(H.Okajima)](https://researchmap.jp/read0203288?lang=en), [ORCID(H.Okajima)](https://orcid.org/0000-0001-7621-7482)

- YouTube: [Control Engineeing Channel(10000subscribers, Japanese)](https://www.youtube.com/c/ControlEngineeringChannel/videos)

- YouTube2: [Control Engineeing Channel 2(300subscribers, English)](https://www.youtube.com/@ControlEngineeringCh/videos)

- Twitter: [@control_eng_ch](https://twitter.com/control_eng_ch)

![無題](https://user-images.githubusercontent.com/112537733/188295382-7b3892e7-38ec-4fc6-93e2-f9d575c0926c.jpg)

Hiroshi Okajima (PhD, Assoc. Prof. at Japan) [Okajima Lab., Web page(Eng)](https://www.control-theory.com/en)

Paper and proc. of international conference: [My research articles](https://www.control-theory.com/en/research-achievements) 

岡島 寛（熊本大学工学部情報電気工学科准教授）[岡島研，日本語Webページ](https://www.control-theory.com)

## 1: Model error compensator (My main research topic)

"Model Error Compensator" is a method for adding robustness to existing control systems. A structure of "model error compensator" was proposed by us, and it has been applied to various control systems. The control objective of the model error compensator (MEC) is to minimize as much as possible the effect of the model error and the disturbance in the meaning of the input-output relation. This compensator has a simple form and is easy to apply to various types of existing control systems, such as non-linear systems, control systems with time delay, non-minimum phase systems, MIMO systems, and so on. Various types of control schemes, such as the model predictive control, can be used together with the model error compensator and can achieve good robust performance. 

<img width="713" height="614" alt="image" src="https://github.com/user-attachments/assets/229323a7-5bc6-433f-9af8-4a2046132639" />

- Page: [Research page of MEC](https://www.control-theory.com/en/rt-model-error-compensator)

- [YouTube: Model Error Compensator](https://youtu.be/UbEQD22V20c?si=fTFpegjDsDgVg74e) 14min, English

### 1-1 Model error compensator (MEC)
 - (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/Robust-control-MATLAB_MEC01

 - [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/Robust-control-MATLAB_MEC01)

 - (Google Colab codes in GitHub) https://github.com/Hiroshi-Okajima/python-google-colab/tree/main

### 1-2 MEC with sensor noise 

- (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/MATLAB_MEC02_sensor_noise

- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC02_sensor_noise)
  
### 1-3 MEC with PFC to overcome NMP zeros 
- (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/MATLAB_MEC03_withPFC

- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC03_withPFC)
  
### 1-4 MEC for nonlinear system 

- (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/non_linear_control_MATLAB_MEC04
  
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/non_linear_control_MATLAB_MEC04)
  
### 1-5 Signal limitation filter 
- (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/MATLAB_MEC05_signal_limitation_filter

- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC05_signal_limitation_filter)
 
### 1-6 Robust Vehicle control 

- (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/Vehicle_control_MEC05

- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/Vehicle_control_MEC05)

## 2: Quantized control(dynamic quantizer, Delta-sigma modulator)

Dynamic quantizer is a sophisticated signal processing component implemented as a linear difference equation that converts continuous-valued control signals into discrete-valued inputs for digital systems. Unlike static quantizers that operate instantaneously, dynamic quantizers maintain internal states and utilize temporal information to achieve optimal approximation of the desired continuous system behavior. These quantizers are particularly valuable in delta-sigma modulation architectures, where they leverage oversampling and noise shaping techniques to push quantization errors to higher frequencies. The optimal design of such quantizers is crucial for achieving effective system performance in discrete-valued input applications.

- Page [Research page of quantizer](https://www.control-theory.com/en/rt-dynamic-quantizer)

  -  (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/MATLAB_Dynamic_Quantizer01
  
  - [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_Dynamic_Quantizer01)

## 3: State estimation using Median of Multiple State Candidates ([Article PDF](https://www.tandfonline.com/doi/full/10.1080/18824889.2021.1985702))

This research proposes an MCV (Median of Candidate Vectors) observer to address state estimation degradation caused by outliers in sensor outputs. The method generates multiple state estimation candidates from different time instances and selects the optimal candidate using median operations, assuming outliers occur infrequently. Observer gains are designed using Lyapunov inequalities and LMIs, with weighted median extensions for enhanced performance.

  - (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/MATLAB_state_estimation

- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_state_estimation)

## 4: Multi-rate system control based on cyclic reformulation 

- Page [Research page of multi-rate control](https://www.control-theory.com/en/rt-multi-rate-system)

- https://codeocean.com/capsule/3611894/tree/v1

## 5: Vehicle control (Research)

  - See my web page https://www.control-theory.com/en/rt-vehicle-control

## Education topics about Control Engineering

### E1: Linear Matrix Inequality 

- Page: [Education page of LMIs](https://www.control-theory.com/en/et-linear-matrix-inequality)
- YouTube: [Linear Matrix Inequalities](https://youtu.be/gJT_rudgnSY?si=mrtiYnEakJWn8Y14)

　[![Linear Matrix Inequality](https://user-images.githubusercontent.com/112537733/188101141-f86dee2e-ba6a-41c3-b223-e12b2da5aef6.png)](https://youtu.be/gJT_rudgnSY?si=mrtiYnEakJWn8Y14)

  - (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/Linear-matrix-inequality-and-control-MATLAB_fandamental_control

- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/Linear-matrix-inequality-and-control-MATLAB_fandamental_control)

### E2: Control animation (MATLAB code -> mp4)

 - (MATLAB codes in GitHub) https://github.com/Hiroshi-Okajima/MATLAB_animation

  ### E3: Transfer function based control 
  - (Video Links for Japanese students in GitHub) https://github.com/Hiroshi-Okajima/control-education01-transferfunction
   

 - (MATLAB Livescript codes in GitHub) https://github.com/Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-/tree/main

  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-)

   
 ### E4: State-space model based control
 - (Video Links for Japanese students in GitHub) https://github.com/Hiroshi-Okajima/control-education02-stateequation

 - (MATLAB Livescript codes in GitHub) https://github.com/Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-/tree/main

  [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-)

### E5: Circuits
 - (Video Links for Japanese students in GitHub) https://github.com/Hiroshi-Okajima/circuits-education01
 ### E6: Other topics
 - 制御工学チャンネル（動画500本以上の動画ポータルサイト） https://www.portal.control-theory.com
 - 電気電子チャンネル（動画200本の動画ポータルサイト） https://www.denki.control-theory.com
 - ブログ: [制御工学ブログ](https://blog.control-theory.com)
-  Control Scratch Programming: [OKJ1980](https://scratch.mit.edu/users/OKJ1980/)
