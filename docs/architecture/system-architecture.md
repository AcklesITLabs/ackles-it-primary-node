# System Architecture

## System Name

Ackles IT Labs – Primary Node

## Purpose

This system is designed as a workstation-class lab platform for cybersecurity study, virtualization, AI experimentation, and long-term infrastructure documentation.

## Architecture Principles

- Stability over unnecessary complexity
- Thermal control as hardware protection
- PCIe lane preservation
- Storage role separation
- Clean cable routing and airflow
- Future expansion without compromising current performance

## Core Design Notes

- GPU remains in primary PCIe x16 slot
- M.2_2 intentionally left empty to preserve GPU bandwidth
- RAM installed in A2/B2
- Bottom intake feeds GPU
- Side AIO intake feeds CPU
- Top and rear exhaust remove heat
