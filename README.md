# MagPl5

*Inspired by "magpie", short for **Modding Application Game Engine Injector 5***

MagPl5 is an engine-independent C++ wrapper designed to bring powerful Lua 5 scripting and runtime modding capabilities to custom game engines with minimal integration effort.

Whether you're developing a bespoke game engine or retrofitting modding support into an existing C++ project, MagPl5 acts as a dynamic middleware layer, allowing developers to expose, override, and extend engine functionality via Lua scripts — all at runtime.

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

