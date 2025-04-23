# Leader-Follower-Formation-Control
 This repository implements a Lyapunov-based leader–follower strategy for nonholonomic, differential-drive wheeled robots. A single “leader” vehicle generates a desired trajectory, while multiple “followers” autonomously track its motion, maintaining prescribed inter-vehicle distances—and, in the full control law, orientations as well. Three Python simulation scripts demonstrate the method under progressively challenging scenarios:  Line Formation (velocity control only)  Rectangular Formation (velocity control only)  Complex Trajectory (distance + orientation control)  Each script models the robots’ nonholonomic kinematics, applies a rigorously derived Lyapunov control law, and visualizes the resulting formations. Whether you’re exploring multi-agent coordination or developing advanced formation controllers, this codebase offers a clear, extensible foundation.
# Leader–Follower Formation Control of Differential-Drive Mobile Robots

[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](#license)

> **Multi-Agent Control** using a Lyapunov-based **Leader–Follower** approach for nonholonomic wheeled mobile robots, implemented and validated in three scenarios:  
> 1. Line Formation  
> 2. Rectangular Formation  
> 3. Complex Trajectory with Distance & Orientation Control

## 📖 Table of Contents

- [Overview](#overview)  
- [Features](#features)  
  - [Line Formation](#line-formation)  
  - [Rectangular Formation](#rectangular-formation)  
  - [Complex Trajectory](#complex-trajectory)  
- [Results](#results)  


## 🔍 Overview

This project implements a **leader–follower** formation control strategy for differential-drive robots based on Lyapunov stability theory.  
- **Leader** generates the desired trajectory.  
- **Followers** track the leader while maintaining specified distances (and orientations, in the full control law).  

Three simulation scripts demonstrate the approach under increasing complexity.

## ⚙️ Features

- **Nonholonomic Kinematics** model of a differential-drive robot  
- **Lyapunov-based** control laws for:  
  - Pure position tracking (distance only)  
  - Full pose tracking (distance + orientation)  
- **Three scenarios**:  
  1. Line formation (velocity control only)  
  2. Rectangular formation (velocity control only)  
  3. Complex trajectory (complete control law)
## results
https://github.com/Parag-IIT/Leader-Follower-Formation-Control-main/blob/main/Screenshot%202025-04-23%20095122.png

