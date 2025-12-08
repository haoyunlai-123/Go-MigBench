# Go-MigBench

## Benchmarking Large Language Models for Automated Library Migration in Go Programming

**Go-MigBench** is the first comprehensive benchmark designed to evaluate the capabilities of Large Language Models (LLMs) in automating library migrations within the Go ecosystem. It focuses on the intelligent fusion of heterogeneous data sources—code history, API documentation, and runtime traces—to ensure semantic equivalence in code evolution.

---

## 📥 Data Access (Full Dataset)

Due to the large size of the dataset and file quantity limitations, **this GitHub repository contains representative examples** to demonstrate the data structure and migration patterns.

**🚀 The complete dataset is available for download via Google Drive:**

👉 **[Download Full Go-MigBench Dataset](https://drive.google.com/drive/folders/181RkfcdqPQjel9zGm7EIURO33Fqr7ytO?usp=drive_link)**

The full dataset includes:
- **1,235** migration scenarios across **88** libraries.
- **646** instances with fully executable test cases (Ground Truth).
- Detailed metadata including commit history, API mapping, and documentation context.

---

## 📊 Dataset Statistics

| Feature | Count / Description |
| :--- | :--- |
| **Total Libraries** | 88 |
| **Total Migrations** | 1,235 |
| **Executable Tests** | 646 |
| **Migration Types** | Library Replacement (e.g., `OpenTracing` → `OpenTelemetry`) <br> Version Upgrades (e.g., `gorm v1` → `v2`) |
| **Key Categories** | Observability, Database Drivers, Web Frameworks, Logging, etc. |

---

## 📂 Repository Structure (Preview)

This repository provides a preview of the data structure found in the full dataset:

```text
.
├── examples/                   # Representative migration samples
│   ├── code_migrations/        # Source code before and after migration
│   └── withTest/               # Executable test cases for validation
├── README.md                   # Project documentation
└── LICENSE                     # License file