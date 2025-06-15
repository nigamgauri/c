# CPU-Scheduling-Simulator

## Table of Contents
- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Features](#features)
- [Files and Directories](#files-and-directories)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Example](#example)
- [Contributing](#contributing)

## Overview

This repository contains a Java-based simulator for CPU scheduling algorithms. CPU scheduling is a fundamental aspect of operating systems, where the CPU decides the order in which processes are executed. This simulator allows users to visualize and analyze different scheduling algorithms such as First-Come, First-Served (FCFS), Shortest Job Next (SJN), Round Robin (RR), and more.

This project was developed and maintained by **Gauri Nigam** to aid in the understanding and demonstration of core scheduling concepts in Operating Systems.

## Problem Statement

Different CPU scheduling algorithms have unique properties, and choosing the right one for a particular situation depends on various performance criteria. In some cases, maximizing response time may be prioritized over throughput, while in others, minimizing average waiting time might be more important. Sometimes, a balance between multiple criteria is required.

The challenge lies in determining which scheduling algorithm is best suited for a given situation. This simulator provides an environment to experimentally test and compare various algorithms through user inputs and live visualizations.

## Features

- **Multiple Scheduling Algorithms**: Simulates FCFS, SJN, Round Robin, and other algorithms.
- **Graphical Interface**: Interactive GUI for easy operation and visualization.
- **Real-Time Visualization**: Shows queue states, wait times, and burst time progress.
- **Performance Metrics**: Displays waiting time, turnaround time, and CPU utilization.
- **Modular Code**: Built using custom data structures to manage processes effectively.

## Files and Directories

- `sources/`: Additional source files (e.g., images).
- `src/main/`: Java source code directory.
- `target/`: Compiled output and build artifacts.
- `pom.xml`: Maven configuration file.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- Apache Maven (optional, for build management).
- A Java IDE (e.g., IntelliJ IDEA, Eclipse).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nigamgauri/cpu-scheduling-simulator.git
