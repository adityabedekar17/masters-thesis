# BTI Modeling and Reliability Analysis in Advanced Nodes

This repository presents the implementation and results of my Master's thesis:
**"Survey on Bias Temperature Instability: Characterization, Modeling, and Security Implications in Advanced Process Nodes"**  
University of California, Santa Cruz — June 2025  
**Author:** Aditya Ashish Bedekar

## Overview

Bias Temperature Instability (BTI), particularly Negative BTI (NBTI), is a critical reliability concern in modern CMOS circuits. This thesis models and characterizes BTI-induced threshold voltage shifts and delay degradation in planar and FinFET architectures using both SPICE-based and TCAD-based workflows.

The project combines:
- **SPICE (HSPICE with MOSRA)** for aging simulation of Sky130 standard cells.
- **TCAD (Synopsys Sentaurus)** for physical degradation modeling in predictive 7nm FinFET devices.

The final goal includes security implications of BTI in FPGA fabrics.
## Key Contributions

- SPICE modeling of BTI effects in Sky130 PMOS/NMOS transistors using Synopsys HSPICE and MOSRA.
- Sentaurus TCAD modeling of BTI stress and recovery for 7nm predictive FinFETs.
- ΔVth extraction, temperature-voltage sweep analysis, and recovery time characterization.
- Exploration of BTI-based hardware security vulnerabilities in FPGA systems.

## Tools Used

- Synopsys Sentaurus (SProcess, SDevice, SVisual)
-  Synopsys HSPICE with MOSRA aging models
- Python (for plotting and parsing)
- Synopsys  WaveView (for waveform analysis)
- Skywater Sky130 PDK
- Synopsys Predictive 7nm FinFET PDK

## Figures & Results

Figures highlight ΔVth trends across 30 devices, temperature dependency in Sky130, and stress/recovery analysis in FinFETs. Security relevance is tied to remanence effects in FPGA as per the Pentimento phenomenon.

## Citation

If you use this work, please cite the thesis:

```bibtex
@mastersthesis{Bedekar2025,
  title={Survey on Bias Temperature Instability: Characterization, Modeling, and Security Implications in Advanced Process Nodes},
  author={Bedekar, Aditya Ashish},
  school={University of California, Santa Cruz},
  year={2025}
}



