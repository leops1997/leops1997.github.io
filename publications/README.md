---
sort: 3
---

# Publications

Scientific papers, theses and other works published.


## Conference Papers

- **Enabling On-the-Fly Automotive Suspension Health Monitoring with Vision-based Vibration Model.** Leonardo Pezenatto da Silva, Antônio Augusto Fröhlich, José Luis Conradi Hoffmann, Luiz Fernando Martins Pastuch. In *2025 XV Symposium on Computing Systems Engineering (SBESC)*, pp. 1–6, 2025. [DOI: 10.1109/SBESC68008.2025.11288814](https://doi.org/10.1109/SBESC68008.2025.11288814)

  > **Abstract:** Predictive Maintenance plays a vital role in improving cost-efficiency of commercial fleets while improving reliability and safety metrics. This work presents a lightweight, vision-based framework for vibration-based suspension health monitoring that leverages video-derived vertical acceleration signals to detect anomalies on-the-fly. By classifying driving events that naturally excite the suspension (e.g., traversing speed bumps and potholes), our approach triggers condition-aware assessment of suspension health that uses a deep Autoencoder trained solely on health behavior where the reconstruction error serves as a proxy for degradation severity. The proposed solution employs CARLA simulator with custom maps and suspension configuration to emulate a wide range of fault scenarios, overcoming the lack of high-fidelity, labeled datasets. Experimental results demonstrates the model’s ability to detect suspension degradation, with a mean detection error of 19.13%. The framework operates without the need for dedicated vibration sensors or labeled data, making it highly suitable for real-world deployment in fleet-scale predictive maintenance systems.

- **Farneback Optical Flow Application for Automotive Onboard Vibration Monitoring.** Leonardo Pezenatto da Silva, Luiz Fernando Martins Pastuch. In *Anais do I Workshop Latinoamericano de Dependabilidade e Segurança em Sistemas Veiculares (SSV 2024)*, pp. 21–24, 2024. [DOI: 10.5753/ssv.2024.32624](https://doi.org/10.5753/ssv.2024.32624) · [PDF](https://sol.sbc.org.br/index.php/ssv/article/download/32624/32421)

  > **Abstract:** This research explores a vision-based vibration monitoring algorithm that may be used to detect and measure vibrations on a vehicle with an onboard camera. To achieve this, we explored Optical Flow algorithms techniques such as Lucas-Kanade, Horn-Schunck and Farneback to analyze pixel motion between frames and relate it to vibrations. For testing and validation, CARLA simulator was used to acquire the front camera image and IMU data in scenarios where the vehicle drives over road bumps and potholes. The visual vibration estimation was compared with the z-axis acceleration data of an IMU and the results shows that it is possible to use optical flow methods to detect vibration on the vehicle.
