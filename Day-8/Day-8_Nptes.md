# Day 08: Memory Information in Linux

## Overview
Memory management is an important part of Linux system monitoring.
Memory information commands are used to check RAM usage and system
performance.

These commands help understand how system memory is being utilized.

---

## Commands

### free
**Purpose:**  
Used to display memory usage information.

**Syntax:**
- free
- free -m

**Usage:**
- Shows total, used, and free memory
- `-m` displays memory in MB

---

### vmstat
**Purpose:**  
Used to display virtual memory statistics.

**Syntax:**
- vmstat

**Usage:**
- Shows memory, swap, and CPU activity
- Useful for performance analysis

---

### top
**Purpose:**  
Used to monitor memory usage in real time.

**Syntax:**
- top

**Usage:**
- Displays memory consumption per process
- Helps identify memory-heavy processes

---

## Why These Commands Matter
- Monitor RAM usage
- Identify performance bottlenecks
- Prevent system slowdowns
- Useful in servers and cloud systems

---

## Summary
- free → check memory usage  
- vmstat → view virtual memory statistics  
- top → real-time memory monitoring  

Monitoring memory helps keep the system stable and efficient.