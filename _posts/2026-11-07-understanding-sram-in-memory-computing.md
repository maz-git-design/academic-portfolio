---
title: "Understanding SRAM-Based In-Memory Computing for Edge AI"
date: 2026-11-07
permalink: /posts/2026/11/understanding-sram-in-memory-computing/
tags:
  - In-Memory Computing
  - SRAM
  - Edge AI
  - VLSI
  - AI Hardware
---

This is a blog on SRAM-based In-memory Computing for Edge AI

Introduction
======

The growing demand for Artificial Intelligence (AI) on resource-constrained devices has increased the need for energy-efficient computing architectures.

Traditional computing systems rely on frequent data transfers between processors and memory. These transfers can significantly increase energy consumption and limit performance.

In-Memory Computing (IMC) offers an alternative by performing selected computational operations directly within or near memory structures.

What is In-Memory Computing?
======

In-Memory Computing is a computing paradigm that reduces data movement by integrating computational capabilities into memory architectures.

Instead of repeatedly transferring data between memory and processing units, IMC enables certain operations to be executed within the memory array or its peripheral circuits.

This approach is particularly attractive for Edge AI applications, where energy efficiency, latency, and hardware resources are critical constraints.

Why SRAM?
======

Static Random-Access Memory (SRAM) is widely used in modern integrated circuits because of its fast access time and compatibility with standard CMOS technologies.

SRAM-based IMC architectures can exploit existing memory structures to support additional computational operations.

However, incorporating computation into SRAM introduces challenges involving circuit complexity, area, energy consumption, and reliability.

SRAM Architectures for In-Memory Computing
======

Conventional SRAM typically uses a 6-transistor (6T) bitcell.

Alternative architectures, including 7T and 8T SRAM, introduce additional transistors to support different access mechanisms or computational capabilities.

The choice of bitcell architecture depends on the required operations and the trade-offs between area, performance, power consumption, and stability.

Applications in Edge AI
======

SRAM-based IMC has potential applications in:

* Neural network acceleration
* Logic-based machine learning
* Low-power inference
* On-chip learning
* Energy-efficient embedded AI systems

My Research
======

My MSc research at Newcastle University focused on the design and simulation of a 7T/8T SRAM-based in-memory computing macro supporting inference and online Tsetlin Machine learning.

The project investigated circuit-level approaches for integrating Tsetlin Automata state updates into SRAM structures using a 65 nm CMOS technology.

Conclusion
======

SRAM-based In-Memory Computing represents a promising direction for energy-efficient AI hardware.

By reducing data movement and enabling computation closer to stored information, these architectures can help address some of the challenges associated with deploying AI on resource-constrained devices.