# Cadence Battery Controller (CBC)

The **Cadence Battery Controller (CBC)** is an implementation of the [Cadence Control Law (CCL)](https://github.com/andrewmureddu/cadence-control-law).  
It demonstrates how heterogeneous energy storage modules (e.g., LFP, NMC, LTO, ultracapacitors, flywheels) can be orchestrated in cadence to extend life, reduce cost-of-ownership, and improve resilience under real-world duty.

---

## Core Idea
By rotating modules through three roles — **bulk**, **alignment**, and **sprinters** — in a repeating cadence (e.g., 2–2–3), the controller:

- Suppresses ΔSoC exposure by an order of magnitude.  
- Synchronizes aging across chemistries.  
- Extends usable pack life from 2–3 years to >10 years in fleet duty.  
- Improves hot and cold performance by letting sprinters absorb bursts and regen.  
- Flattens cost-of-ownership across the system lifetime.  

---

## Contents
- `/simulations/` — notebooks and CSVs showing model results.  
- `/docs/` — design notes, diagrams, and controller logic.  
- `/figures/` — schematic diagrams and results plots.  
- [References](references.md) — Zenodo DOIs and related sources.

---

## Why This Matters
Electric vehicles and stationary storage today rely on single-pack chemistries that degrade quickly under stress.  
The CBC shows how cadence orchestration can turn fragile packs into **long-lived ensembles**, lowering replacement costs and making sustainable transport more practical worldwide.

---

## License
This repository is released under the **Creative Commons Zero v1.0 Universal (CC0)** license.  
It is open prior art: free for anyone to study, use, or adapt without restriction.

---

## Citation
When referencing this work, please cite as:

> Mureddu, A. (2025). *Cadence Battery Controller (Embodiment of the Cadence Control Law).* GitHub repository.  
> DOI: [Zenodo DOI will appear here after release]
