graph TD
    A[Data Collection] --> B[Data Preprocessing]
    B --> C[Ligand-based Virtual Screening]
    B --> D[Structure-based Virtual Screening]
    C --> F[Model Development - Molecular Similarity]
    D --> G[Model Development - Molecular Docking]
    D --> H[Model Development - Pharmacophore Modeling]
  
    F --> J[Model Validation - Molecular Similarity]
    G --> K[Model Validation - Molecular Docking]
    H --> L[Model Validation - Pharmacophore Modeling]

    J --> N[Optimized Molecular Similarity Model]
    K --> O[Optimized Molecular Docking Model]
    L --> P[Optimized Pharmacophore Model]
    N --> Q[Consensus Scoring and Ranking]
    O --> Q
    P --> Q
    Q --> R[Hit Identification and Prioritization]
    R --> S[Hits and Lead Compounds]
    S --> T[Hit-to-Lead and Lead Optimization]
    