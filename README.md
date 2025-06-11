# 🔧 Getting into ESP32

:contentReference[oaicite:1]{index=1}

---

## 🎯 Table of Contents
- [Introduction](#introduction)
- :contentReference[oaicite:2]{index=2}
- :contentReference[oaicite:3]{index=3}
- :contentReference[oaicite:4]{index=4}
- :contentReference[oaicite:5]{index=5}
  - :contentReference[oaicite:6]{index=6}
  - :contentReference[oaicite:7]{index=7}
- :contentReference[oaicite:8]{index=8}
- :contentReference[oaicite:9]{index=9}
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
:contentReference[oaicite:10]{index=10}

---

## Why ESP32?
:contentReference[oaicite:11]{index=11}
- :contentReference[oaicite:12]{index=12}
- :contentReference[oaicite:13]{index=13}
- :contentReference[oaicite:14]{index=14}
- :contentReference[oaicite:15]{index=15} :contentReference[oaicite:16]{index=16}

---

## Required Tools & Setup

### 1. ESP32 Board
:contentReference[oaicite:17]{index=17} :contentReference[oaicite:18]{index=18}.

### 2. USB Cable & Drivers
- :contentReference[oaicite:19]{index=19}
- :contentReference[oaicite:20]{index=20} :contentReference[oaicite:21]{index=21}.

### 3. Software
- :contentReference[oaicite:22]{index=22} :contentReference[oaicite:23]{index=23}  
- :contentReference[oaicite:24]{index=24} :contentReference[oaicite:25]{index=25}  

---

## Quick Start – Blink Example

1. :contentReference[oaicite:26]{index=26}  
   - :contentReference[oaicite:27]{index=27}  
     :contentReference[oaicite:28]{index=28} :contentReference[oaicite:29]{index=29}  

2. :contentReference[oaicite:30]{index=30}

3. :contentReference[oaicite:31]{index=31}  
   ```cpp
   void setup() {
     pinMode(2, OUTPUT);
   }
   void loop() {
     digitalWrite(2, HIGH);
     delay(500);
     digitalWrite(2, LOW);
     delay(500);
   }


https://www.espressif.com/
https://github.com/espressif/esp-idf
https://components.espressif.com/

https://github.com/espressif/esp-at
https://github.com/espressif/esp-homekit-sdk

https://github.com/espressif/esp-hosted

https://docs.espressif.com
https://github.com/zephyrproject-rtos/zephyr
https://github.com/espressif/esp-adf
https://github.com/espressif/esp-mesh-lite

https://github.com/espressif/arduino-esp32
https://docs.espressif.com/projects/arduino-esp32/en/latest/index.html

https://wokwi.com/
https://www.arduino.cc/en/software/
https://insights.espressif.com/

https://rainmaker.espressif.com/

https://www.espressif.com/en/contact-us/circuit-schematic-pcb-design-review

https://www.espressif.com/en/company/newsroom/news
https://www.espressif.com/en/company/newsroom/newsletter
https://developer.espressif.com/
https://www.espressif.com/en/company/newsroom/events

https://www.espressif.com/en/ecosystem/partnership-and-resource/aws-advanced-technology-partner

https://www.espressif.com/en/ecosystem/partnership-and-resource/third-party-sdks

https://evaluation.rainmaker.espressif.com/get-started#welcome-to-the-get-started-page-of-the-esp-rainmaker-evaluation-hub

https://esp32.com/

https://medium.com/the-esp-journal
https://devcon.espressif.com/
https://www.espressif.com/en/ecosystem/community-engagement/projects

https://www.espressif.com/en/ecosystem/community-engagement/books

https://github.com/esp-rs/esp-hal

https://www.espressif.com/en/ecosystem/community-engagement/courses