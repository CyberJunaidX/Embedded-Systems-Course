# Lesson 2: Challenges in Embedded Systems (ES)

# 1. Limited Resources
Embedded systems have limited hardware resources.

- Very low RAM
- Tiny storage (ROM/Flash)
- Minimal processing power
- Limited battery / energy source

**Challenge:** Must perform efficiently with very little hardware.

---

# 2. Real-Time Requirements

A **Real-Time System** is a system where tasks must be completed within a fixed time limit.

**Examples:**
- Airbag must inflate within milliseconds after crash
- Medical monitor must show real-time heart activity

**Challenge:** Late response can cause failure or danger.

---

# Why Timing is Crucial

### Automotive
Systems like:
- ABS (Anti-lock Braking System)
- Lane assist

Need instant response.

### Medical
Devices like:
- Pacemakers
- Ventilators

Must work in real time.

### Aerospace
Delays in control systems can be life-threatening.

---

# Types of Real-Time Systems

## Hard Real-Time
Deadlines must **never** be missed.

Missing deadline = serious failure / danger.

**Examples:**
- Airbags
- Pacemakers
- Industrial robots

---

## Soft Real-Time
Small delays are acceptable, but performance reduces.

**Examples:**
- Video streaming
- Voice recognition

---

# 3. Reliability

Embedded systems must operate safely and continuously.

Failures can be dangerous.

**Examples of failure:**
- Ventilator suddenly restarting
- Robot arm going out of control

---

# Environmental Challenges

Embedded systems may face harsh conditions such as:
- Temperature
- Humidity
- Vibration

System must remain stable under these conditions.

---

# Quick Summary
- **Challenges = Limited resources + Real-time response + Reliability**
- **Real-time = Task must finish before deadline**
- **Hard RT = No delay allowed**
- **Soft RT = Small delays allowed**
