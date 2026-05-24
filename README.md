# 5V DC Power Supply – KiCad Design

A compact and reliable **5V DC regulated power supply** designed using **KiCad** for PCB schematic and layout development. This project converts AC/DC input voltage into a stable 5V DC output suitable for powering embedded systems, IoT devices, microcontrollers, and low-power electronics projects.

---

## Features

* Stable **5V regulated output**
* Designed using **KiCad EDA**
* Compact PCB layout
* Easy-to-fabricate single-layer PCB
* Suitable for:

  * Arduino projects
  * ESP8266 / ESP32
  * Sensors and IoT modules
  * Embedded systems

---

## Components Used

* Transformer / DC Input Jack
* Bridge Rectifier
* Filter Capacitors
* Voltage Regulator (7805)
* LED Indicator
* Resistors
* Screw Terminals / Headers

---

## Software Used

* KiCad for schematic and PCB design

Official Website: [KiCad](https://www.kicad.org?utm_source=chatgpt.com)

---

## Project Structure

```bash
5V-DC-Power-Supply/
│
├── Schematic/
│   └── 5V_DC_Power_Supply.kicad_sch
│
├── PCB/
│   └── 5V_DC_Power_Supply.kicad_pcb
│
├── Gerber/
│   └── Production Files
│
├── Images/
│   ├── Schematic.png
│   └── PCB_Layout.png
│
└── README.md
```

---

## Circuit Description

The circuit uses a regulated power supply design based on the **7805 voltage regulator IC**.

### Working Principle

1. Input voltage is applied through a DC jack or transformer.
2. Bridge rectifier converts AC to DC.
3. Capacitors filter ripple voltage.
4. 7805 regulator provides stable 5V output.
5. LED indicates power status.

---

## PCB Design

The PCB was designed with:

* Proper grounding
* Wide power traces
* Compact component placement
* Easy soldering layout

---

## Output Specifications

| Parameter      | Value       |
| -------------- | ----------- |
| Output Voltage | 5V DC       |
| Regulator      | 7805        |
| Input Voltage  | 7V – 12V DC |
| PCB Tool       | KiCad       |

---

## Applications

* Embedded Systems
* IoT Devices
* Microcontroller Projects
* Sensor Power Supply
* Educational Electronics Projects

---


## Future Improvements

* Add overcurrent protection
* Add fuse protection
* Convert to SMPS design
* Add USB output port

---
This project is open-source and available under the MIT License.
