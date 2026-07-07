# Master Reference Tables

> **Purpose:**  
> This document serves as the master engineering reference for every laser material, pump source, dopant, architecture, nonlinear crystal, and performance parameter introduced throughout the **Laser Materials & Solid-State Lasers Masterclass**.
>
> Unlike the lesson notes, this document is continuously updated as new topics are introduced. It is intended to become a quick-reference handbook for engineers and students.

---

# Table of Contents

- [How to Use This Document](#how-to-use-this-document)
- [Reference Data Notes](#reference-data-notes)
- [Laser Gain Media](#laser-gain-media)
- [Laser Dopants](#laser-dopants)
- [Pump Sources](#pump-sources)
- [Laser Architectures](#laser-architectures)
- [Nonlinear Optical Crystals](#nonlinear-optical-crystals)
- [Common Laser Wavelengths](#common-laser-wavelengths)
- [Material Properties](#material-properties)
- [Revision History](#revision-history)

---

# How to Use This Document

This document is updated throughout the course.

Whenever a new material, pump source, or laser architecture is introduced:

- A new row is added.
- Existing rows may be expanded.
- Values are refined when better engineering references become available.

Every numerical value is classified as one of:

| Classification | Meaning |
|---------------|---------|
| **Constant** | Fundamental physical constant |
| **Typical** | Common manufacturer datasheet value |
| **Range** | Representative engineering range |
| **Estimate** | Order-of-magnitude estimate |

---

# Reference Data Notes

Laser material properties vary depending on:

- Dopant concentration
- Crystal orientation
- Growth method
- Temperature
- Manufacturer
- Surface finish
- Coatings

Unless otherwise stated:

- Room temperature (≈20–25°C)
- Typical industrial-grade material
- CW operation
- Representative values

---

# Laser Gain Media

> **Status:** Living table (initial template)

| Host | Dopant(s) | Crystal Structure | Pump λ | Laser λ | Lifetime | Thermal Conductivity | M² Capability | Cooling | Cost | Typical Applications | Status |
|------|-----------|------------------|--------|----------|----------|----------------------|---------------|---------|------|---------------------|--------|
| *(To be populated during Module 3)* | | | | | | | | | | | |

---

# Laser Dopants

| Dopant | Symbol | Typical Oxidation State | Common Hosts | Primary Emission | Primary Pump | Notes | Status |
|---------|---------|------------------------|--------------|------------------|--------------|-------|--------|
| *(To be populated during Module 5)* | | | | | | | |

---

# Pump Sources

| Pump Type | Efficiency | Lifetime | Cooling | Cost | Maintenance | Typical Applications | Status |
|-----------|-----------|----------|---------|------|-------------|----------------------|--------|
| Flashlamp | | | | | | | Planned |
| Arc Lamp | | | | | | | Planned |
| Laser Diode | | | | | | | Planned |
| Fiber-Coupled Diode | | | | | | | Planned |
| VCSEL | | | | | | | Planned |
| Electrical | | | | | | | Planned |
| Chemical | | | | | | | Planned |

---

# Laser Architectures

| Architecture | Beam Quality | Efficiency | Scalability | Cooling | Complexity | Typical Uses | Status |
|-------------|-------------|-----------|-------------|----------|------------|--------------|--------|
| Rod | | | | | | | Planned |
| Slab | | | | | | | Planned |
| Thin Disk | | | | | | | Planned |
| Fiber | | | | | | | Planned |
| Ring | | | | | | | Planned |
| Waveguide | | | | | | | Planned |
| Microchip | | | | | | | Planned |
| DPSS | | | | | | | Planned |
| MOPA | | | | | | | Planned |

---

# Nonlinear Optical Crystals

| Crystal | Transparency Range | Nonlinear Coefficient | Damage Threshold | Phase Matching | Typical Uses | Status |
|----------|-------------------|-----------------------|------------------|----------------|--------------|--------|
| KTP | | | | | | Planned |
| LBO | | | | | | Planned |
| BBO | | | | | | Planned |
| KDP | | | | | | Planned |
| CLBO | | | | | | Planned |
| PPLN | | | | | | Planned |

---

# Common Laser Wavelengths

| Wavelength | Laser Material | Spectral Region | Common Applications | Status |
|------------|----------------|-----------------|---------------------|--------|
| 355 nm | | UV | | Planned |
| 532 nm | | Green | | Planned |
| 632.8 nm | | Red | | Planned |
| 694.3 nm | | Red | | Planned |
| 808 nm | | Near IR | | Planned |
| 940 nm | | Near IR | | Planned |
| 980 nm | | Near IR | | Planned |
| 1030 nm | | Near IR | | Planned |
| 1064 nm | | Near IR | | Planned |
| 1550 nm | | Near IR | | Planned |
| 1940 nm | | Mid IR | | Planned |
| 2090 nm | | Mid IR | | Planned |
| 2940 nm | | Mid IR | | Planned |
| 10.6 µm | | Far IR | | Planned |

---

# Material Properties

The following engineering properties will be tracked for every laser material.

| Property | Units | Importance |
|----------|-------|------------|
| Density | g/cm³ | Mechanical design |
| Crystal Structure | — | Manufacturing |
| Hardness | Mohs / Vickers | Machining |
| Fracture Toughness | MPa√m | Reliability |
| Young's Modulus | GPa | Mechanical design |
| Thermal Conductivity | W/m·K | Cooling |
| Specific Heat | J/kg·K | Thermal analysis |
| Thermal Expansion | ppm/K | Thermal stress |
| Refractive Index | — | Optical design |
| dn/dT | 1/K | Thermal lensing |
| Fluorescence Lifetime | µs / ms | Laser efficiency |
| Absorption Cross Section | cm² | Pump design |
| Emission Cross Section | cm² | Gain calculations |
| Saturation Fluence | J/cm² | Pulsed systems |
| Damage Threshold | J/cm² or MW/cm² | Reliability |
| Beam Quality (Typical M²) | — | Optical performance |
| Typical Optical Efficiency | % | System efficiency |
| Wall-Plug Efficiency | % | Electrical efficiency |
| Typical Output Power | W / kW | System capability |

---

# Planned Comparison Tables

As the course progresses, this document will gain dedicated comparison tables for:

- Single-Doped Gain Media
- Co-Doped Gain Media
- Fiber Gain Media
- Laser Ceramics
- Pump Sources
- Pump Geometries
- Resonator Types
- Cooling Methods
- Beam Delivery Systems
- Thermal Lensing
- Optical Coatings
- Crystal Growth Methods
- Laser Safety Classes
- Manufacturing Defects
- Failure Mechanisms
- Industrial Applications
- Medical Applications
- Semiconductor Applications
- Aerospace Applications
- Defense Applications
- Emerging Technologies

---

# Engineering Notes

> **Design Rule**
>
> Never compare laser materials using only one property.
>
> Every engineering decision is a tradeoff involving:
>
> - Performance
> - Efficiency
> - Cost
> - Manufacturability
> - Reliability
> - Cooling
> - Availability
> - Safety
> - Serviceability

Throughout this course, every comparison will consider the complete engineering picture rather than optimizing a single parameter.

---

# Revision History

| Version | Date | Changes |
|----------|------|---------|
| 1.0 | 2026-07-07 | Initial master reference table structure created. |

---

> **Living Document:** This file is expected to become one of the largest documents in the repository. By the end of the course, it will contain comprehensive comparison tables covering virtually every commercially significant laser gain medium, dopant, pump source, architecture, and nonlinear optical material used in modern laser engineering.