# SEAC: Simultaneous Exploration and Coverage for Surface Inspection of Complex Structures Using a UAV

[![ROS Noetic](https://img.shields.io/badge/ROS-Noetic-blue)](http://wiki.ros.org/noetic)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-20.04-orange)](https://releases.ubuntu.com/20.04/)
[![Language](https://img.shields.io/badge/Language-C++-blue)](https://isocpp.org/)
[![Simulator](https://img.shields.io/badge/Simulator-AirSim-lightblue)](https://microsoft.github.io/AirSim/)
[![Engine](https://img.shields.io/badge/Engine-UE4.27-black)](https://www.unrealengine.com/)
[![Python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-Supported-EE4C2C?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![CUDA](https://img.shields.io/badge/CUDA-12.8-76B900?logo=nvidia&logoColor=white)](https://developer.nvidia.com/cuda-toolkit)

## Abstract

Surface visual inspection using Unmanned Aerial Vehicles (UAVs) is an efficient way for High‑Definition (HD) structural health monitoring. Classic Explore‑Then‑Exploit (ETE) workflows decouple tasks into sequential stages including online exploration and offline coverage, which are time‑consuming and susceptible to localization drift. This study proposes an online path planner for the **Simultaneous Exploration And Coverage (SEAC)** of complex structures using a UAV.

![Demo animation](preview.gif)

*Example of SEAC on complex structures.*

---

## Key Features

- ✅ **Simultaneous exploration & coverage** – no separate offline coverage stage.
- ✅ **Real‑time operation** – hierarchical planning ensures fast computation suitable for onboard deployment.
- ✅ **High coverage rate** – achieves >90% surface coverage under strict visual inspection constraints.
- ✅ **Robust to complex geometries** – validated on buildings and bridges.
- ✅ **Modular ROS implementation** – easy to adapt for different UAV platforms.

---

## Target-Aware Inspection

A 3D value map is developed based on instance segmentation and vision-language models, which can be added to the mapping module of SEAC to perform a zero-shot target-aware inspection.
Therefore, the UAV can focus on exploring and inspecting target structures in a complex environment without searching through the whole space.

An implementation of target-aware SEAC in AirSim is shown as follows:

![Demo animation in AirSim](target-aware.gif)

*Example of inspecting the house in complex environment with trees, shrub and vehicles.*

## Installation

> **Note:** The source code will be released soon.
