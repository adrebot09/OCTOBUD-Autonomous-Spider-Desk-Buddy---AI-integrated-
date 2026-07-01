# OCTOBUD-Autonomous-Spider-Desk-Buddy---AI-integrated-
OCTOBUD🕷️🤖
An autonomous, AI-powered spider desk companion equipped with surrounding awareness, a camera, and voice interaction.

## 💡 The Vision
* **Why am I making this?** There is big space in good desk buddies in the bot scenario especially those with good functionality and originality. Most desktop robots today are either simple toys or expensive research platforms. OCTOBUD aims to bridge that gap by creating an affordable, open-source AI desk companion with real autonomy, personality, and practical functionality. That is why I am making 'OCTOBUD' an Autonomous Spider Desk Buddy.be
* **What my project does:** Octobud sits on a desk it holds enough functionality to hold proper conversations with people recognize objects and faces,environmental awarness so it walks only around the desk and not fall off,and IOT integration for functionality.The AI initially will be made to run on cloud based API for the obvious fund reasons :P but at the end if it runs on cloud it will be more accessible.

## Features

✅ Autonomous walking

✅ Edge detection

✅ Obstacle avoidance

✅ Face recognition

✅ Object recognition

✅ Voice conversations

✅ OLED facial expressions

✅ Cloud AI

✅ Wi-Fi connectivity

✅ IoT control

✅ PC automation

✅ Modular open-source hardware

## 📂 Repository Structure
* `/firmware` - Code for the microcontroller and API integration.
* `/hardware` - CAD `.STEP`/`.STL` files and circuit schematics.
* `bom.csv` - Bill of Materials with part links for hardware funding.

Notes from adrebot - WELL this is the first time i am building a bot so it will be hell of a ride for me. This is obviously a project that will take a lot of time and a lot of learning.I will face many difficulties and failures but i aspire to overcome and actually make it into real project.
I hope to build it successfully and learn new things form this personal project and make new friends along the way and get to meet like minded people and get support form the community as I am sure I will be needing a lot of it. 

THANKS FOR READING TILL THE END :D - adrebot09

# 🗺️ OCTOBUD Development Roadmap

The development of OCTOBUD follows a modular, engineering-first approach. Rather than building the entire robot at once, every subsystem is developed, tested, and validated independently before being integrated into the final platform. This minimizes debugging complexity, improves reliability, and makes future upgrades significantly easier.

---

# Phase 0 — Planning & System Architecture

**Goal:** Define the complete system before purchasing or building hardware.

### Objectives

* Finalize hardware architecture
* Create the Bill of Materials (BOM)
* Design the software architecture
* Select communication protocols
* Create the repository structure
* Sketch the mechanical design
* Define project milestones

**Deliverables**

* Hardware block diagram
* Software flow diagram
* Initial CAD concepts
* Complete BOM

---

# Phase 1 — Core Electronics ("The Brain")

**Goal:** Build and validate the electronic foundation.

### Objectives

* Configure the ESP32
* Wi-Fi connectivity
* OTA firmware updates
* GPIO testing
* Power regulation
* Battery management
* Development environment setup

**Deliverables**

* Stable firmware
* Reliable wireless communication
* Power distribution tested

---

# Phase 2 — AI Communication

**Goal:** Establish reliable communication with cloud AI services.

### Objectives

* REST/WebSocket communication
* Authentication
* JSON parsing
* Command handling
* Response processing
* Conversation memory

**Deliverables**

* ESP32 successfully exchanges messages with the cloud AI

---

# Phase 3 — Voice Interface

**Goal:** Give OCTOBUD the ability to hear and speak.

### Objectives

* I2S microphone integration
* Speaker amplifier integration
* Audio recording
* Audio playback
* Speech-to-text
* Text-to-speech
* Wake word support (future)

**Deliverables**

* Functional voice conversations

---

# Phase 4 — Computer Vision

**Goal:** Give OCTOBUD visual perception.

### Objectives

* Camera integration
* Image capture
* Cloud vision processing
* Object recognition
* Face recognition
* Person detection

**Deliverables**

* Robot understands what it sees

---

# Phase 5 — Environmental Awareness

**Goal:** Allow OCTOBUD to safely understand its surroundings.

### Objectives

* ToF sensor integration
* Edge detection
* Obstacle detection
* Distance measurement
* Environmental mapping (basic)

**Deliverables**

* Reliable edge and obstacle detection

---

# Phase 6 — Motion System

**Goal:** Build the robotic body.

### Objectives

* CAD refinement
* 3D printing
* Servo installation
* Servo calibration
* PCA9685 integration
* Mechanical testing

**Deliverables**

* Fully assembled spider platform

---

# Phase 7 — Locomotion

**Goal:** Teach OCTOBUD to move.

### Objectives

* Standing
* Sitting
* Walking
* Turning
* Speed control
* Walking gait optimization

**Deliverables**

* Stable autonomous walking

---

# Phase 8 — Autonomous Behaviour

**Goal:** Combine perception and movement.

### Objectives

* Desk exploration
* Edge avoidance
* Obstacle avoidance
* Patrol mode
* Idle behaviours
* Basic decision making

**Deliverables**

* Robot navigates safely without user input

---

# Phase 9 — Personality & Expressions

**Goal:** Make OCTOBUD feel alive.

### Objectives

* OLED facial expressions
* Emotions
* Idle animations
* Conversational personality
* Memory system
* Behaviour states

**Deliverables**

* Interactive AI companion

---

# Phase 10 — Smart Integrations

**Goal:** Expand functionality beyond robotics.

### Objectives

* PC automation
* IoT device control
* Home Assistant support
* Desktop assistant features
* API integrations

**Deliverables**

* AI-powered desktop companion

---

# Phase 11 — Optimization

**Goal:** Improve reliability and user experience.

### Objectives

* Cable management
* Battery optimization
* Power efficiency
* Walking improvements
* Firmware optimization
* OTA updates
* Documentation

**Deliverables**

* Stable Version 1.0 release

---

# Future Versions

* Docking & self-charging
* Multi-room navigation
* Local AI processing
* SLAM mapping
* Gesture recognition
* Mobile application
* Multi-agent communication
* Swarm robotics experiments

