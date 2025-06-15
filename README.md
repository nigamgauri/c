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

This project is a Java-based simulator built by **Gauri Nigam** to demonstrate how different CPU scheduling algorithms work in an operating system. The simulator provides a visual and interactive way to understand scheduling strategies like First-Come, First-Served (FCFS), Shortest Job Next (SJN), Round Robin (RR), and others. It is designed to support learners, developers, and educators by simulating process execution and performance metrics.

## Problem Statement

In real-world systems, selecting the most suitable CPU scheduling algorithm depends on criteria like turnaround time, waiting time, response time, and throughput. The challenge lies in balancing these depending on the application's needs. This simulator aims to provide a flexible environment where users can input process details (like burst time, priority, arrival time) and observe how different algorithms handle scheduling, enabling better understanding through comparison. The inclusion of a graphical interface makes this tool intuitive and user-friendly.

## Features

- **Supports Multiple Algorithms**: FCFS, SJN, Round Robin, Priority Scheduling, and more.
- **Intuitive GUI**: Easy-to-use interface for process input and simulation visualization.
- **Comprehensive Metrics**: Shows performance indicators like waiting time and turnaround time.
- **Custom Data Structures**: Efficiently handles processes and ready queues for simulation.

## Files and Directories

- `sources/`: Contains supporting files and images.
- `src/main/`: Java source files implementing the simulator logic.
- `target/`: Build output including compiled classes and JAR files.
- `pom.xml`: Maven configuration file for dependencies and project build.

## Getting Started

### Prerequisites

- JDK 8 or higher
- (Optional) Apache Maven
- Java IDE like IntelliJ IDEA, Eclipse, or VS Code

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gauri-nigam/cpu-scheduling-simulator.git
