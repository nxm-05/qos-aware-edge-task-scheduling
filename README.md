# QoS-Aware Intelligent Task Scheduling Using Federated Learning for Edge Computing

## Overview

This project explores Quality of Service (QoS)-aware task scheduling in an edge computing environment. It simulates task allocation across edge nodes with different processing speeds while considering task priorities, execution times, and deadlines.

## Objectives

- Simulate task scheduling in an edge computing environment.
- Compare First-In, First-Out (FIFO) scheduling with a QoS-aware scheduling heuristic.
- Examine task completion times and deadline violations.
- Demonstrate the basic concept of federated averaging using illustrative client updates.

## Implementation

The project is implemented in Python using Google Colab. Task workloads are synthetically generated for simulation purposes. No external public benchmark dataset is used.

## Technologies Used

- Python
- Google Colab
- GitHub

## Repository Contents

- `qos-aware-edge-task-scheduling.ipynb` - Jupyter notebook containing the uploaded implementation.

## Dataset

This project uses synthetically generated workloads rather than an external dataset. Task execution requirements, priorities, and deadlines are generated programmatically using Python.

## Reproducibility

The simulation uses configured random seeds where specified. Results depend on the implemented algorithms, parameters, and workload settings.

The federated averaging component demonstrates the basic aggregation concept and is not intended to represent a complete, privacy-preserving federated learning system.

## Disclaimer

This is an academic simulation project. The results should be interpreted within the limits of the implemented experiments and should not be assumed to generalize to real-world edge computing environments.
