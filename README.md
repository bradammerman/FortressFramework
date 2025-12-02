# 🛡️ FORTRESS Framework

**Framework for Organized RedTeam and Threat Response Evaluation for Security and Safeguards**

FORTRESS is an open-source, PTES / MITRE ATT&CK-style framework purpose-built for physical security assessments. It enables red teams, blue teams, and auditors to structure, test, and map real-world physical threats against compliance requirements and defensive capabilities.

---

## 🔍 Why FORTRESS?

Unlike cyber threat modeling, physical security still relies heavily on unstructured checklists or tribal knowledge. FORTRESS brings a unified language to physical security testing — from badge cloning and tailgating to surveillance evasion and access control bypass.

### ✅ Key Features:
- MITRE-style **Tactics, Techniques, and Procedures (TTPs)** for physical security
- **Mapped to compliance**: CMMC, FedRAMP, HIPAA, ISO 27001, NIST 800-53, PCI DSS, and more
- Aligned to **Red, Blue, and Audit** workflows
- JSON and CSV output for integration into GRC and security platforms
- Interactive matrix + playbooks (coming soon)

---

## 📂 Repository Contents

| File/Folder | Description |
|------------|-------------|
| `fortressframework.json` | Machine-readable JSON of all TTPs and compliance mappings |
| `Fortress_Framework_v9.xlsx` | Full matrix of TTPs and standards |
| `excel_to_json_complete.py` | python script to convert Fortress_Framework_v9.xlsx to fortressframework.json |
| `playbooks/` | Coming soon: Detection and response playbooks per Tactic |

---

## ⚔️ Example Use Cases

- Physical red team engagement scoping and reporting
- Defensive gap analysis for facilities and campuses
- SOC 2, HIPAA, or PCI DSS readiness checks
- Blue team physical detection mapping and drill simulation
- GRC integration into compliance platforms or risk dashboards

---

## 🧠 Compliance Coverage

Mapped to 50+ frameworks and standards, including:
- **PCI DSS**
- **FedRAMP & NIST SP 800-53**
- **HIPAA**
- **ISO/IEC 27001**
- **SOC 2**
- **CMMC**
- **FISMA / CJIS / StateRAMP**
- **OSHA / NFPA / ADA**

---

## 🚀 Getting Started

1. Clone this repository  
   `git clone https://github.com/your-org/fortressframework.git`

---

## 🤝 Contributing

Want to help grow the framework?  
We welcome community contributions, corrections, and new technique submissions. See [`CONTRIBUTING.md`](./CONTRIBUTING.md) to get started.

---

## 🧾 Citation

If you reference this work in research or professional presentations, please cite it as:

> Ammerman, B. (2025). _FORTRESS: A Structured Framework for Physical Security Testing and Compliance Alignment._ 

---

## 🙏 Acknowledgments

Special thanks to:
- The consultants who field-tested early versions of FORTRESS
- The mentors and peers who encouraged open sourcing
- The community of physical security testers who inspired this work

---

## 🔐 License

FORTRESS is open-sourced under the [MIT License](./LICENSE).  
Use it, break it, improve it — just give credit where it's due.

---

## 🌐 Visit the Live Site

Explore FORTRESS online at:  
🔗 [https://fortressframework.com](https://fortressframework.com)
