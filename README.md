# .github
#  IA\_AUT\_ECO: The Fabless Architecture for Augmented Autonomy

**IA\_AUT\_ECO** is a French **Deep Tech** company specializing in the design of secure architectures for critical robotic and cognitive assistance.

We operate on a **Fabless** and **B2C Premium** model: we design the sovereign software, provide the safety standards (ISO, NIS 2), and certify a network of approved companies for hardware installation and maintenance.

**Our Motto:** *Let's be Useful. Cognitive Life Insurance.*

---

## 🛡️ The WINTERHOLD Framework: The Trust Infrastructure

The **WINTERHOLD** architecture is the guarantor of resilience, security, and auditability for the entire ecosystem.

### 1. The System Core
* **HEARTHFIRE (Hardened OS):** A minimalist **FreeBSD Fork** serving as the critical OS. It enforces a **Zero Trust Architecture (ZTA)**, strict process isolation, and integrates **Post-Quantum Cryptography (PQC)** for future resilience.
* **FORT GRAYMOR (IoT/Edge Hub):** The central pivot. Also built on **FreeBSD**, it acts as a secure, redundant gateway. It filters, validates, and normalizes encrypted events from the sensors (Jetson-Net) before transmitting them to the AI backend.
* **DELPHINE (Data Core):** The sovereign **On-Premise** database for the ethical management of critical data (medical and social).

### 2. Intelligence and Audit
* **MASAQ:** The AI orchestrator that manages model inference on **NVIDIA Jetson** chips and enterprise-level servers. It handles CPU/GPU redundancy (AMD/Intel/NVIDIA) for service continuity.
* **SKALD:** The primary Cognitive Agent. It uses **SLMs** and **GNNs** to translate raw data into **Semantic Intentions** (e.g., translating "pixels" into "turn right now").
* **YSGRAMMOR:** The ethical audit module. It traces the entirety of the AI's decision cycle (Proof of Intent), essential for compliance and legal accountability.

---

## 🤖 The Physical and Software Agents

The architecture supports a set of physical and cognitive agents designed for autonomy.

### Robotic Agents (Certified Hardware)
* **DAWNSTAR:** The mobility agent (robotic wheelchair). It executes navigation, critical motor control, and sensor fusion (ROS 2).
* **ESBERN:** The manipulator agent (robotic companion arm). Ensures fine physical interactions with the environment. 

[Image of robotic arm on wheelchair]


### "Companion" Software Suite (Premium Cognitive Modules)
These heavy modules are the core of the B2C premium subscription:
* **MNEMOSYNE:** Total memory prosthesis (local RAG) and indexing of daily events.
* **VESTA:** Guardian of routines and detection of anomaly in habits.
* **KAIROS:** Reality anchor and management of confusion states.
* **HERMES:** Social decoder and communication assistance.
* **HYGIE:** Pharmacological vigilance and compliance via computer vision.

### Universal Demonstration
* **DRAGONBORN:** The mobile application (Kotlin/Go/TFLite) that demonstrates the power of **SKALD** on a consumer smartphone. It translates the visual world into semantic instructions.

---

## 🤝 Premium B2C Model & Delegated Maintenance

Our Deep Tech model is directly linked to a premium service, without the burden of massive B2C maintenance payroll.

* **Product:** A resilient life infrastructure (redundant servers, dual-circuit Jetson/equivalent cameras, external drone potential).
* **Distribution:** Direct B2C sales, but physical installation and maintenance are delegated to a network of **Approved Companies** trained and audited by IA\_AUT\_ECO.
* **Revenue:** Focused on **Security and Cognitive Service Subscriptions** (PQC, AI updates) rather than relying solely on single-unit hardware margin.

---

## 🛠️ Key Technical Stack

* **OS/Security:** FreeBSD (Hearthfire/Fort Graymor), ZTA, mTLS, PQC.
* **AI/Edge:** NVIDIA Jetson, Go, Python, TFLite, SLM.
* **Robotics:** ROS 2, C++, Sensor Fusion.
* **Orchestration:** Kestra (Monitoring, SBOM).

---

We are seeking partners and investors who share our vision of sovereignty and utility.

