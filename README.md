# RAOA–DTCTP Data: Large-Scale Construction Time–Cost Trade-off (81, 146, 208, 291 activities)

This repository hosts the **dataset and documentation** supporting the study:

# Data Guide (DTCTP)

This dataset supports large-scale **Discrete Time–Cost Trade-off Problems (DTCTP)** used in the RAOA study.  
Each activity has discrete **modes** with `(duration_days, direct_cost)`. **Project Cost (PC)** is computed as
`PC = Σ direct_cost + PD × DIC`, where **PD** is project duration and **DIC** is daily indirect cost.  
**Objectives**: minimize PD and PC simultaneously.

> **Project Scheduling to Minimize the Time and Cost in Large-Scale Construction Projects with Repulsion-Based Improved Arithmetic Optimization**  
> Vedat Toğan; Abdikarim Said Sulub; Mohammad Azim Eirgash; Fatemeh Mostofi

**Context.** The dataset is designed for **discrete time–cost trade-off problems (DTCTP)** in construction scheduling, where each activity has multiple execution modes with different durations and direct costs. Objectives are to minimize **Project Duration (PD)** and **Project Cost (PC)**, with **PC = Σ(Direct Costs) + PD × DIC (daily indirect cost)**. These are the formal objectives used in the manuscript.  

**Why this dataset?** It accompanies the RAOA study (Repulsion-based Arithmetic Optimization Algorithm), which aims to avoid local optima and improve Pareto-front quality in large DTCTP instances (81/146/208/291-activity benchmarks). The paper evaluates solution quality/effort using metrics such as **Average Percent Deviation (APD)** and **Number of Function Evaluations (NFE)**. See `/docs/paper/`.  

**What’s included**
- Four benchmark folders under `data/raw/`: `081`, `146`, `208`, `291`
- Minimal **data dictionary** (`data/README.md` and `data/Case study dat.zip`)
- Citation file (`CITATION.cff`) and data license (CC BY 4.0)

## How to cite

If you use this dataset, please cite the paper and dataset:

- **Article**: Toğan V., Sulub A. S., Eirgash M. A., Mostofi F., *Project Scheduling to Minimize the Time and Cost in Large-Scale Construction Projects with Repulsion-Based Improved Arithmetic Optimization*,  journal: Construction Engineering & Management.
- **Dataset**: “RAOA–DTCTP Data (v1.0.0)”, this repository URL or DOI (if you mint one via Zenodo).

## License

Data are released under **Creative Commons Attribution 4.0 International (CC BY 4.0)**. See `LICENSE`.

## Contact

- Maintainer: [Sulub A. S., cksulub10@gmail.com ]
- Issues & corrections: open a GitHub Issue using the **Data Correction** template.
