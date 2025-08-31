# Project 3: RADAR ASW Module Testing for Adaptive Cruise Control (ACC)

## Project Overview
This project focuses on **RADAR ASW (Application Software) module testing** for **Adaptive Cruise Control (ACC)**, specifically for the **Medium Range Radar (MRR)** system.  
The objective was to validate and enhance radar-based ACC functionalities, ensuring effective communication, diagnostics, and fault management for real-time vehicle operations.

### Roles & Responsibilities
- Analyzed requirements for RADAR MRR ASW modules, specifically for ACC functionalities.
- Designed and reviewed test cases to validate ACC performance and ensure compliance with standards.
- Executed test cases, identified defects, and managed the defect lifecycle (logging, tracking, and retesting).
- Performed fix testing and collaborated with developers for issue resolution.
- Ensured compliance with quality standards, improving RADAR ASW robustness in real-world conditions.

---

## Tools & Technologies Used
- **CAN Tools**: Vector CANoe, CANalyzer   
- **Scripting**: CAPL
- **Requirement & Defect Management**: IBM DOORS, JIRA, RQM  
- **Version Control**: Git, GitHub  

---

## 📂 Folder Structure
```plaintext
RADAR_ASW_ACC_Testing/
│── README.md                # Project Overview
│── LICENSE                  # License file
│── .gitignore               # Git ignore rules
│
├── documents/               # Requirements
│   ├── ACC_requirements.xlsx
│
├── testcases_and_execution/ # Test cases and execution results
│   ├── ACC_test_cases_with_results.xlsx
│
├── scripts/                 # Automation scripts
│   ├── capl_script.can
│
├── assets/                  # Supporting diagrams and logos
│   ├── architecture_diagram.png
│   └── logo_placeholder.png
│
└── screenshots/             # Execution results/screenshots
    └── sample_execution.png

---

## How to Run / Test the Project

Open requirements from /documents/ACC_requirements.xlsx.
Review test cases in /testcases_and_execution/ACC_test_cases_with_results.xlsx.
Execute automation scripts in /scripts/ depending on your toolchain:
example_capl_script.can → Load into CANoe environment.
Store outputs and screenshots in /screenshots.

---

## Example Test Case Format

| Test Case ID | Requirement ID | Pre-Condition         | Test Steps               | Expected Result         | Status |
| ------------ | -------------- | --------------------- | ------------------------ | ----------------------- | ------ |
| TC\_ACC\_001 | ACC\_REQ\_001  | Vehicle in drive mode | Enable ACC and set speed | ACC maintains set speed | Pass   |

---

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.