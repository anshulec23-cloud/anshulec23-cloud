# Anshul

**Final-year B.E. Electronics &amp; Communication — Mangalore, India**

I build systems for environments where something is actively trying to break them: industrial control security, computer-vision forensics, and the embedded hardware underneath both.

**Project write-ups → [bergg.me](https://bergg.me)**

---

### Focus

- **ICS / OT security** — inline zero-trust gateways, signed field telemetry, physical enforcement on ESP32 hardware rather than alerts after the fact
- **Applied ML for security** — anomaly detection, attack classification, and explainable forensics where the explanation is part of the output
- **Embedded &amp; edge** — ESP32 firmware, fieldbus framing, per-device key exchange, offline-first systems

---

### Projects

| Project | What it does | Stack |
| --- | --- | --- |
| **[aegis-ics](https://github.com/anshulec23-cloud/aegis-ics)** | Zero-trust gateway and physical safety enforcer for industrial control systems. Validates every frame, tests setpoints against physical stability limits, de-energises a relay in 12.74 ms. [Write-up](https://bergg.me/projects/aegis-ics.html) | Python, Flask, ESP32, scikit-learn |
| **[digital-surveillance-system](https://github.com/anshulec23-cloud/digital-surveillance-system)** | Real-time video anomaly detection. YOLOv8 → DeepSORT → LSTM autoencoder, trained on normal footage only. [Write-up](https://bergg.me/projects/sentinel.html) | PyTorch, YOLOv8, FastAPI |
| **[image-forgery-detection](https://github.com/anshulec23-cloud/image-forgery-detection)** | Document screening via a dual-stream ResNet18 over raw RGB and Error Level Analysis, with Grad-CAM evidence maps. [Write-up](https://bergg.me/projects/image-forgery-detection.html) | PyTorch, ResNet18, Streamlit |
| **[aegis-bank](https://github.com/anshulec23-cloud/aegis-bank)** | Five-agent LangGraph pipeline that detects OT attacks, isolates the device, and prices the incident in downtime, SLA and regulatory exposure. [Write-up](https://bergg.me/projects/cyberrisk.html) | LangGraph, FastAPI, MQTT, React |
| **[bergg-tactical-recon](https://github.com/anshulec23-cloud/bergg-tactical-recon)** | Offline-first navigation console. Local Valhalla routing with automatic OSRM fallback, telemetry swept along the route. [Write-up](https://bergg.me/projects/tactical-recon.html) | JavaScript, Python, Docker |

---

### Stack

`Python` · `JavaScript` · `C/C++ (ESP32)` · `PyTorch` · `scikit-learn` · `FastAPI` · `Flask` · `MQTT` · `Docker` · `GitHub Actions`

---

<sub>Each project README documents its own limits — what is tested, what is simulated, and what has not been validated yet. The write-ups at <a href="https://bergg.me">bergg.me</a> go into why each system is built the way it is.</sub>
