# Demo-code

[![CI/CD Pipeline](https://github.com/Xiaohu-Zheng/Demo-code/workflows/CI/CD%20Pipeline/badge.svg)](https://github.com/Xiaohu-Zheng/Demo-code/actions)
[![Python](https://img.shields.io/badge/python-3.8%20%7C%203.9%20%7C%203.10-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![MATLAB](https://img.shields.io/badge/MATLAB-Compatible-orange)](https://www.mathworks.com/)

**Algorithms for Bayesian Network Modeling and Reliability Inference of Complex Multistate Systems**

## 📖 Overview

This repository provides demo code for the paper:

> **Algorithms for Bayesian network modeling and reliability inference of complex multistate systems: Part I – Independent systems**  
> *Zheng, Xiaohu et al.*

## 🌟 Key Features

- **Bayesian Network Modeling**: Advanced modeling techniques for multistate systems
- **Reliability Inference**: Efficient inference algorithms
- **Compression Methods**: Novel compression techniques for complex systems
- **Independent Systems**: Specialized algorithms for independent component systems
- **MATLAB Implementation**: Ready-to-use MATLAB demonstrations

## 🚀 Quick Start

### Prerequisites

- MATLAB R2018a or later
- Statistics and Machine Learning Toolbox

### Installation

```bash
# Clone the repository
git clone https://github.com/Xiaohu-Zheng/Demo-code.git
cd Demo-code

# Extract the demo files
unzip "Demo code.zip"
```

### Basic Usage

```matlab
% Navigate to the extracted directory
cd "Demo code"

% Run compression process demo
cd Demo_for_compression_process
Demo_for_compression_process

% Run inference time analysis
cd ../Demo_for_Inference_time_analysis
% Choose appropriate subdirectory and run experiments
```

## 📁 Project Structure

```
Demo-code/
├── Demo code.zip                       # Compressed MATLAB demo files
│   ├── Demo_for_compression_process/   # Compression algorithm demo
│   │   ├── Demo_for_compression_process.m
│   │   ├── Component_state_combination.p
│   │   ├── NPT_System.p
│   │   ├── Structure_Function.p
│   │   └── ... (other utilities)
│   └── Demo_for_Inference_time_analysis/  # Inference analysis
│       ├── None_Parallel_Reliability_inference_by_CA_method/
│       │   ├── Experiment_case2_CA_none_parallel.m
│       │   ├── Multistate_CA_Probability_Algorithm.p
│       │   └── ... (other functions)
│       └── ... (other analysis methods)
├── .github/workflows/                  # CI/CD configuration
│   └── ci.yml
├── tests/                              # Test suite
│   └── test_basic.py
├── .gitignore
├── requirements.txt
├── LICENSE                             # MIT License
├── Readme                              # Original readme
└── README.md                           # This file
```

## 🔧 Core Algorithms

### 1. Compression Process

```matlab
% Demonstrate the compression process
Demo_for_compression_process
```

This demo shows:
- Component state combinations
- System structure functions
- Compression of probability tables

### 2. Inference Analysis

```matlab
% Run inference time analysis
Experiment_case2_CA_none_parallel
```

This experiment:
- Implements Compression Algorithm (CA) method
- Analyzes inference time
- Compares different approaches

## 📊 Algorithm Description

### Bayesian Network Modeling

The algorithm implements:

1. **System Modeling**: Defines component relationships
2. **State Combinations**: Generates all possible system states
3. **CPT Compression**: Compresses Conditional Probability Tables
4. **Reliability Inference**: Calculates system reliability

### Mathematical Foundation

**System Reliability**:

```
R_system = ∑ P(System_State = Working | Component_States)
```

**Compression Ratio**:

```
CR = (Original_CPT_Size - Compressed_Size) / Original_CPT_Size
```

## 🎯 Applications

- **Multistate Systems**: Systems with multiple operational states
- **Independent Components**: Systems with independent failure modes
- **Reliability Analysis**: Probabilistic reliability assessment
- **Bayesian Networks**: Efficient inference in large networks

## 📈 Performance

The demo demonstrates:

- **Compression Efficiency**: Significant reduction in CPT size
- **Inference Speed**: Faster computation with compressed models
- **Scalability**: Handles complex multistate systems

## 🧪 Examples

### Compression Demo

```matlab
% Navigate to compression demo directory
cd "Demo code/Demo_for_compression_process"

% Run the demo
Demo_for_compression_process

% This will:
% 1. Define system structure
% 2. Generate state combinations
% 3. Apply compression
% 4. Display compression results
```

### Inference Analysis

```matlab
% Navigate to inference analysis directory
cd "Demo code/Demo_for_Inference_time_analysis/None_Parallel_Reliability_inference_by_CA_method"

% Run the experiment
Experiment_case2_CA_none_parallel

% This will:
% 1. Load system configuration
% 2. Apply CA method
% 3. Calculate reliability
% 4. Measure inference time
```

## 📖 Citation

If you use this code in your research, please cite:

```bibtex
@article{Zheng2020DemoCode,
   author = {Zheng, Xiaohu and others},
   title = {Algorithms for Bayesian network modeling and reliability inference of complex multistate systems: Part I – Independent systems},
   journal = {Journal Name},
   year = {2020}
}
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

- **Author**: Xiaohu Zheng
- **Email**: zhengxiaohu16@nudt.edu.cn
- **GitHub**: [@Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

## 🙏 Acknowledgments

- National University of Defense Technology
- Research collaborators

---

**Star ⭐ this repository if you find it helpful!**
