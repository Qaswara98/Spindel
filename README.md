<p align="center">
  <img src="spindel_logo.svg" width="380" alt="Spindel logo"/>
</p>

<h1 align="center">Spindel</h1>
<p align="center">
  <em>Graph Genome Evaluation: Comparing Linear and Pangenome References for Structural Variant Detection</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Structural_Variant-Detection-a78bfa"/>
  <img src="https://img.shields.io/badge/PacBio%20HiFi-Long--read-34d399"/>
  <img src="https://img.shields.io/badge/Illumina-Short--read-60a5fa"/>
  <img src="https://img.shields.io/badge/GRCh38_%7C_T2T_%7C_HPRC-3_references-a78bfa"/>
  <img src="https://img.shields.io/badge/SVDB-benchmarking-fb923c"/>
</p>

---

## Overview

Does your reference genome affect structural variant detection?

This project benchmarks SV detection across three reference strategies:

| Strategy | Reference | Type |
|---|---|---|
| Linear | GRCh38 | Standard linear |
| Complete | T2T-CHM13 v2.0 | Telomere-to-telomere |
| Pangenome graph | HPRC v1.1 (Minigraph-Cactus) | Graph-based |

Evaluated on both **short-read** (Illumina WGS) and **long-read** (PacBio HiFi) data from clinical cohort.

---

## Progress

> **Status: actively in development** — results and scripts are updated as analysis completes.



*Supervisor:* **Jesper Eisfeldt**

*Subject reader:* **Adam Ameur**
