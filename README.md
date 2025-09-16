# Advanced Data Analysis - PHYS605

A comprehensive repository for the PHYS605 Advanced Data Analysis course, featuring computational methods, statistical techniques, and data analysis implementations used in physics research.

## 📋 Course Overview

This repository contains educational materials and implementations for advanced data analysis techniques commonly used in physics research, including:

- **Monte Carlo Methods**: Integration techniques and statistical sampling
- **Markov Chain Monte Carlo (MCMC)**: Bayesian inference and parameter estimation
- **Statistical Analysis**: Advanced statistical methods for physics applications
- **Computational Physics**: Numerical methods and data processing techniques

## 📁 Repository Structure

```
PHYS605(DA)/
├── Assignment1/                    # CO2 Data Analysis
│   ├── co2_mm_mlo.txt             # CO2 measurement data from Mauna Loa
│   ├── code2_assignment_1.ipynb   # Data analysis implementation
│   ├── code3_assignment_1.ipynb   # Advanced analysis techniques
│   └── PHYS_605_F23_Assignment_1_New.pdf
├── Assignmnet2/                   # Assignment 2 Materials
│   ├── code2_assignment_2.ipynb
│   └── PHYS_605_F23_Assignment_2.pdf
├── Assignment3/                   # Assignment 3 Materials
│   ├── code1_assignmnet_3.ipynb
│   ├── code2_assignmnet_3.ipynb
│   ├── code3_assignmnet_3.ipynb
│   └── PHYS_605_F23_Assignment_3.pdf
├── Assignmnet4/                   # Assignment 4 Materials
│   ├── code1_assignmnet_4.ipynb
│   ├── code2_assignmnet_4.ipynb
│   └── PHYS_605_F23_Assignment_4.pdf
├── MCMC_methods.ipynb             # Markov Chain Monte Carlo Tutorial
├── monte_carlo_methods_v2_run_class.ipynb  # Monte Carlo Integration
└── code_assignment_4_exercise_2.ipynb     # Additional Exercise
```

## 🔬 Key Topics Covered

### 1. Monte Carlo Integration
- **File**: `monte_carlo_methods_v2_run_class.ipynb`
- **Description**: Implementation of Monte Carlo methods for numerical integration
- **Key Concepts**:
  - Area-based sampling techniques
  - Statistical estimation of π using quarter-circle integration
  - Error estimation and convergence analysis

### 2. Markov Chain Monte Carlo (MCMC)
- **File**: `MCMC_methods.ipynb`
- **Description**: Comprehensive tutorial on MCMC methods
- **Key Concepts**:
  - Metropolis-Hastings algorithm
  - Bayesian parameter estimation
  - Posterior distribution sampling
  - Acceptance/rejection criteria

### 3. Environmental Data Analysis (Assignment 1)
- **Files**: Assignment1 directory
- **Data**: CO2 concentration measurements from Mauna Loa Observatory
- **Techniques**:
  - Time series analysis
  - Trend detection
  - Statistical modeling of atmospheric data

### 4. Advanced Statistical Methods (Assignments 2-4)
- **Files**: Assignment2-4 directories
- **Topics**: Various advanced data analysis techniques and applications

## 🛠️ Requirements

### Python Dependencies
The notebooks require the following Python packages:
```
numpy
matplotlib
scipy
corner  # For corner plots in MCMC analysis
pandas  # For data manipulation
jupyter # For running notebooks
```

### Installation
```bash
pip install numpy matplotlib scipy corner pandas jupyter
```

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/alikauc/Advanced_Data_Analysis_PHYS605.git
   cd Advanced_Data_Analysis_PHYS605
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt  # If available
   # Or install manually:
   pip install numpy matplotlib scipy corner pandas jupyter
   ```

3. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

4. **Navigate to the PHYS605(DA) directory** and open any notebook to begin exploring.

## 📊 Example Applications

### Monte Carlo Integration
The repository demonstrates how to:
- Estimate π using random sampling
- Calculate complex integrals numerically
- Assess convergence and error bounds

### MCMC Parameter Estimation
Learn to:
- Implement Metropolis-Hastings sampling
- Estimate parameters from noisy data
- Create corner plots for parameter visualization
- Analyze posterior distributions

### Environmental Data Analysis
Explore techniques for:
- Processing real-world atmospheric CO2 data
- Identifying long-term trends
- Statistical modeling of environmental time series

## 📖 Educational Objectives

By working through this repository, students will gain practical experience with:

1. **Computational Methods**: Hands-on implementation of numerical techniques
2. **Statistical Inference**: Bayesian and frequentist approaches to data analysis
3. **Real Data Analysis**: Working with actual scientific datasets
4. **Visualization**: Creating informative plots and visualizations
5. **Scientific Computing**: Best practices in computational physics

## 🤝 Usage Guidelines

- Each assignment folder contains both the problem statement (PDF) and implementation (Jupyter notebooks)
- Start with the Monte Carlo methods notebook for foundational concepts
- Progress through assignments sequentially for optimal learning
- Modify and experiment with the code to deepen understanding

## 📧 Contact & Support

This repository serves as educational material for PHYS605. For questions about specific implementations or concepts, refer to the course instructor or teaching assistants.

## 📄 License

This repository contains educational materials for academic use. Please respect academic integrity guidelines when using these materials.

---

*Advanced Data Analysis - PHYS605*  
*Computational methods and statistical techniques for physics research*