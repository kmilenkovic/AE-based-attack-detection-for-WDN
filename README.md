# AE-based Attack Detection for Water Distribution Networks (WDN)

This repository contains the code and generated data used in the paper:

**Physics-Augmented Autoencoder-Based Cyber-Attack Detection for Critical Water Infrastructure**

The work proposes an autoencoder-based anomaly detection framework augmented with physics-informed features for detecting cyber-attacks in water distribution networks (WDNs). The approach targets SCADA-monitored critical water infrastructure and improves detection robustness by incorporating domain-specific hydraulic knowledge.

---
## Repository Contents

- `BATADAL_Attack_Detection.ipynb`  
  Main notebook for training and evaluating the proposed autoencoder-based attack detection method.

- `Test_different_classical_model_architectures.ipynb`  
  Experiments with classical and baseline model architectures for comparison.

- `generated_data/`  
  Generated and preprocessed datasets used in the experiments.

---
## Citation

If you use this code or the generated data in your research, please cite the following paper:

```bibtex
@inproceedings{petrovic2025physics,
  title={Physics-Augmented Autoencoder-Based Cyber-Attack Detection for Critical Water Infrastructure},
  author={Petrovi{\'c}, Katarina and Stojanovic, Branka and Saukh, Olga},
  booktitle={Proceedings of the 15th International Conference on the Internet of Things (IoT 2025)},
  year={2025},
  publisher={ACM},
  doi={10.1145/3770501.3770507}
}
````
---
## Project Context

This work was conducted within the **FFG-funded research project _SeRWas – Secure Resilient Water Management_**.

Project website:  
https://www.joanneum.at/digital/en/projects/serwas/

The SeRWas project focuses on improving the security and resilience of water management systems by developing advanced methods for cyber-attack detection, monitoring, and risk assessment in critical water infrastructure.
