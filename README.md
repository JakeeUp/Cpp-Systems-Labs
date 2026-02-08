# ⚙️ C++ Systems Architecture Labs

**High-Performance Game Engine Components & Educational Implementations**

This repository houses standalone implementations of core game engine systems. Developed during my tenure as a **Game Programming TA**, these labs serve as both advanced curriculum material and a testing ground for low-level optimization techniques.

The goal of this project is to demonstrate **"Engine-Native" programming**: moving beyond standard library containers to build memory-aware, cache-friendly, and thread-safe architectures used in AAA development.

### 🎯 Key Technical Focus
* [cite_start]**Memory Management:** Custom allocators (Pool/Stack) to minimize heap fragmentation and enforce cache locality[cite: 9, 12].
* [cite_start]**Concurrency:** Thread-safe containers and job systems to utilize multi-core architectures.
* [cite_start]**File I/O:** Asynchronous serialization systems for non-blocking asset loading[cite: 9, 13].
* **Design Patterns:** Decoupled architecture using Event Buses and Service Locators.
