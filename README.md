### 🚗 Project Roots: SqPlus & *Amazing Curves Racing*

> **📦 Public Archive from SourceForge:** *Includes various open-source developer contributions.*

I originally created **SqPlus** to seamlessly integrate Squirrel script into my real-time racing simulator, [Amazing Curves Racing](https://steampowered.com). 

#### 🐿️ Why Squirrel?
* **Syntax:** Features a familiar C/C++ style syntax.
* **Memory:** Unlike Lua, it operates with **no Garbage Collection (GC)** pauses.

---

#### 🛠️ Evolution of the Tech Stack: 2005 vs. Modern C++

* **Back in 2005:** 
  SqPlus required complex template metaprogramming to function properly. However, once established, binding variables, functions, and classes became remarkably simple and easy to use.
  
* **The Modern Advantage (C++17 / C++20 / C++23):** 
  While this implementation historically required intense metaprogramming, this kind of binding has become significantly easier using modern language features. Features like **compile-time reflection helpers**, **`std::apply`**, **variadic templates (C++17)**, and **Concepts (C++20)** drastically reduce boilerplate code when mapping native structures to script environments.

* **Looking Back from 2026:** 
  For any dynamically updated code today, I would bypass scripting languages entirely and use **COM-style virtual interfaces with native C++**. 

#### 💡 The Benefits of a Native Approach:
1. **Performance:** Eliminates the overhead entirely.
2. **Debugging Efficiency:** You only need a single debugger, drastically accelerating the overall development loop.

