# C++ Network Packet Analyzer

A C++ Deep Packet Inspection (DPI) project for exploring network protocol parsing, connection tracking, and concurrent packet processing.

## Problem Statement

Raw network traffic is difficult to inspect manually. This project explores how packets can be parsed, grouped into stateful flows, and inspected to help understand network behavior and application protocols.

## Features

- **Network Protocol Parsing:** Examine packet structures and protocol information.
- **Deep Packet Inspection:** Inspect supported packet and connection metadata.
- **Flow Tracking:** Maintain state for network connections.
- **Multithreaded Processing:** Explore thread pools and parallel packet processing.
- **Producer–Consumer Pattern:** Use thread-safe queues to coordinate processing.
- **TLS Metadata Inspection:** Explore destination-domain metadata exposed by supported TLS handshakes.

## Technologies and Concepts

- C++
- Computer Networks and TCP/IP
- Packet Parsing and Protocol Analysis
- Deep Packet Inspection (DPI)
- Connection and Flow Tracking
- Multithreading and Thread-Safe Queues
- Producer–Consumer Architecture

## Repository Structure

The repository contains a simpler implementation and a multithreaded implementation. Review the source files to identify the available entry points and build requirements before running either version.

## Getting Started

1. Clone this repository.
2. Review the source files and any existing build instructions.
3. Compile using a C++ compiler compatible with the code and its dependencies.
4. Run only against traffic or packet captures you are authorized to inspect.

Exact build commands will be documented after the compiler requirements and dependencies are verified.

## Learning Objectives

This project provides a practical way to study packet structure, protocol metadata, stateful flow processing, concurrency, and producer–consumer design in C++.

## Attribution

This repository is based on work from the original project:
https://github.com/perryvegehan/Packet_analyzer

Original code and contributions remain subject to the original project's applicable license and attribution requirements. Additional modifications should be documented separately.

## Disclaimer

Use this project only on networks and traffic you own or have explicit permission to analyze. Encrypted traffic inspection is limited to metadata that is actually available; this project does not imply that HTTPS payloads can generally be decrypted.
