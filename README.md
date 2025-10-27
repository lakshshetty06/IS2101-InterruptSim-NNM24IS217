# InterruptController

A simple Java simulation of an **Interrupt Controller** handling interrupts from multiple devices (Keyboard, Mouse, and Printer).  
The program demonstrates **multithreading**, **priority-based interrupt handling**, and **interrupt masking**.

---

## 🧠 Overview

The `InterruptControllerShort` program simulates how an interrupt controller manages requests from different devices.  
Each device runs in its own thread and periodically generates interrupt requests, which are then processed by an interrupt handler thread.

- Devices: `Keyboard`, `Mouse`, and `Printer`
- Each device has a **priority** (lower number = higher priority)
- Devices can be **masked** (disabled) or **enabled**
- Interrupts are queued and handled based on device priority
- A synchronized log records the order of interrupt service routines (ISRs)

---

## ⚙️ Features

✅ **Priority-based scheduling** — Higher-priority devices are serviced first.  
✅ **Interrupt masking** — Disable a device to ignore its interrupt requests.  
✅ **Multithreading** — Simulates concurrent devices raising interrupts.  
✅ **Logging** — Shows when each device’s ISR (Interrupt Service Routine) completes.  

---
