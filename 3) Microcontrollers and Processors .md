# Lesson 3: Microcontrollers and Processors

# What is a Microcontroller?
A **microcontroller** is a **small computer on a single chip**.

It contains:
- CPU (Central Processing Unit)
- RAM (Random Access Memory)
- ROM / Flash memory
- Input / Output (I/O) ports
- Timers, ADCs, communication interfaces

---

# Real-Life Analogy

Think of a microcontroller like a human body:

- **Eyes & Ears → Sensors (Input)**
- **Brain → CPU (Processing)**
- **Arms / Voice → Actuators or Displays (Output)**

---

# Microcontroller vs Microprocessor

| Microcontroller | Microprocessor |
|---|---|
| Specific task | General-purpose computing |
| CPU + RAM + ROM + I/O | Only CPU |
| Low cost | Higher cost |
| Very low power | High power |
| Compact | Larger, needs extra chips |
| Used in embedded systems | Used in computers/laptops |

---

# Microcontrollers in Embedded Systems

Embedded systems need to:
- Run specific tasks
- Be compact & affordable
- Use very little power

Why microcontrollers?
- Low cost
- Battery operated
- All components built-in
- Reliable for years
- Easy to program

---

# Common Applications

- **Microwave** → Controls timing, heating, display
- **Car** → Airbags, sensors, auto wipers
- **Camera** → Focus and shutter control
- **Bluetooth Earphones** → Audio + battery management
- **Smart Light** → App control, brightness adjustment

---

# Processor Cycle

Every microcontroller works in a cycle:

### 1. Fetch
Get instruction from memory

### 2. Decode
Understand instruction

### 3. Execute
Perform action

**Memory Trick:** **F-D-E**  
(Fetch → Decode → Execute)

---

# Role of Processor in Microcontroller

Processor is the **core decision-maker**.

It:
- Reads sensor data (example: temperature)
- Compares values / performs calculations
- Sends signals to motors, displays, alarms
- Stores important data/settings in memory

---

# Complete Control Components

### ADC (Analog to Digital Converter)
Converts analog signals into digital data.

### Timers
Used for delays, counting, scheduling tasks.

### Serial Ports
Used for communication between devices.

Types:
- UART
- SPI
- I2C

---

# Quick Summary
- **Microcontroller = Small computer on one chip**
- Contains **CPU + RAM + ROM + I/O**
- Used in **embedded systems**
- Processor cycle = **Fetch → Decode → Execute**
- Extra control via **ADC, Timers, Serial Ports**
