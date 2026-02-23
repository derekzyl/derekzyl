<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0d14,40:0057FF,70:8B5CF6,100:F97316&height=220&section=header&text=Derek%20Og%27&fontSize=65&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20%7C%20Systems%20%7C%20Embedded%20%7C%20ML%20%7C%20Robotics&descSize=17&descAlignY=58&descColor=9ca3af&animation=fadeIn" width="100%"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/derekzyl)
[![GitHub](https://img.shields.io/badge/GitHub-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/derekzyl)
[![Website](https://img.shields.io/badge/cybergenii.com-0057FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://cybergenii.com)
[![Email](https://img.shields.io/badge/Email-F97316?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cybersgenii@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/message/7FQ35RMU2VVZP1)
[![Twitter](https://img.shields.io/badge/@cyber__genii-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/cyber_genii)
[![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white)](https://dribbble.com/cybergenii)
[![Behance](https://img.shields.io/badge/Behance-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://behance.net/derekzyl)

<br/>

```
╔══════════════════════════════════════════════════════════════════╗
║  Software engineer who builds from silicon to cloud.            ║
║  Package managers in Rust. IoT firmware in C++. APIs in         ║
║  TypeScript. Robots that move. Models that think.               ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

---

## 🧠 Currently Focused On

<div align="center">

| 🤖 Machine Learning | 🦾 Robotics | ⚙️ Systems Programming |
|:---:|:---:|:---:|
| Neural networks · Computer vision · TensorFlow · PyTorch · TFLite Micro · On-device inference | ROS2 · Inverse kinematics · Motion planning · Sensor fusion · IMU integration · PID control | Rust · C++ · Memory safety · High-performance computing · Embedded Rust |

</div>

> Building intelligent systems that operate at the edge — where machine learning meets embedded hardware
> and robots make real decisions in the physical world.

---

## 🚀 Flagship Projects

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Ion — C++ Package Manager
[![Rust](https://img.shields.io/badge/Rust-F97316?style=flat-square&logo=rust&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat-square)]()
[![License](https://img.shields.io/badge/MIT-0057FF?style=flat-square)]()

> *What if C++ had Cargo?*

A modern C++ package manager and linter written in **Rust**. No more CMake hell. No more dependency wrestling. One CLI, one TOML file, everything works.

```bash
ion new my-robot-arm    # scaffold C++ project
ion add eigen3 opencv   # add dependencies
ion build && ion run    # done ✨
```

**Roadmap:** PubGrub dependency resolution · package registry · memory safety linter · LSP support

[![View Repo](https://img.shields.io/badge/→%20github.com/cybergenii/ion-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybergenii/ion)

</td>
<td width="50%" valign="top">

### 🔥 ExpressBolt — Express + Mongoose Layer
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)]()
[![npm](https://img.shields.io/badge/npm-published-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/expressbolt)
[![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat-square)]()

> *One class. All your CRUD. Zero boilerplate.*

Wraps Express.js + Mongoose with a clean `CrudController` API — filtering, sorting, pagination, nested population, duplicate checks, and environment-aware errors built in.

```typescript
await crud.getMany<UserI>({
  modelData: { Model: User },
  query: req.query, // ?page=1&sort=-date
  populate: { path: "profile" }
});
```

[![View Repo](https://img.shields.io/badge/→%20github.com/cybergenii/expressbolt-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybergenii/expressbolt)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Andrea Table — React Data Table
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)]()
[![npm](https://img.shields.io/badge/npm-published-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/andrea-table)
[![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat-square)]()

> *Config-in, table-out.*

Pass one config object. Get a fully wired React data table — API fetching, multi-column sort, filter, pagination, CRUD actions, custom cell renderers, theming, auto-refresh.

```tsx
<NewTable data={{
  baseUrl: API_URL, subUrl: "/data",
  heading: [...], fn: { fetchFn },
  crud: { add: true, edit: true }
}} />
```

[![View Repo](https://img.shields.io/badge/→%20github.com/cybergenii/andrea--table-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybergenii/andrea-table)

</td>
<td width="50%" valign="top">

### 📱 Flutter Wireless — Bluetooth Package
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)]()
[![pub.dev](https://img.shields.io/badge/pub.dev-published-0175C2?style=flat-square&logo=dart&logoColor=white)](https://pub.dev/packages/flutter_wireless)
[![Status](https://img.shields.io/badge/Status-Active-10B981?style=flat-square)]()

> *Bluetooth Serial for Flutter, done right.*

Device discovery, connection management, data transfer, auto-pairing with PIN, bonding, and Bluetooth state monitoring — clean Dart API for Android and iOS.

```dart
NewFlutterBluetooth.instance
  .startDiscovery()
  .listen((r) => connect(r.device));
```

**Supports:** SPP · BLE · multi-connection · background ops

[![View Repo](https://img.shields.io/badge/→%20github.com/cybergenii/flutter__wireless-0a0d14?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cybergenii/flutter_wireless)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

### Languages
[![Skills](https://skillicons.dev/icons?i=ts,js,rust,cpp,c,python,dart,go&theme=dark)](https://skillicons.dev)

### Frontend & Mobile
[![Skills](https://skillicons.dev/icons?i=react,nextjs,flutter,tailwind,scss,vite,webpack&theme=dark)](https://skillicons.dev)

### Backend & APIs
[![Skills](https://skillicons.dev/icons?i=nodejs,express,fastapi,django,actix&theme=dark)](https://skillicons.dev)

### Databases & Cache
[![Skills](https://skillicons.dev/icons?i=postgres,mongodb,mysql,sqlite,redis,firebase&theme=dark)](https://skillicons.dev)

### DevOps & Cloud
[![Skills](https://skillicons.dev/icons?i=docker,github,githubactions,aws,vercel,heroku,nginx,linux&theme=dark)](https://skillicons.dev)

### ML & Robotics
[![Skills](https://skillicons.dev/icons?i=tensorflow,pytorch,opencv,raspberrypi,arduino&theme=dark)](https://skillicons.dev)

### Design
[![Skills](https://skillicons.dev/icons?i=figma,xd,ps,ai&theme=dark)](https://skillicons.dev)

</div>

---

### 🤖 Machine Learning & Robotics Stack

<div align="center">

| 🧠 ML Frameworks | 🦾 Robotics | 📡 Edge AI |
|:---:|:---:|:---:|
| ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) | ![ROS](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white) | ![TFLite](https://img.shields.io/badge/TFLite%20Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) |
| ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) | ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) | ![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white) |
| ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![scikit](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) | ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) | ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) |

</div>

<details>
<summary><b>🔬 ML & Robotics Details</b></summary>
<br/>

**Machine Learning**
- Computer Vision: object detection · image segmentation · real-time tracking (YOLO · MobileNet · EfficientDet)
- Model Optimization: quantization · pruning · knowledge distillation for edge deployment
- On-Device Inference: TFLite Micro on ESP32/STM32 · ONNX Runtime · CoreML
- Data: NumPy · Pandas · Matplotlib · OpenCV pipelines

**Robotics**
- ROS2: nodes · topics · services · actions · launch files
- Motion Planning: PID control · inverse/forward kinematics · trajectory planning
- Sensor Fusion: IMU (MPU6050) · encoders · LiDAR · ultrasonic · camera integration
- Actuation: servo · stepper · BLDC motors · ESC control
- Perception: depth estimation · lane detection · obstacle avoidance

**Embedded ML**
- Running neural nets on microcontrollers (no OS, no GPU)
- FreeRTOS task scheduling with inference pipelines
- Custom datasets, labeling, and training for embedded targets

</details>

---

### 🔌 Embedded Systems & IoT

<div align="center">

| 🔲 Microcontrollers | 📡 Protocols | 🔧 Toolchains |
|:---:|:---:|:---:|
| ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white) | ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white) ![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white) | ![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white) |
| ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) | ![WebSocket](https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white) ![CoAP](https://img.shields.io/badge/CoAP%20%2F%20Modbus-555?style=flat-square) | ![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=flat-square&logo=espressif&logoColor=white) ![CubeMX](https://img.shields.io/badge/CubeMX-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white) |
| ![RPi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white) ![RPiPico](https://img.shields.io/badge/RPi%20Pico-A22846?style=flat-square&logo=raspberrypi&logoColor=white) | ![I2C](https://img.shields.io/badge/I2C%20%2F%20SPI%20%2F%20UART-555555?style=flat-square) ![GSM](https://img.shields.io/badge/GSM%20%2F%20LTE-F97316?style=flat-square) | ![FreeRTOS](https://img.shields.io/badge/FreeRTOS-003153?style=flat-square) ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white) |

</div>

<details>
<summary><b>📋 Full Embedded Capabilities</b></summary>
<br/>

**Hardware Design**
- Circuit Design: digital & analog electronics · power supply design · voltage regulators
- PCB Tools: KiCad · Eagle · Fritzing · Proteus · Multisim
- Debugging: JTAG · SWD · logic analyzers · oscilloscopes · serial monitors

**Firmware**
- Languages: C · C++ · MicroPython · Embedded Rust
- RTOS: FreeRTOS · bare-metal · Arduino loop model
- OTA: ESP-IDF OTA · Arduino OTA · custom HTTP update servers
- Power: deep sleep · light sleep · wake stubs · battery optimization

**Sensors & Peripherals**
- Environmental: DHT11/22 · BMP280/BME280 · MQ-series gas sensors
- Motion: MPU6050 (IMU) · HC-SR04 (ultrasonic) · PIR · encoders
- Display: OLED SSD1306 · TFT ILI9341 · e-Paper · 7-segment
- Connectivity: SIM800L/SIM7600 (GSM/LTE) · NEO-6M (GPS) · nRF24L01 (RF)
- Actuators: servo · stepper · DC motor L298N/L293D · BLDC + ESC · relay modules
- Storage: SD card SPI · EEPROM · LittleFS · SPIFFS

**IoT Architecture**
- MQTT (Mosquitto/HiveMQ) → API → database pipeline
- BLE + mobile app provisioning · captive portal Wi-Fi setup
- Fleet OTA · telemetry dashboards · threshold alerting
- Edge ML inference with TFLite Micro

</details>

---

## 📦 All Open Source

<div align="center">

| Project | Stack | Description | Links |
|---|---|---|---|
| **ion** | ![Rust](https://img.shields.io/badge/-Rust-F97316?style=flat-square&logo=rust&logoColor=white) | C++ package manager — TOML manifests, CMake generation, Cargo-style CLI | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/ion) |
| **expressbolt** | ![TS](https://img.shields.io/badge/-TS-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000?style=flat-square&logo=express) | CRUD middleware for Express + Mongoose | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/expressbolt) [![npm](https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/expressbolt) |
| **andrea-table** | ![TS](https://img.shields.io/badge/-TS-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) | Config-driven React data table with API, CRUD, sorting, filters | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/andrea-table) [![npm](https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/andrea-table) |
| **mich-pages** | ![TS](https://img.shields.io/badge/-TS-3178C6?style=flat-square&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) | CRUD page generator — define fields, get full forms | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/mich-pages) [![npm](https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/mich-pages) |
| **flutter_wireless** | ![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat-square&logo=dart&logoColor=white) | Flutter Bluetooth Serial — discovery, connection, data transfer | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/flutter_wireless) [![pub](https://img.shields.io/badge/-pub.dev-0175C2?style=flat-square&logo=dart&logoColor=white)](https://pub.dev/packages/flutter_wireless) |
| **repoflow** | ![TS](https://img.shields.io/badge/-TS-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) | CLI + web UI for GitHub repo automation | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/repoflow) [![npm](https://img.shields.io/badge/-npm-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/repoflow) |
| **termux-nvim** | ![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white) | One-command Neovim dev environment for Android via Termux | [![GitHub](https://img.shields.io/badge/-Repo-0a0d14?style=flat-square&logo=github)](https://github.com/cybergenii/termux-nvim) |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=derekzyl&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0a0d14&title_color=0057FF&icon_color=F97316&text_color=9ca3af"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=derekzyl&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0a0d14&title_color=0057FF&text_color=9ca3af"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=derekzyl&theme=tokyonight&hide_border=true&background=0a0d14&ring=0057FF&fire=F97316&currStreakLabel=9ca3af&sideLabels=9ca3af&dates=9ca3af&stroke=0a0d14" />

</div>

---

## 🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=derekzyl&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F97316,40:8B5CF6,70:0057FF,100:0a0d14&height=130&section=footer&animation=fadeIn" width="100%"/>

### *"Building bridges between silicon and intelligence —*
### *from embedded firmware to robotic autonomy."*

<br/>

**Open to collaborations · Freelance · Research · Open Source**

[![Email](https://img.shields.io/badge/cybersgenii%40gmail.com-F97316?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cybersgenii@gmail.com)
[![Website](https://img.shields.io/badge/cybergenii.com-0057FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://cybergenii.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/message/7FQ35RMU2VVZP1)

</div>
