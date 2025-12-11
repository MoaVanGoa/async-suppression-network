# Asynchronous Suppression Network Simulator

**Author:** Moa van Goa  
**Date:** 2025-12-11

This repository contains a **Python-based, event-driven simulator** of a chip-level asynchronous suppression network.  
It models nodes with thresholds, decay, and links that fire asynchronously — no biology, no global clock.

---

## Features

- Event-driven node dynamics with thresholding and decay.
- Sparse random connectivity between source and target nodes.
- Asynchronous firing using `asyncio`.
- Optional visualization of target node activity using `matplotlib`.
- Fully camera-ready, self-contained, and reproducible.

---

## Requirements

- Python 3.8+  
- Optional: `matplotlib` for plotting node activity.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
