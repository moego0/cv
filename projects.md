# Projects of Mohamed Ahmed Abdelraouf

A detailed catalog of cyber-physical, TinyML, AI agents, and custom hardware engineering projects built by Mohamed Ahmed Abdelraouf.

---

## 1. Local Tab Agent
- **Description**: A local, private, and repository-aware AI coding assistant extension for VS Code, published on the Open VSX Registry.
- **Technologies**: TypeScript, WebSocket, Ollama, local LLMs (Llama 3, Phi-3, Qwen-2), Node.js, VS Code API.
- **Key Achievements**:
  - Bridges the editor with local models and private browser AI tabs (ChatGPT, Claude, Gemini) via WebSocket connections to execute planning workflows for free.
  - Features distributed compute clusters (Swarm Groups) to pool CPU/GPU resources across local machines.
- **Link**: [Open VSX Registry](https://open-vsx.org/extension/moego0/local-tab-agent) | [GitHub Repository](https://github.com/moego0)
- **Metrics**: 650+ downloads.

---

## 2. Self-Built 3D Printer & PCB Lab
- **Description**: Personal laboratory workstation designed to manufacture case structures and custom PCB circuits.
- **Technologies**: Marlin Firmware, KiCad, CAD modeling (SolidWorks), Electroless Copper Plating Chemistry, electroplating.
- **Key Achievements**:
  - Built an FDM 3D printer from individual frame rails, stepper motors, and Marlin firmware configuration files.
  - Formulated a home chemical copper-deposition bath (palladium sensitization, electroless copper, acid copper electroplating) to plate double-sided through-hole vias.
- **Link**: [Request Details](mailto:bazeet298@gmail.com)

---

## 3. Schematic Sidekick
- **Description**: An AI-powered hardware design companion that converts project goals into schematics and firmware.
- **Technologies**: Python, LLMs, Schematic Generation Engine, KiCad Netlists, Firmware synthesis.
- **Key Achievements**:
  - Recommends boards and peripheral modules based on natural language inputs.
  - Synthesizes wiring lists, generates electrical netlists, and drafts initial embedded C firmware libraries.
- **Link**: [GitHub Repository](https://github.com/moego0)

---

## 4. Panic Attack Detection System
- **Description**: Wearable sensor-fusion wristband running real-time ML classifiers to predict panic attack onset.
- **Technologies**: Python, scikit-learn, Random Forest, SVM, PPG (Heart Rate), EDA (Electrodermal Activity), Temperature, Accelerometer, Arduino.
- **Key Achievements**:
  - Fuses multi-biometric sensor values to capture physiological stress spikes.
  - Employs personalized baseline calibration to dynamically adjust decision boundaries.
  - Predicts panic onset in under 1 second of threshold crossing.
- **Link**: [GitHub Repository](https://github.com/moego0/panic-attack-detector)

---

## 5. Custom Wake-Word Engine
- **Description**: TinyML audio processing pipeline to train and compile custom keyword spotting models for resource-constrained microcontrollers.
- **Technologies**: TensorFlow, TensorFlow Lite for Microcontrollers, Librosa, Python, C++, Audio DSP.
- **Key Achievements**:
  - Synthesizes audio parameters (キッチン sound overlays, pitches, time stretch) to train models on small voice datasets.
  - Extracts 2D Mel-Frequency Cepstral Coefficients (MFCC) matrices, feeding them into a 2D CNN.
  - Quantizes weights to INT8 to run under 100KB heap limitations.
- **Link**: [GitHub Repository](https://github.com/moego0)
- **Metrics**: ≈98% target accuracy.

---

## 6. EMG Bionic Hand
- **Description**: Robotic prosthetic hand controlled by Electromyography muscle signals.
- **Technologies**: Arduino, EMG sensors, Servos, Embedded C, SolidWorks CAD modeling.
- **Key Achievements**:
  - Implements differential instrumentation amplification and full-wave rectification.
  - Computes a digital exponential moving average (EMA) envelope in embedded microcontroller code.
  - Directs servo motors proportionally to muscle activation contraction force.
- **Exhibitions**: Presented at Pharos University Exhibition.
- **Link**: [GitHub Repository](https://github.com/moego0)

---

## 7. Interview Booster
- **Description**: Desktop AI copilot application providing real-time speech transcription and conversational support.
- **Technologies**: TypeScript, Local Whisper STT inference, Node.js, LLMs.
- **Key Achievements**: Runs local speech-to-text models to transcribe audio inputs and formulate answers instantly during interviews.
- **Link**: [GitHub Repository](https://github.com/moego0)

---

## 8. AI Desktop Assistant
- **Description**: Bilingual smart home and workspace assistant integrating computer vision, speech recognition, and BLE microcontrollers.
- **Technologies**: Python, PyQt6, Gemini API, OpenCV, BLE, STM32.
- **Key Achievements**: Uses camera streams and voice prompts to control room lights, run desktop tasks, and take voice notes in Arabic and English.
- **Link**: [GitHub Repository](https://github.com/moego0)

---

## 9. Micropad (Senet Labs)
- **Description**: Mechanical macro shortcut keyboard shortcut pad powered by STM32F4.
- **Technologies**: C, KiCad, STM32F4, React, Electron, USB HID.
- **Key Achievements**: Shortcut configuration dials, OTA firmware updates, React UI editor dashboard.
- **Link**: [GitHub Repository](https://github.com/moego0)
