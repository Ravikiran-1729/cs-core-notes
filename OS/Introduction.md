# Operating System (OS) Notes  
**Date:** 01 May 2026  

---

## 📌 What is an Operating System?

An **Operating System (OS)** is system software that acts as a bridge between the user and computer hardware, and manages system resources efficiently.

### 🔑 Key Roles of OS

1. **Intermediary**
   - Acts as a mediator between **user and hardware**
   - Translates user commands into machine-level instructions

2. **Resource Manager / Allocator**
   - Allocates resources like CPU, memory, and I/O devices
   - Ensures fair and efficient usage among programs

3. **Platform Provider**
   - Provides an environment for application execution
   - Supports installation and running of software

---

## 🎯 Goals of an Operating System

### 1. Primary Goal
- **Convenience (User-Friendly System)**
  - Easy interaction between user and system

### 2. Secondary Goals
- **Efficiency** → Optimal use of hardware resources  
- **Reliability** → System should work without failure  
- **Maintainability** → Easy to update and manage  

---

## ⚙️ Core Functions of OS

### 1. Process Management
- Handles creation, execution, scheduling, and termination of processes
- Ensures smooth multitasking

### 2. Memory Management
- Allocates and deallocates memory
- Manages **RAM and virtual memory**

### 3. I/O Device Management
- Controls devices like keyboard, mouse, printer, disk
- Uses **buffering & caching** to improve speed

### 4. File Management
- Organizes files and directories
- Manages permissions, naming, and storage structure

### 5. Network Management
- Handles network communication
- Enables data transfer and connectivity

### 6. Security & Protection
- Prevents unauthorized access
- Uses:
  - Authentication
  - Authorization
  - Encryption

---

## 🖥️ Batch Operating System

### 🔹 Concept
- Early computers were **non-interactive**
- Users prepared jobs consisting of:
  - Program
  - Control Information
  - Input Data

### 🔹 Working
- One job processed at a time
- Input devices like **punch cards/tapes** were slow → CPU idle

### 🔹 Solution: Batch Processing
- Similar jobs grouped into batches
- Executed sequentially to improve efficiency

### 🔹 Key Points
- Grouping done by:
  - Operator OR
  - Batch Monitor (in memory)
- Jobs stored as decks of punched cards

---

## 🔄 Spooling (Simultaneous Peripheral Operations Online)

### 🔹 Concept
- Technique to handle slow I/O devices efficiently

### 🔹 Working
- Data is temporarily stored in memory or disk
- Device processes data at its own speed

### 🔹 Example
- Printing:
  - Data stored first → printer prints later

### 🔹 Benefit
- CPU does not wait for slow devices → improves performance

---

## 🔁 Multiprogramming

### 🔹 Concept
- Multiple jobs kept in memory simultaneously

### 🔹 Working Steps
1. OS loads multiple jobs into memory  
2. CPU executes one job  
3. If job waits (e.g., I/O), OS switches to another job  
4. CPU remains busy continuously  

---

### 🔹 Comparison

| Feature | Non-Multiprogramming | Multiprogramming |
|--------|---------------------|------------------|
| CPU Usage | Idle during I/O | Always active |
| Efficiency | Low | High |
| Task Handling | Single task | Multiple tasks |

---

## ✅ Advantages of Multiprogramming

1. High CPU utilization  
2. Reduced waiting time  
3. Supports multitasking  
4. Efficient resource sharing  

---

## ❌ Disadvantages

1. Complex scheduling algorithms  
2. Difficult memory management  
3. Increased system complexity  

---



## ⏱️ Multitasking / Time Sharing OS

> 💡 Extension of multiprogramming

### 🔹 Key Points

* Allows multiple users simultaneously
* CPU switches rapidly between tasks
* Gives illusion of dedicated system

⚠️ **Note:**

* Requires multiprogramming
* Not true parallelism

---

## 🧠 Multiprocessing OS

> 💡 Uses **multiple CPUs** for execution

### 🔹 Features

* Multiple CPUs share:

  * Memory
  * Bus
  * Devices

* Achieves **true parallel execution**

### 📌 Applications

* AI systems
* Image processing
* Weather forecasting

---

## ⚖️ Types of Multiprocessing

| Feature       | Symmetric | Asymmetric |
| ------------- | --------- | ---------- |
| Task Handling | Any CPU   | Fixed role |
| Complexity    | Simple    | Complex    |
| Performance   | Balanced  | Varies     |

---

## 🔄 Multiprogramming vs Multiprocessing

| Feature    | Multiprogramming | Multiprocessing |
| ---------- | ---------------- | --------------- |
| CPU        | Single           | Multiple        |
| Execution  | Simulated        | Parallel        |
| Complexity | Low              | High            |

---

## ⏱️ Real-Time OS

> 💡 System with **strict time constraints**

### 🔹 Key Points

* Must respond within fixed time
* Failure if deadline missed

### 📌 Examples

* Air traffic control
* Reservation systems

---

## 🔴 Hard Real-Time OS

* Must meet deadlines strictly
* Failure if delayed

📌 Example: Airbag system

---

## 🟡 Soft Real-Time OS

* Deadlines may be missed
* Slight delay acceptable

📌 Example: Mobile apps, games

---

## ⚖️ Hard vs Soft Real-Time OS

| Feature     | Hard RTOS | Soft RTOS |
| ----------- | --------- | --------- |
| Deadline    | Strict    | Flexible  |
| Reliability | Very high | Moderate  |
| Cost        | High      | Low       |

---

## 🌐 Distributed OS

> 💡 Collection of independent systems working together

### 🔹 Features

* Multiple nodes connected via network
* Share resources & tasks
* Each node has part of OS

---

### 🎯 Why Distributed OS?

* Resource sharing
* Faster computation
* Reliability
* Communication

---

## 🧠 Final Revision

> ⚡ **One Shot Summary**

* OS → Intermediary + Resource Manager + Platform
* Batch → Group jobs
* Spooling → Avoid CPU waiting
* Multiprogramming → CPU always busy
* Multiprocessing → Multiple CPUs
* RTOS → Time-critical systems
* Distributed → Network-based OS

---
