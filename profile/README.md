# 🔐 DISTA-IoT — AI-Driven Security for the Internet of Things

> **Research group at the [Department of Science and High Technology (DISTA)](https://www.uninsubria.it/), University of Insubria, Varese, Italy.**  
> We build open, reproducible tools at the intersection of **machine learning**, **network security**, and **Industrial IoT (IIoT)**.

---

## 🧭 Research Areas

| Area | Description |
|------|-------------|
| **Intrusion Detection** | Deep learning-based IDS for IoT/IIoT networks |
| **Adversarial ML** | Decision boundary exploration and adversarial robustness |
| **Active Inference** | Bayesian optimal-control agents for cyber defence |
| **Synthetic Data** | Generative approaches to IIoT dataset augmentation |
| **Biometric Security** | ML methods applied to biometric cryptography |

---

## 🏙️ Smartville — IoT Security Testbed

Smartville is a **modular, containerised testbed** for evaluating deep-learning-based intrusion detection and mitigation in SDN-managed IoT networks. It simulates realistic attacker/victim traffic flows while giving the controller full observability.

- 📦 **Main repo**: [DISTA-IoT/insubria-smartville](https://github.com/DISTA-IoT/insubria-smartville)
- 🌐 **Docs / GitHub Page**: [dista-iot.github.io/insubria-smartville](https://dista-iot.github.io/insubria-smartville/)

| Repository | Role | Lang |
|-----------|------|------|
| [**smartville-controller**](https://github.com/DISTA-IoT/smartville-controller) | SDN controller — runs the DL-based IDS and mitigation logic | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square) |
| [**smartville-botmaster**](https://github.com/DISTA-IoT/smartville-botmaster) | Orchestrates coordinated attack campaigns across bots | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square) |
| [**smartville_attacker**](https://github.com/DISTA-IoT/smartville_attacker) | Generates adversarial / malicious traffic flows | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square) |
| [**smartville_victim**](https://github.com/DISTA-IoT/smartville_victim) | Simulates victim devices producing benign traffic | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square) |
| [**smartville-mockserver**](https://github.com/DISTA-IoT/smartville-mockserver) | Lightweight mock server for end-to-end integration testing | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square) |
| [**smartville-monitor**](https://github.com/DISTA-IoT/smartville-monitor) | Collects and visualises real-time network telemetry | ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square) |

---

## 🔬 Research Repositories

### 🧠 Active Inference Cybersecurity Zoo
**[`active_inference_cybersec_zoo`](https://github.com/DISTA-IoT/active_inference_cybersec_zoo)**  
A growing collection of cybersecurity agents built on **Active Inference** — a physics- and physiology-inspired framework for Bayesian optimal control. Current agents cover:
- 🚁 UAV defence against DDoS
- ⚡ Smart Grid protection against impersonation
- 🏠 Smart Home mitigation of spoofing
- 🚂 Railway IIoT spoofing defence
- 🛠️ General-purpose Active Inference development framework

---

### 📊 KAN vs MLP for IIoT
**[`KAN_vs_MLP_IIoT_usecase`](https://github.com/DISTA-IoT/KAN_vs_MLP_IIoT_usecase)**  
Comparative study of **Kolmogorov-Arnold Networks (KANs)** against classic **Multi-Layer Perceptrons** on industrial IoT tasks (power consumption prediction, train delay forecasting). Explores the interpretability / training-cost trade-off for resource-constrained IIoT deployments.

---

### 🏭 IIoT Synthetic Data Generation
**[`Train_IIoT_SyntheticDataGeneration`](https://github.com/DISTA-IoT/Train_IIoT_SyntheticDataGeneration)**  
Notebooks and pipelines for generating high-fidelity **synthetic IIoT traffic datasets**, addressing the chronic data-scarcity problem in industrial network security research.

---

### 🗺️ AMBE — Adversarial Decision Boundary Exploration
**[`ambe`](https://github.com/DISTA-IoT/ambe)**  
**Adaptive Multi-Scale Boundary Explorer**: a black-box algorithm for mapping the decision boundaries of ML models trained on IIoT data. Uses binary search + PCA-guided directional exploration to locate frontier points without gradient access — useful for quantifying adversarial robustness in critical infrastructure.

---

### 🔐 ML for Biometric Cryptography
**[`ML4BioCrypto`](https://github.com/DISTA-IoT/ML4BioCrypto)**  
Machine-learning approaches applied to **biometric cryptography** — combining biometric authentication signals with cryptographic key generation and verification.

---

## 📫 Contact & Collaboration

We welcome collaborations, issue reports, and dataset requests.

- 🌐 **Website**: [dista.uninsubria.it/~jesus.cevallos](http://www.dista.uninsubria.it/~jesus.cevallos/)
- 🏛️ **Affiliation**: University of Insubria — DISTA, Via O Rossi 8, 22100 Varese, Italy
- 📧 **Email**: jesusfcevallos@gmail.com

> *"Wanna create/evolve beasts alike? Contact us!"*
