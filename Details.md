# Manufacturing Anomaly Detection Using Statistical Process Control

A comprehensive analysis comparing statistical quality control methods with machine learning approaches for detecting anomalies in manufacturing sensor data.

##  Project Overview

This project implements and compares multiple anomaly detection techniques on manufacturing sensor data, leveraging both classical Statistical Process Control (SPC) methods and modern machine learning algorithms. The goal is to identify equipment failures and process deviations before they lead to costly downtime.

##  Dataset

**Source**: NASA Bearing Dataset / Semiconductor Manufacturing Data

The dataset contains sensor readings from manufacturing equipment including:
- Temperature sensors
- Vibration measurements
- Pressure readings
- Other process variables

**Size**: [Add after loading data]
**Time Period**: [Add after loading data]
**Features**: [Add after loading data]

## 🔧 Methods Implemented

### Statistical Process Control (SPC) Methods
1. **Shewhart Control Charts** (X-bar and R charts)
   - Traditional SPC for monitoring process mean and variability
   - 3-sigma control limits

2. **CUSUM (Cumulative Sum Control Chart)**
   - Detects small shifts in process mean
   - More sensitive than Shewhart charts for sustained shifts

3. **EWMA (Exponentially Weighted Moving Average)**
   - Weighted control chart responsive to recent data
   - Balances sensitivity and stability

4. **Hotelling's T² Chart**
   - Multivariate control chart for monitoring multiple sensors simultaneously
   - Accounts for correlation between variables

### Machine Learning Methods
1. **Isolation Forest**
   - Tree-based ensemble method
   - Effective for high-dimensional data

2. **One-Class SVM**
   - Learns boundary of normal operation
   - Kernel-based approach

3. **Autoencoder**
   - Neural network reconstruction approach
   - Detects anomalies via reconstruction error

4. **Local Outlier Factor (LOF)**
   - Density-based local outlier detection
   - Identifies points in low-density regions

##  Project Structure

```
manufacturing-anomaly-detection/
├── README.md                          # Project overview and documentation
├── requirements.txt                   # Python dependencies
├── data/
│   ├── raw/                          # Original unprocessed data
│   └── processed/                    # Cleaned and preprocessed data
├── notebooks/
│   ├── 01_data_exploration.ipynb     # EDA and data understanding
│   ├── 02_statistical_methods.ipynb  # SPC implementation
│   ├── 03_ml_methods.ipynb           # ML approaches
│   └── 04_comparison_analysis.ipynb  # Method comparison
├── src/
│   ├── data_processing.py            # Data loading and preprocessing
│   ├── statistical_detectors.py      # SPC method implementations
│   ├── ml_detectors.py               # ML method implementations
│   └── evaluation.py                 # Metrics and evaluation functions
└── results/
    ├── visualizations/               # Charts and plots
    └── metrics/                      # Performance metrics
```

##  Getting Started

### Prerequisites
```bash
Python 3.8+
pip install -r requirements.txt
```

### Installation
```bash
git clone https://github.com/Shruti_B_29/manufacturing-anomaly-detection.git
cd manufacturing-anomaly-detection
pip install -r requirements.txt
```

### Usage
1. Start with data exploration:
   ```bash
   jupyter notebook notebooks/01_data_exploration.ipynb
   ```

2. Run statistical methods:
   ```bash
   jupyter notebook notebooks/02_statistical_methods.ipynb
   ```

3. Compare with ML approaches:
   ```bash
   jupyter notebook notebooks/03_ml_methods.ipynb
   ```

## 📈 Key Results

[To be filled after analysis]

### Performance Comparison

| Method | Precision | Recall | F1 Score | Detection Delay |
|--------|-----------|--------|----------|-----------------|
| Shewhart Charts | - | - | - | - |
| CUSUM | - | - | - | - |
| EWMA | - | - | - | - |
| Hotelling's T² | - | - | - | - |
| Isolation Forest | - | - | - | - |
| One-Class SVM | - | - | - | - |
| Autoencoder | - | - | - | - |
| LOF | - | - | - | - |

### Key Findings

1. **Statistical Methods**:
   - [findings here]
   
2. **Machine Learning Methods**:
   - [findings here]

3. **Practical Recommendations**:
   - [recommendations here]

##  Technical Skills Demonstrated

- **Statistics**: Hypothesis testing, control charts, multivariate analysis, process monitoring
- **Machine Learning**: Unsupervised learning, anomaly detection, neural networks
- **Data Processing**: Time series handling, feature engineering, data normalization
- **Visualization**: matplotlib, seaborn for statistical and time series plots
- **Python Libraries**: pandas, numpy, scikit-learn, scipy, statsmodels

##  References

1. Montgomery, D.C. (2012). *Statistical Quality Control*
2. Chandola, V., Banerjee, A., & Kumar, V. (2009). Anomaly detection: A survey
3. [Add ]

##  Author

**[Shruti]**
- LinkedIn: [LinkedIn]
- Email: [Email]
- Portfolio: [Website/GitHub]

##  License

This project is licensed under the MIT License - see the LICENSE file for details.

##  Acknowledgments

- NASA Prognostics Data Repository for the bearing dataset
- [Add]

---

*This project was developed as part of my Data Science portfolio, demonstrating the application of statistical quality control methods and machine learning to real-world manufacturing problems.*
