# Shoot Them Up
 
A third-person shooter built **entirely in C++** in Unreal Engine 5, with no Blueprint gameplay logic. Course project, **2024**.
 
## Why this one is worth reading
 
Unlike my other Unreal repositories, this project has a real `Source` folder: everything is C++, so the code is actually readable here rather than sealed inside `.uasset` files.
 
It was written to work through the engine's C++ side deliberately rather than reaching for Blueprints:
 
- **Actor lifecycle and memory management** — construction, `BeginPlay`, component ownership, and how UObjects are kept alive.
- **Line-trace combat** — hit detection, damage application and weapon handling in C++.
- **AI** — NavMesh navigation and enemy behaviour.
- **UI** — UMG widgets created and driven from C++.
## Built with
 
Unreal Engine 5 · C++ · Blueprints · UMG
