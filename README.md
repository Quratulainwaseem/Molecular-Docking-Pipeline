# Omicron-Docking

In silico analysis and molecular docking of different ligands against the Spike glycoprotein of Omicron (B.1.1.529) — identifying CXCR3 Antagonistic 6C as the top drug candidate.

---

## Overview

The SARS-CoV-2 Omicron variant (B.1.1.529) introduced significant mutations in the spike (S) glycoprotein, which plays a critical role in viral attachment, fusion, and host cell entry. This project screened 4 drug candidates computationally against the Omicron spike glycoprotein to identify potential therapeutic ligands.

**Top finding:** CXCR3 Antagonistic 6C showed the highest binding affinity (-9.8 kcal/mol) against the Omicron spike glycoprotein, suggesting it as a strong potential therapeutic candidate.

---

## Pipeline

```
Omicron Spike Glycoprotein (B.1.1.529)
        ↓
3D Structure Retrieval (PDB)
        ↓
Active Site Identification
        ↓
Ligand Preparation (4 drug candidates)
        ↓
Molecular Docking (MOE)
        ↓
Binding Affinity Scoring (kcal/mol)
        ↓
Best Candidate Identified → CXCR3 Antagonistic 6C
```

---

## Drug Candidates Screened

| Drug | Category | Binding Affinity |
|------|----------|-----------------|
| Hydroxychloroquine | Anti-malarial | -5.8 kcal/mol |
| Darunavir | Anti-HIV | -6.0 kcal/mol |
| Carburazepam | Psychoactive | -8.2 kcal/mol |
| **CXCR3 Antagonistic 6C** | **Antagonist** | **-9.8 kcal/mol ✓ Best** |

> Higher negative binding affinity = stronger protein-ligand interaction = better drug candidate.

---

## Key Result

**CXCR3 Antagonistic 6C** demonstrated the strongest binding affinity (-9.8 kcal/mol) against the Omicron spike glycoprotein, outperforming existing antivirals including Darunavir and Hydroxychloroquine. This suggests CXCR3 Antagonistic 6C as a potential repurposed therapeutic candidate against Omicron.

---

## Repository Structure

```
Omicron-Docking/
├── figures/
│   ├── spike_glycoprotein_omicron.png
│   ├── hydroxychloroquine_docking.png
│   ├── darunavir_docking.png
│   ├── carburazepam_docking.png
│   └── CXCR3_antagonistic_docking.png
├── results/
│   └── binding_affinity_summary.csv
└── README.md
```

---

## Docking Results — Figures

### Spike Glycoprotein of Omicron (B.1.1.529)


### Anti-Malarial Drug — Hydroxychloroquine (-5.8 kcal/mol)


### Anti-HIV Drug — Darunavir (-6.0 kcal/mol)


### Psychoactive Drug — Carburazepam (-8.2 kcal/mol)


### Best Candidate — CXCR3 Antagonistic 6C (-9.8 kcal/mol)


---

## Tools Used

| Tool | Purpose |
|------|---------|
| `MOE` (Molecular Operating Environment) | Molecular docking |
| `PyMOL` | 3D structure visualization |
| `RCSB PDB` | Protein structure retrieval |
| `PubChem` | Ligand structure retrieval |

---

## Authors

**Qurat-ul-Ain Waseem, Ayesha Bibi, Faiza Nadeem**
BS Biotechnology — Group #04
Knowledge Unit of Science, Department of Biotechnology
University of Management and Technology (UMT), Sialkot

Supervised by: Sir Farhan Sarwar

---

- LinkedIn: [quratulain-waseem-239310353](https://www.linkedin.com/in/quratulain-waseem-239310353)
- ORCID: [0009-0003-9735-5632](https://orcid.org/0009-0003-9735-5632)

---

> This project was completed as part of BS-level research in Computational Biotechnology at UMT. The pipeline can be adapted for docking against other viral protein targets.
