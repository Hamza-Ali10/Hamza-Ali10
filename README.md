<h1 align="center">Hi 👋, I'm Hamza Abdelrehim</h1>

<h3 align="center">
  MEng Computer Engineering · FPGA & ASIC Design · Wireless Communications · AI / ML
</h3>

<p align="center">
  <em>
    Building intelligent digital systems at the intersection of hardware and machine learning —<br/>
    from RTL-to-GDS-II silicon to deep-learning models deployed on the edge.
  </em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/hamzaalimorsi/">
    <img src="https://img.shields.io/badge/LinkedIn-hamzaalimorsi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:hamabdelrehi@mun.ca">
    <img src="https://img.shields.io/badge/Email-hamabdelrehi@mun.ca-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/Hamza-Ali10">
    <img src="https://img.shields.io/badge/GitHub-Hamza--Ali10-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/Location-St.%20John's%2C%20NL%2C%20Canada-1B2A5A?style=for-the-badge&logo=googlemaps&logoColor=white"/>
</p>

---

## 💫 About Me

I'm a **graduate researcher and engineer** at Memorial University of Newfoundland (MEng, GPA 4.0/4.0), combining deep expertise in **digital hardware design** with modern **AI/ML** methodologies.

- 🔧 **FPGA & ASIC** — Full RTL-to-GDS-II flow: Verilog/SystemVerilog, Synopsys DC synthesis, ICC2 P&R, PrimeTime STA, DFT scan insertion, low-power design  
- 📡 **Wireless Communications** — MIMO, RIS/IRS, OFDM, QPSK/QAM, BER/SNR simulation, channel modelling in MATLAB & Python  
- 🤖 **Machine Learning** — Supervised (CNN, LSTM, Transformer, XGBoost), Unsupervised (Autoencoders, Clustering), Reinforcement Learning (DQN)  
- 🧠 **Edge AI / TinyML** — INT8 quantization, TFLite deployment, MCU firmware integration  

---

## 🗂️ Project Repositories

### ⚙️ RTL / FPGA / ASIC Design 

> Full RTL-to-GDS-II flow · SystemVerilog & Verilog · Synopsys DC + ICC2 + PrimeTime

| # | Project | Highlight |
|---|---------|-----------|
| 01 | AXI4-Lite Slave Controller | All 5 channels, WSTRB, SLVERR, FSM |
| 02 | SPI Master Controller | All 4 CPOL/CPHA modes, CLK_DIV |
| 03 | I²C Master Controller | Open-drain, START/STOP/ACK, 400 kHz |
| 04 | UART Transceiver | 16× oversample, 2-FF sync, framing error |
| 05 | USB 2.0 UTMI Model | NRZI, bit-stuffing, SE0/EOP |
| 06 | AHB-to-APB Bridge | SETUP+ENABLE, HREADY stretch, 4 slaves |
| 07 | Async FIFO (CDC) | Gray-code, 2-FF sync, fill level |
| 08 | PWM + APB Controller | 8-channel, prescaler, interrupt |
| 09 | RISC-V RV32I Pipeline | 5-stage, forwarding, load-use stall |
| 10 | AXI4 Crossbar Interconnect | 2M×4S, round-robin arbitration, burst |
| 11 | Low-Power ALU (ASIC) | ICG, multi-VT, full synth+P&R+STA+DFT |
| 12 | CDC FIFO (ASIC) | Formal CDC annotations, set_false_path |
| 13 | Radix-4 Booth Multiplier | MBE, 3-stage pipeline, DC retiming |
| 14 | 32×32 Register File | 3R/2W ports, write-through bypass |
| 15 | DFT Scan Chain | 4-chain MUX-FF, STIL, TetraMAX |
| 16 | CRC-32 Engine | IEEE 802.3, parallel LFSR, verified |
| 17 | AXI-Stream Width Converter | 32↔64, TKEEP/TLAST, back-pressure |
| 18 | Clock Gating Unit | 4 domains, PMU FSM, glitch-free ICG |
| 19 | Vectored Interrupt Controller | 16-source, FIQ, APB register map |
| 20 | Low-Power Timer | Free-run/one-shot/PWM, APB, prescaler |

📁 **[→ View VLSI Portfolio Repository](https://github.com/Hamza-Ali10/VLSI-Portfolio)**

---

### 📡 Wireless Communication 

> MATLAB simulation + BER plots · SystemVerilog RTL · MATLAB↔RTL comparison testbench

| # | Project | Standard | Key Feature |
|---|---------|----------|-------------|
| 01 | QPSK Modulator/Demodulator | LTE / WiFi | BER vs Eb/N0, Gray coding, fixed-point IQ |
| 02 | OFDM Baseband TX | LTE / 5G NR | IFFT, cyclic prefix, ITU-VA multipath |
| 03 | Viterbi Decoder | LTE 4G | R=1/2 K=7, ACS units, traceback |
| 04 | LDPC Codec | 5G NR / WiFi | Base Graph BG1, min-sum BP decoding |
| 05 | Wireless CRC Engine | LTE/WiFi/BT | CRC-24A, CRC-16-CCITT, mode-select |
| 06 | CORDIC Phase Rotator | Universal NCO | 16-stage pipeline, rotation + vector modes |
| 07 | 64-Point FFT Engine | WiFi 802.11a | Radix-2 DIT, twiddle ROM, Q2.13 |
| 08 | LTE Turbo Encoder | LTE 4G | PCCC R=1/3, QPP interleaver, dual RSC |
| 09 | Bluetooth GFSK Modulator | Bluetooth 5.x | Gaussian FIR, phase accumulator, NCO |
| 10 | 5G NR Polar Encoder | 5G NR | F-kernel, reliability ordering, SC decoder |

📁 **[→ View Wireless Portfolio Repository](https://github.com/Hamza-Ali10/Wireless-Portfolio)**

---

### 🤖 AI / Machine Learning 

> PyTorch · TensorFlow/Lite · Scikit-learn · XGBoost · LightGBM · Optuna · SHAP

#### Supervised Learning
| # | Project | Libraries | Key Concept |
|---|---------|-----------|-------------|
| 01 | Multi-Class Classification Benchmark | Sklearn, XGBoost | 5-classifier CV, feature importance |
| 02 | LSTM Time-Series Forecasting | PyTorch | Stacked LSTM, early stopping, RMSE/MAE |
| 03 | TinyML / TFLite Deployment | TF Lite | INT8 quant, C-header, MCU latency |
| 04 | Signal Drift Regression | XGBoost | Temporal features, TimeSeriesSplit |
| 05 | Multi-Output 1D CNN | PyTorch | Residual blocks, Huber loss, 4-output |
| 08 | Transformer Forecasting | PyTorch | Positional encoding, attention vs LSTM |
| 09 | Gradient Boosting Ensemble | XGB+LGB+Optuna | Stacking, HPO, SHAP explainability |
| 16 | CNN Image Classification | PyTorch | Conv blocks, augmentation, label smoothing |
| 17 | NLP Text Classification | PyTorch+Sklearn | TF-IDF, LSTM, word embeddings |
| 20 | AutoML Pipeline with Optuna | Optuna, XGB | TPE sampler, joint model+HP search |

#### Unsupervised Learning
| # | Project | Libraries | Key Concept |
|---|---------|-----------|-------------|
| 06 | EDA Data Pipeline | Pandas, SciPy | Missing values, outliers, normality tests |
| 07 | Anomaly Detection Autoencoder | PyTorch | Reconstruction error, ROC-AUC > 0.95 |
| 10 | Kalman Filter + ML Fusion | NumPy, Sklearn | Signal denoising, accuracy improvement |
| 11 | Feature Engineering Pipeline | Pandas, SciPy | FFT, rolling, MI selection |
| 13 | Model Monitoring Dashboard | Matplotlib | PSI, KS-test, calibration, drift alerts |
| 14 | Unsupervised Clustering | Sklearn, SciPy | K-Means, DBSCAN, GMM, t-SNE |
| 15 | Edge AI Quantization | NumPy | INT8/16, MCU compatibility matrix |

#### Reinforcement Learning & Generative AI
| # | Project | Libraries | Key Concept |
|---|---------|-----------|-------------|
| 12 | Real-Time Inference Engine | Sklearn | Streaming, P99 latency, confidence alerts |
| 18 | Deep Q-Network (DQN) | PyTorch | Experience replay, target network |
| 19 | GAN Data Augmentation | PyTorch | cGAN, downstream accuracy boost |

📁 **[→ View AI/ML Portfolio Repository](https://github.com/Hamza-Ali10/AI-Portfolio)**

---

## 💻 Tech Stack

### Hardware Design
![Verilog](https://img.shields.io/badge/Verilog-1B2A5A?style=for-the-badge&logo=v&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1A6B72?style=for-the-badge)
![VHDL](https://img.shields.io/badge/VHDL-444?style=for-the-badge)
![FPGA](https://img.shields.io/badge/FPGA-Xilinx%20%7C%20Intel-FF6F00?style=for-the-badge)
![Synopsys](https://img.shields.io/badge/Synopsys-DC%20%7C%20ICC2%20%7C%20PT-0052CC?style=for-the-badge)

### AI / ML / DS
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-4CAF50?style=for-the-badge)
![Optuna](https://img.shields.io/badge/Optuna-0052CC?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### Programming & Tools
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![MATLAB](https://img.shields.io/badge/MATLAB-e16737?style=for-the-badge)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![TCL](https://img.shields.io/badge/TCL-1B2A5A?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 🏆 Achievements

- 🥇 **1st Place** — ASME Assiut puck-collection robot competition (led electrical team)
- 🎓 **GPA 4.0 / 4.0** — MEng Computer Engineering, Memorial University of Newfoundland  
- 📜 **Graduation Grade: Excellent** — FPGA-Based Poseidon2 Accelerator with RISC-V ISA Extension  
- 🏅 **Intel FPGA Certification** — Quartus, Altera SoC, Advanced Verilog HDL  

---

## 📡 Wireless & AI Research Focus

```text
🔷 MIMO / Massive MIMO          🔷 RIS / IRS-Assisted Channels
🔷 OFDM, QPSK, QAM              🔷 BER / SNR Performance Analysis
🔷 ML-Based Channel Estimation  🔷 Deep Learning for Signal Processing
🔷 Supervised Classification    🔷 Unsupervised Anomaly Detection
🔷 Reinforcement Learning (DQN) 🔷 TinyML / Edge AI Deployment
```


## 📫 Contact

| | |
|---|---|
| 📧 Email | [hazmaalimorsi@gmail.com](mailto:hazmaalimorsi@gmail.com) |
| 💼 LinkedIn | [linkedin.com/in/hamzaalimorsi](https://www.linkedin.com/in/hamzaalimorsi/) |
| 🐙 GitHub | [github.com/Hamza-Ali10](https://github.com/Hamza-Ali10) |
| 📍 Location | St. John's, NL, Canada |

---

<p align="center">
  <a href="https://visitcount.itsvg.in">
    <img src="https://visitcount.itsvg.in/api?id=Hamza-Ali10&icon=6&color=1"/>
  </a>
</p>

<p align="center">⭐ <em>50+ projects spanning RTL/ASIC, Wireless DSP, and AI/ML — feel free to explore and connect!</em> ⭐</p>
