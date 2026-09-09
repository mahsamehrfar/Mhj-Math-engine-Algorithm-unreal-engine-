
# 🧮 MHJ Algorithm Math Engine for Unreal Engine

![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-5.0+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Real-Time](https://img.shields.io/badge/Performance-Real--Time-orange.svg)

**MHJ Algorithm Math Engine** is a powerful, high-performance mathematical parser and graphing plugin built natively for Unreal Engine. It allows developers to evaluate complex string-based math expressions at runtime, calculate calculus operations, and instantly generate beautiful 2D and 3D graphs using Procedural Meshes.

Whether you are building a sci-fi UI, an educational tool, or a complex physics simulator, this plugin gives you full mathematical freedom entirely inside Blueprints.

## ✨ Key Features

* ⚡ **Full Real-Time Calculation:** Parse and evaluate complex string expressions (e.g., `sin(x ^ 2 + y)`) instantly at runtime with zero lag.
* 🌐 **3D Surface Graphing:** Generate dynamic 3D Procedural Meshes from math equations. (Perfect for terrain generation, data visualization, and dynamic VFX).
* 📈 **2D Line Graphing:** Draw real-time 2D Cartesian graphs and UI data plots based on player inputs or in-game variables.
* 🔍 **Root Finding Algorithm:** Built-in dynamic solvers to accurately find the roots (x-intercepts) of complex mathematical equations at runtime.
* 📉 **Derivative Engine:** Calculate instantaneous rates of change and slopes for any given string function.
* 📊 **Integral Engine:** Perform real-time area-under-the-curve calculus evaluations using advanced quadrature parameters (Simpson's rule, Tanh-Sinh, etc.).
* 🔵 **100% Blueprint Compatible:** No C++ knowledge required. Every feature is exposed to Unreal's Blueprint visual scripting system.

## 📸 Showcase

<img width="1729" height="750" alt="Screenshot 2026-09-10 021011" src="https://github.com/user-attachments/assets/6ce1cec6-2fd8-46eb-8edc-85c3f62d87e0" />
<img width="1777" height="775" alt="Screenshot 2026-09-10 014233" src="https://github.com/user-attachments/assets/af5fafae-e1fb-4336-9fb0-1f3e5f051a3a" />

## 🚀 Installation

1. Download the latest release from the [Releases](#) tab, or clone this repository.
2. Inside your Unreal Engine project directory, create a folder named `Plugins` (if it doesn't already exist).
3. Extract the `MHJ_AlgorithmMathEngine` folder into the `Plugins` directory.
4. Right-click your `.uproject` file and select **Generate Visual Studio project files**.
5. Open your project. When prompted, click **Yes** to rebuild the missing plugin modules.
6. Enable the plugin via **Edit > Plugins > Math > MHJ Algorithm Math Engine**.

## 🛠️ Quick Start & Usage

### 1. Real-Time Math Evaluation
Evaluate a math string on the fly by passing in a dictionary/map of variables.
```text
[ "sin(x * x + y)" ] ---> [ MHJ Math Engine ] ---> [ Result: 0.841 ]
```

### 2. Procedural 3D Graphing
Feed an X and Y nested `For-Loop` into the Math Engine, output the `Z` height, and pass the arrays into a `Procedural Mesh Component` to generate real-time 3D solid graphs. (Supports Normals, UVs, and custom bounds).

### 3. Calculus Engines
Pass your mathematical string into the **Integral** or **Derivative** nodes, define your Min/Max bounds, choose your accuracy step counts, and retrieve precision outputs directly in Blueprints.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! 
Feel free to check out the [issues page](#) to report bugs or suggest new algorithms.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
**Created by MHJ Studios** | Powering Math in Unreal Engine
```
