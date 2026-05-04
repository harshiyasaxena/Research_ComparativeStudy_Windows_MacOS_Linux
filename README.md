# 💻 Comparative Study of Desktop Operating Systems  
## Windows vs macOS vs Linux  

This repository contains the implementation, datasets, analysis scripts, and results for the research project:

> **“A Comparative Study of Windows, macOS and Linux”**

---

## 📌 Overview

Desktop operating systems play a critical role in modern computing environments. This project performs a system-level comparative analysis of three major operating systems:

- Microsoft Windows  
- macOS  
- Linux  

The study evaluates performance, stability, and system behavior under controlled experimental conditions using real-world workloads and automated scripts.

---

## 🎯 Key Focus Areas

The analysis is based on the following 10 core parameters:

- ⚙️ Kernel Transition Overhead  
- 🔄 Background Service Interference Index (BSII)  
- 🧠 Cold vs Warm Cache Performance  
- 🔧 Update-Induced Performance Regression  
- 💻 Developer Workflow Latency  
- 🔐 Permission Friction Analysis  
- 🖥️ Virtualization Overhead Differential  
- ♻️ System Recovery Time  
- 🌡️ Thermal Throttling Sensitivity  
- 📊 Performance Variance Stability Index (PVSI)  

---

## 🧠 Methodology

**Platforms Compared:** Windows, macOS, Linux  
**Experimental Runs:** 90 total runs (30 per OS)  

### Data Collection Tools
- **Windows:** PerfMon, ETW  
- **macOS:** Activity Monitor, DTrace  
- **Linux:** perf, top  

### Processing Approach
- Raw logs → Parsed using Python scripts  
- Converted into structured datasets (CSV/Excel)  
- Normalized and analyzed using Jupyter notebooks  

### Analysis Techniques
- Feature extraction & standardization  
- Composite metric computation (BSII, PVSI)  
- Cross-platform comparison  
- Visualization using Python  

---

## 📂 Repository Structure

```plaintext
├── datasets/
│   └── Excel datasets for each parameter (10 datasets)
│
├── notebooks/
│   └── Jupyter notebooks (.ipynb) for each parameter analysis
│
├── graphs/
│   └── Generated graphs and visualizations
│
├── Research_Paper.pdf
│   └── Final Research Paper
│
├── README.md
│   └── Project documentation
```

---

## 📊 Datasets

Each parameter has:

- 📁 1 Excel dataset (.xlsx)  
- 📓 1 Jupyter Notebook (.ipynb)  

Data includes:

- Execution time  
- Runtime variance  
- System behavior metrics  
- Resource utilization  

---

## ⚙️ Key Scripts / Notebooks

- Data preprocessing and normalization  
- Metric computation (BSII, PVSI)  
- Platform-wise comparison  
- Visualization generation  

---

## 📈 Results & Insights

Key findings from the study:

- **Linux** → Highest performance & stability  
- **macOS** → Balanced performance with strong security  
- **Windows** → Best recovery time but higher background interference  

---

## 🚀 Future Enhancements

- Dynamic workload-based evaluation  
- Machine learning-based performance prediction  
- Hardware diversity (low-end to high-end systems)  
- Enhanced user perception analysis  

---

## 📄 Research Contribution

This project introduces:

- A unified experimental framework for OS comparison  
- Novel composite metrics:  
  - BSII (Background Service Interference Index)  
  - PVSI (Performance Variance Stability Index)  
- Integration of system-level + user-level analysis  

---

## 👩‍💻 Authors

- Harshiya Saxena  
- Divyam Agarwal  
- Harshit  
- Shruti Goel  

---

## 📜 License

This project is for academic and research purposes.

---

## ⭐ Notes

- All experiments were conducted under controlled conditions  
- Hardware configurations were kept consistent to ensure fairness  
- Results reflect relative system behavior, not absolute benchmarks  
