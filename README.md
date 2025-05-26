# MagPl5

*Inspired by "magpie", short for **Modding Application Game Engine Patch Injector 5***

Magpi5 (Modding Application Game Engine Patch Injector 5) is a Lua 5.x-based C++ runtime wrapper that injects modding capabilities into custom C++ game engines. It allows developers to expose engine functions and systems to Lua scripts using a flexible configuration system (whitelist or blacklist), enabling runtime monkey patching and modification with minimal integration overhead.

---

## Features

- **Runtime Monkey Patching**  
  Inject or override engine behavior dynamically via Lua scripts.

- **Minimal Engine Integration**  
  Use simple macros or config settings to expose or protect functions from being patched.

- **Whitelist / Blacklist Config**  
  Flexible function access control to define what scripts can and can't modify.

- **Lua 5.x Scripting Support**  
  Uses the Lua C API to execute user-defined scripts within the engine runtime.

- **Engine-Agnostic Architecture**  
  Works with any C++ engine that provides function access and basic integration hooks.

---

## 🚀 Getting Started (Coming Soon)

MagPl5 is under active development. Initial build instructions and integration examples will be provided in future commits.

Planned:
- CMake build system
- Header-only integration
- Example: basic example engine with Lua modding support

---

## 📦 Project Structure (Planned)

