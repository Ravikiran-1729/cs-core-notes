# Operating System (OS) Notes  
**Date:** 01 May 2026  

---

## 📌 What is an Operating System?

- An Operating System (OS) is **system software** that acts as a bridge between the **user and computer hardware**  
- It provides an **environment for execution of programs** and smooth interaction with the system  

- The OS works as an **intermediary**
  - Converts user instructions into machine-level operations  
  - Hides hardware complexity from the user  

- It acts as a **resource manager / allocator**
  - Manages CPU, memory, and I/O devices  
  - Allocates resources among multiple programs in a fair and efficient manner  

- It also acts as a **platform**
  - Provides a base for installing and running applications  
  - Ensures proper execution of software  

---

## 🎯 Goals of Operating System  

### 1. Primary Goal – Convenience  
- The system should be **user-friendly**  
- Users should be able to interact easily without understanding internal hardware details  

### 2. Secondary Goals  

- **Efficiency**
  - Proper and optimal utilization of hardware resources  
  - Avoid wastage of CPU time and memory  

- **Reliability**
  - System should operate correctly without frequent failures  
  - Should handle errors effectively  

- **Maintainability**
  - Easy to modify, update, and debug  
  - Supports long-term system improvements  

---

## ⚙️ Functions of Operating System  

### 1. Process Management  
- Handles **creation, execution, and termination** of processes  
- Manages **CPU scheduling** to decide which process runs  
- Ensures multiple processes can execute without conflict  

### 2. Memory Management  
- Allocates memory to different programs when required  
- Deallocates memory after execution  
- Manages both **physical memory (RAM)** and **virtual memory**  
- Ensures efficient utilization and avoids memory wastage  

### 3. I/O Device Management  
- Controls all input and output devices such as keyboard, disk, printer  
- Coordinates device operations through drivers  
- Uses techniques like:
  - **Buffering** → Temporary storage of data  
  - **Caching** → Faster data access  

### 4. File Management  
- Handles creation, deletion, and organization of files  
- Maintains file naming, permissions, and hierarchy  
- Ensures secure and efficient storage  

### 5. Network Management  
- Manages network communication between systems  
- Handles protocols and data transmission  
- Enables sharing of resources over a network  

### 6. Security and Protection  
- Protects system from unauthorized access  
- Uses:
  - Authentication (login verification)  
  - Authorization (access control)  
  - Encryption (data protection)  

---

## 🖥️ Batch Operating System  

- Early computers were **non-interactive systems**  
- Users prepared jobs consisting of:
  - Program  
  - Control Information  
  - Input Data  

- Only **one job was processed at a time**
  - CPU remained idle during I/O operations  
  - Input devices like punch cards were slow  

- To improve efficiency:
  - Similar jobs were grouped together into **batches**  
  - These batches were executed sequentially  

- Job grouping could be done by:
  - Operator manually  
  - Batch monitor (present in memory)  

- Jobs were typically stored as **punched card decks**  

---

## 🔄 Spooling (Simultaneous Peripheral Operations Online)  

- Spooling is a technique used to handle **slow I/O devices efficiently**  

- In this process:
  - Data is temporarily stored in **memory or disk**  
  - Device processes data later at its own speed  

- Example:
  - Printing → Data is stored first, then printed  

- Key benefit:
  - CPU does not wait for I/O operations  
  - Improves overall system performance  

---

## 🔁 Multiprogramming  

- Multiprogramming allows **multiple jobs to reside in memory simultaneously**  

- Working:
  - OS loads several jobs into memory  
  - CPU starts executing one job  
  - If the job waits (e.g., I/O), OS switches to another job  
  - CPU remains continuously active  

- Comparison:

  - Non-Multiprogramming:
    - CPU stays idle during waiting time  
    - Low efficiency  

  - Multiprogramming:
    - CPU switches between jobs  
    - High efficiency  

---

### ✅ Advantages of Multiprogramming  

- Increases CPU utilization  
- Reduces waiting time of processes  
- Supports multiple tasks at the same time  
- Improves overall system efficiency  

---

### ❌ Disadvantages of Multiprogramming  

- Requires complex scheduling techniques  
- Memory management becomes difficult  
- Increases system design complexity  

---

## 🧠 Quick Revision  

- OS = Intermediary + Resource Manager + Platform  
- Goals → Convenience + Efficiency + Reliability  
- Functions → Process, Memory, I/O, File, Network, Security  
- Batch OS → Groups similar jobs to improve performance  
- Spooling → Reduces delay caused by slow devices  
- Multiprogramming → Keeps CPU busy and efficient  

---
