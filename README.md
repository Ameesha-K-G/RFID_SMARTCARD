<div align="center">
  <h1>🎫 Smart RFID Transit & Ticketing System</h1>
  <p><b>An IoT-enabled public transportation management portal featuring real-time data sync, dynamic status tracking, and automated emergency email alerts.</b></p>

  [![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=netlify)](https://rfidticketing.netlify.app/)
  [![Built With](https://img.shields.io/badge/Tech_Stack-HTML5_|_CSS3_|_JS-blue?style=for-the-badge&logo=javascript)](https://github.com/)
  [![Framework](https://img.shields.io/badge/UI_Framework-Bootstrap_5.3-7952b3?style=for-the-badge&logo=bootstrap)](https://getbootstrap.com/)
</div>

---

## 💡 The Problem & The Solution

In typical urban mass transit networks, tracking passenger balances manually creates immense operational friction, long queues, and frequent toll gate delay errors. 

This **Smart Ticketing Admin Portal** bridges the gap between web applications and hardware infrastructure. It operates as a secure administrative command hub that pulls live commuter wallet metrics straight from physical RFID readers deployed on field vehicles/gates via cloud telemetry, automatically messaging clients the moment an issue arises.

---

## ⚡ Key Engineering Features

* **Secure Admin Gateway:** Protects sensitive passenger tracking logs and API keys behind an authenticated authorization screen.
* **Live IoT Cloud Synchronization:** Polling intervals query the **Blynk IoT Cloud REST API** every 2000ms to fetch up-to-the-second commuter account balances (`V1`, `V2`, `V3` virtual nodes).
* **Automated Communication Pipeline:** Implements **EmailJS** to dispatch automated, direct alert notices to users the exact moment their transport balance drops beneath the critical threshold of **₹20**.
* **Intelligent Metrics Monitor:** A summary analytics panel at the top dynamically aggregates network errors, updating the global system status safely in real time.
* **Fully Responsive Dashboard:** Engineered with smooth CSS keyframe animation pulses (`.low-bal-active`) and designed completely mobile-first using Bootstrap 5.

---

## 🔐 Administrative Sandbox Access

Because the live application obscures tracking statistics behind an authentication barrier to safeguard data, use these simulation credentials to access and evaluate the active environment:

* **Administrator Email ID:** `admin@transit.com`
* **Sandbox Access Key:** `admin123`

---

## 🛠️ System Architecture & Data Flow

The architecture decouples hardware processing from the analytical UI layout layer:
