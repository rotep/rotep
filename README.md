# Hi there, I'm Rotep👋

**Bridging Humanities & Tech. Full-stack Hardware & Software Engineer exploring VR, AI, and Network Society.**

I am a researcher and engineer based in Gunma, Japan, currently studying at Gunma University's Faculty of Informatics. My work focuses on the intersection of Information Technology (VR/AI/Hardware) and Humanities (Sociology/Psychology), treating my career formation as a process of transforming my "self-narrative" through avatars.

---

<p align="center">
  <a href="https://nekomario28.github.io/interactive-project-map/u/?username=rotep&style=galaxy-classic">
    <img width="740" src="https://raw.githubusercontent.com/rotep/rotep/HEAD/project-map/galaxy.svg" alt="rotep project map" />
  </a>
</p>

### 🔭 What I'm working on

Most of my projects live in private repositories. Linked names are public; the rest are described here only.

**🤖 AI agents, kept on a leash**
*   **KYOKAOS** *(Rust)*: A capability sandbox for MCP agents. It derives least-privilege profiles from MCP tool schemas and enforces them in the kernel with Landlock and seccomp, built on [Sandlock](https://github.com/multikernel/sandlock).
*   **Synapse** *(TypeScript monorepo)*: My engineering control room. It searches my design decisions with provenance, observes my own projects evidence-first, and routes infrastructure changes through human approval: agents may request a change, but never approve or apply it.
*   **Running Claude Code across many repositories**: Written decision records for how coding agents work in my projects, a merge gate that checks CI and reservations before squash-merging, and an unattended milestone runner driven from Discord with separate builder, evaluator and supervisor roles.
*   **[spillway](https://github.com/rotep/spillway-ci)** *(JavaScript, zero dependencies)*: Overflow GitHub Actions CI to your own hardware when GitHub-hosted minutes run out. Ephemeral just-in-time runners, no inbound ports, and jobs that started and failed are never papered over.
*   **Lab operations agent** *(Python)*: An assistant for a university AI circle. GitHub events become drafts written by an LLM, and nothing is posted until a human approves it in Discord.

**🧪 Systems & security research**
*   **AyanaOS** *(Rust)*: A from-scratch x86_64 kernel with kernel-native capabilities and transactional rollback: ring-3 programs, virtio networking and storage, memory that survives reboots, and an in-OS agent that asks an LLM through its own userland network stack. 62 self-test scenarios run under QEMU in CI.
*   **kevlag-jp** *(Python, in development)*: A research tool that estimates how many internet-exposed VPN and edge devices in Japan still run versions with known-exploited vulnerabilities (CISA KEV). It uses only data that third parties already publish, never contacts the devices, and publishes national aggregates only.

**🛠️ Hardware R&D**
*   **TepTracker**: A 10-point VR full-body tracking system based on nRF52840 & LSM6DSV.
*   **[AshiCon](https://github.com/rotep/AshiCon)**: Ankle-worn wearables that replace a gamepad's two analog sticks. A near-infrared sensor array reads the ankle, an IMU gates the input, and the device enumerates as a standard USB HID gamepad.
*   **[ScissorBall 36](https://github.com/rotep/scissorball)**: A low-profile split keyboard with laptop-style scissor switches and a 25 mm thumb trackball (RP2040, QMK, KiCad). Designed and DRC-clean, not yet built.
*   **mmWave pose estimation** *(early)*: Upper-body pose from 60 GHz mmWave radar point clouds fused with IMU trackers, output as joint rotations for the VMC protocol.

**🌐 Infrastructure & Networking**
*   **[rotep-homelab](https://github.com/rotep/rotep-homelab)**: A two-node Proxmox VE cluster and a k3s HA cluster, managed with GitOps (Argo CD) and monitored with Prometheus, Loki and Grafana. Built by pair-programming with Claude Code.
*   Operating a home lab and VPS with **Proxmox VE**, **Docker**, **Tailscale Subnet Router HA**, and **Xray (VLESS+REALITY)**.

**📚 Research & Community**
*   **Academic Research:** Investigating Avatar Identification and "Layered Self" formation in network societies at the Comparative Culture & Sociology Lab.
*   **Habataki (Gunma University AI Circle):** Representative of a 20-member circle; presented at JSAI 2026.
*   **AI Evaluation & Governance:** Working on RLHF data correction and QA for large-scale AI projects (OneForma / Centific), and acting as a Google Gemini Student Ambassador.

---

### 🛠️ Tech Stack & Skills

**Languages**  
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**AI Agents & Web**  
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflareworkers&logoColor=white)

**Systems & Security**  
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Landlock](https://img.shields.io/badge/Landlock_&_seccomp-Sandboxing-555555?style=for-the-badge)
![QEMU](https://img.shields.io/badge/QEMU-FF6600?style=for-the-badge&logo=qemu&logoColor=white)
![Xray](https://img.shields.io/badge/Xray_VLESS-Security-800080?style=for-the-badge)

**Infrastructure & Networking**  
![Ubuntu](https://img.shields.io/badge/Ubuntu_Server-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![k3s](https://img.shields.io/badge/k3s-FFC61C?style=for-the-badge&logo=k3s&logoColor=black)
![Argo CD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale_HA-FFFFFF?style=for-the-badge&logo=tailscale&logoColor=black)

**Hardware & Engineering**  
![Microcontrollers](https://img.shields.io/badge/nRF52840-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![RP2040](https://img.shields.io/badge/RP2040_&_QMK-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![Hardware](https://img.shields.io/badge/Circuit_Prototyping-FFB900?style=for-the-badge&logo=arduino&logoColor=white)
![Sensors](https://img.shields.io/badge/LSM6DSV_&_Optical-Sensors-4CAF50?style=for-the-badge)

**Creative**  
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Unity](https://img.shields.io/badge/Unity_VRChat_SDK-100000?style=for-the-badge&logo=unity&logoColor=white)
![Premiere Pro](https://img.shields.io/badge/Premiere_Pro-9999FF?style=for-the-badge&logo=adobe-premiere-pro&logoColor=white)

---

### 📫 Connect with me

- 🌐 **Portfolio Web:** [rotep.site](https://rotep.site)
- 💼 **LinkedIn:** [tsukamotoriku](https://www.linkedin.com/in/tsukamotoriku/)
- 📝 **Qiita:** [rotep](https://qiita.com/rotep)
- ✉️ **Contact:** tsukamoto.rk@gmail.com
