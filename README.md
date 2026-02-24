
# 🏭 Industrial Automation & PLC Control Systems Portfolio

**Authors:** Paula Contreras & Mateo Sánchez  
**Institution:** Universidad del Azuay (Ecuador) - Faculty of Science and Technology  
**Date:** 2023  

> 🎓 **Academic Disclaimer:** *This manual was developed as a comprehensive academic project for the Electronic Engineering B.S. program. It is shared here as an open-source portfolio piece to demonstrate proficiency in industrial automation, PLC programming, system simulation, and technical documentation.*

## 📖 Overview
This repository contains a **60-page technical manual** detailing the architecture, configuration, and simulation of industrial control pipelines using **Siemens Simatic S7-1200 PLCs**. 

***Note:** While the primary text of the document is in Spanish, the technical diagrams, IP configurations, Ladder Logic blocks, and system architectures are universal engineering standards easily readable by automation professionals worldwide.*

## 🛠️ Core Technologies & Protocols Demonstrated
This manual serves as proof of hands-on experience with hardware integration and industrial protocols, which are essential for developing automated testing pipelines and AI-driven workflows in power systems:

* **Modbus-RTU & TCP/IP:** Master-Slave architecture configuration, physical layer setup (RS-485), and real-time signal flow management using `MB_COMM_LOAD` and `MB_MASTER` blocks.
* **Factory I/O Integration:** Virtual plant simulation for manufacturing projects (e.g., automated sorting pipelines) to derive test sequences, map sensors/actuators, and validate expected outcomes before physical deployment.
* **Profinet (ISO on TCP):** Open User Communication implementation using `TSEND_C` and `TRCV_C` blocks for controller-to-controller data exchange.
* **TIA Portal & Ladder Logic:** Automated control mapping, continuous physical variable tuning (PID control for water tank levels), hardware troubleshooting, and IP address management.

## 📄 Document Contents (Key Practices)
The manual is divided into four main practical implementations:

1. **Practice 1:** Programming and Communication of a PLC with FACTORY I/O for manufacturing simulations.
2. **Practice 2:** PID Control configuration for continuous physical variables.
3. **Practice 3:** Modbus-RTU Master/Slave communication implementation.
4. **Practice 4:** Profinet communication via Open User Communication (ISO on TCP).

## ⚖️ License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the LICENSE file for details. You are free to use this material for educational purposes, provided that appropriate credit is given to the original authors.
