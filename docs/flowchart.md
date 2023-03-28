graph TD

A[Project Goals and Scope] --> B[Data Collection]
B --> C[Data Preprocessing]

C --> D[Training, Validation, and Test Data Split]

D --> E1[Ligand-Based Models]
D --> E2[Structure-Based Models]
D --> E3[Multi-Task Models]

E1 --> F1[Model Training and Validation: Ligand-Based]
E2 --> F2[Model Training and Validation: Structure-Based]
E3 --> F3[Model Training and Validation: Multi-Task]

F1 --> G[Model Comparison and Selection]
F2 --> G
F3 --> G

G --> H[Model Fine-tuning and Testing]
H --> I[Virtual Screening]

I --> J[Hit Identification and Prioritization]
J --> K[Hit-to-Lead Optimization]
K --> L[Lead Optimization]

L --> M[Model Validation and Performance Evaluation]
M --> N[Project Conclusion and Future Work]