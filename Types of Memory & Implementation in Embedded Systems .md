# Lesson 5: Types of Memory & Implementation in Embedded Systems

# Types of Memory in Embedded Systems

## 1. SRAM (Static RAM)
- Fast, stable memory
- Used for registers and internal caches
- Expensive → used in small amounts

---

## 2. DRAM (Dynamic RAM)
- Slower than SRAM
- Cheaper and denser
- Used when large RAM is needed

---

## 3. EEPROM
- Electrically erasable memory
- Used for small data storage
- Stores:
  - Calibration values
  - Device settings

---

## 4. NOR Flash
- Used for storing program code
- Supports **random access**
- Allows **XIP (Execute In Place)**

---

## 5. NAND Flash
- Used in SD cards, USB drives
- High density and low cost
- Good for storage
- Slower for direct execution

---

# Memory Architecture in Embedded Systems

## 1. Von Neumann Architecture
- Same memory for code and data
- Single bus
- Simple design
- Limited performance due to bandwidth bottleneck

---

## 2. Harvard Architecture
- Separate memory for code and data
- Separate buses
- Faster and more efficient
- Allows parallel access

---

## 3. Modified Harvard Architecture
- Hybrid of both
- Used in most modern microcontrollers
- Balances flexibility + performance

---

# Real-World Memory Implementation Techniques

## 1. XIP (Execute In Place)
- Code runs directly from Flash
- No need to copy into RAM

---

## 2. Shadowing
- Critical code copied from Flash → SRAM
- Improves execution speed

---

## 3. External Memory Interfaces
- Connect external memory (PSRAM / Flash)
- Expands system memory without redesigning chip

---

## 4. Cache & Prefetch Buffers
- Bridge speed gap between CPU and memory
- Improve performance by reducing wait time

---

# Memory Management Techniques

- Static Memory Allocation → fixed memory assignment
- Memory Pools → pre-allocated blocks for efficiency
- Direct Memory Access (DMA) → data transfer without CPU load
- Wear-Leveling → extends Flash memory lifespan
- Low Power Memory Modes → reduce energy consumption

---

# Quick Summary
- **SRAM = Fast but expensive**
- **DRAM = Large but slower**
- **EEPROM = Small data storage**
- **NOR Flash = Code + XIP**
- **NAND Flash = Storage (USB/SD)**

- **Von Neumann = simple but slower**
- **Harvard = fast (separate buses)**
- **Modified Harvard = modern standard**

- Techniques: **XIP, Shadowing, DMA, Cache, Wear leveling**
