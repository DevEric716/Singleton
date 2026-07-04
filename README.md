# Roblox-Engine-Utils

A collection of high-performance, modular utilities designed for Roblox game development, with a specific focus on system architecture, memory efficiency, and CPU optimization.

## Modules Included

### 1. RateLimiter
A lightweight, high-performance utility designed to throttle function execution based on execution time.
*   **Purpose:** Prevents CPU bottlenecks by limiting function call frequency.
*   **Use-case:** Perfect for input handling, network requests, or limiting expensive logic inside `RenderStepped` loops.

### 2. MemoryManager
A singleton-pattern service for resource tracking and lifecycle management.
*   **Purpose:** Provides a centralized registry for managing game assets and data states.
*   **Use-case:** Ensures efficient cleanup of resources and prevents memory leaks, crucial for maintaining long-running server sessions.

## Technical Philosophy
This repository focuses on **Luau strict typing** and **low-level optimization principles**. The goal is to provide scalable, reusable code components that maintain high performance even under heavy concurrent loads. 

By utilizing strict typing and modular architecture, these utilities help reduce technical debt and improve the overall stability of the engine environment.

## License
MIT
