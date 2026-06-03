## CyberGlitch403 // Welcome to my trials and errors!

## 🛠️ Project 0: Frankenstein CyberPower Revival (Active)

Follow along as I attempt this beautiful Frankenstein build. I am completely new to hardware modification and coding, but I'm diving in headfirst to see exactly how far I can stretch hardware cross-compatibility.

### 🎯 My Learning Objectives & Future Lab Goals
I am building this machine as my ultimate hands-on classroom. Once I figure out the hardware modifications, my goal is to learn how to install an advanced system (**Lenovo T14 Gen 1 AMD Ryzen Pro motherboard**) so I can teach myself cybersecurity from the ground up, including:

* **Host Operating System:** Proxmox VE / Linux Hypervisor (for spinning up isolated virtual testing environments)
* **Dedicated Routing:** Outfitted with a dedicated hardware router to segment all home lab testing traffic completely away from the primary home network.
* **Defensive Monitoring:** Active Honeypot deployments paired with real-time threat intelligence feeds.
* **Security Operations:** SIEM (Security Information and Event Management) pipelines and central log aggregation.
* **Simulation Testing:** An automated attack/defense range to safely launch and mitigate adversarial tactics.
* **Network Auditing:** IoT and network security auditing frameworks.
* **Advanced Research:** A completely isolated malware analysis sandbox.

---

<details>
<summary>🔍 Click here to view the Lab Journal, Costs & Progress</summary>

### 📈 Project Ledger (Current Total Cost: $111.81)


| Component / Part | Source | Cost | Status |
| :--- | :--- | :--- | :--- |
| Vintage CyberPower Laptop Chassis | eBay | $54.44 | In Lab |
| Arduino Micro with Headers [A000053] | Amazon | $23.00 | Ordered |
| Horinktor MCP23017 DIP-28 Chip | Amazon | $8.49 | Ordered |
| 24-Pin 1.0mm to DIP 2.54mm Board | Amazon | $8.50 | Ordered |
| MECCANIXITY 10-Pin 0.5mm to DIP 2.54mm Board | Amazon | $8.39 | Ordered |
| MB-102 830-Point Breadboard Kit + Wires | Amazon | $8.99 | Ordered |

---

### 📓 Step 1: The Teardown & Harvest
* **What I Did:** Completely gutted the vintage CyberPower laptop. Carefully saved all the original casing screws, the plastic frame, the screen and the raw keyboard/trackpad ribbon cables. **WARNING!** She was in gnarly shape before I started this process. I bought it 50% for that reason. I love that she has wear and tear. How cool is it to see this wild beat up laptop and it actually operate an amazing system. Plus the vintage `CyberPower` branding completely won me over.
* **Issues / Roadblocks:** The original screen and internal parts are completely ancient and useless for a modern system, leaving me with a totally empty plastic shell to figure out.
* **Current Status:** Moving to the peripheral translation phase.

[![Vintage CyberPower Chassis Teardown Step 1](chassis-01.jpg)](chassis-01.jpg)
[![Vintage CyberPower Chassis Teardown Step 2](chassis-02.jpg)](chassis-02.jpg)
[![Vintage CyberPower Chassis Teardown Step 3](chassis-03.jpg)](chassis-03.jpg)
[![Vintage CyberPower Chassis Teardown Step 4](chassis-04.jpg)](chassis-04.jpg)
[![Vintage CyberPower Chassis Teardown Step 5](chassis-05.jpg)](chassis-05.jpg)
[![Vintage CyberPower Chassis Teardown Step 6](chassis-06.jpg)](chassis-06.jpg)
[![Vintage CyberPower Chassis Teardown Step 7](chassis-07.jpg)](chassis-07.jpg)
[![Vintage CyberPower Chassis Teardown Step 8](chassis-08.jpg)](chassis-08.jpg)
[![Vintage CyberPower Chassis Teardown Step 9](chassis-09.jpg)](chassis-09.jpg)
[![Vintage CyberPower Chassis Teardown Step 10](chassis-10.jpg)](chassis-10.jpg)

---

### 📓 Step 2: Architecture Design & Sourcing
* **What I Did:** Measured the vintage ribbon cables (24-pin keyboard and 10-pin trackpad). Discovered the keyboard is 1.0mm pitch and the trackpad is 0.5mm pitch. 
* **Issues / Roadblocks:** Realized the Arduino Micro doesn't have 34 physical holes to plug all these lines into! I had to research how to solve a pin bottleneck before I even bought my parts. I also had to dodge "double-row" adapter boards that would have short-circuited my trackpad on a breadboard.
* **Current Status:** Added a MCP23017 expander chip to my order to give the Arduino extra pins. Everything is officially ordered; waiting for delivery so I can start learning how to wire it up!

---

### 📓 Step 3: Breadboard Arrival & Learning to Code (Next Phase)
* **What I Did:** 
* **Issues / Roadblocks:** 
* **Current Status:** 

</details>

---

## 📱 Project 1: BlackBerry Restomod (Zinwa Q25) [Future Phase]

My next upcoming project is a BlackBerry shell modification: retrofitting a Zinwa Q25 platform inside a vintage BlackBerry chassis to explore compact hardware routing.


