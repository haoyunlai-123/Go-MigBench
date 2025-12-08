这是一个非常专业且符合学术规范的 `README.md` 模板。

它清楚地解释了**“为什么 GitHub 上只有部分文件”**，并显眼地提供了**完整数据集的下载链接**，同时涵盖了项目介绍、统计数据和引用格式。你可以直接复制使用。

---

### `README.md` 文件内容

```markdown
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
```

## 🛠️ How to Use

To evaluate an LLM using Go-MigBench:

1.  **Download** the full dataset from the Google Drive link above.
2.  **Input**: Provide the `source_old.go` (legacy code) and relevant `migration_context` to the model.
3.  **Output**: Generate the migrated code.
4.  **Validation**: Run the provided test cases in the `withTest` directory to verify semantic correctness.

```bash
# Example command to run a test case (requires Go installed)
cd withTest/example_case_01
go test -v
```

---

## 📝 Citation

If you use **Go-MigBench** in your research, please cite our paper:

```bibtex
@article{xu2025gomigbench,
  title={Benchmarking Large Language Models for Automated Library Migration in Go Programming},
  author={Xu, Kang and Rong, Zeyu and Huang, Chenbo and Xu, Haozhi and Ji, Qiu and Chen, Lei and Dong, Zhenjiang},
  journal={Submitted to Information Fusion},
  year={2025}
}
```

## 📧 Contact

For any questions regarding the dataset or the paper, please contact:
**Kang Xu** (kxu@njupt.edu.cn)

---
*School of Computer Science, Nanjing University of Posts and Telecommunications, China*
```

---