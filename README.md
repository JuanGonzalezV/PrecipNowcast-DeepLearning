# CNN-Based Weather Nowcasting for Extreme Precipitation Events  

This repository contains the code and resources for the thesis:  
**"A Kernel-Based Strategy to Design Convolutional Neural Network Architecture for Learning Spatial and Temporal Representation of Weather Variables"**  

---

## 📄 Abstract  
Extreme precipitation events, defined as periods where empirical rainfall thresholds are abruptly exceeded, are of significant interest to urban planners, water researchers, and climate-related institutions. This thesis proposes a data-driven approach to analyze, nowcast, and classify extreme precipitation events using hydroclimate features from two climatological stations.  

The methodology involves:  
1. **Pre-processing**: Cleaning and preparing precipitation-related time series data.  
2. **Feature Selection**: Applying correlation analysis, Principal Component Analysis (PCA), and Regressional Relief-F (RR) for exploratory analysis.  
3. **Classification**: Using a Support Vector Machine (SVM) classifier.  
4. **Regression**: Designing a Convolutional Neural Network (CNN) with Long Short-Term Memory (LSTM) and 1-D/2-D convolutions to learn spatio-temporal representations of weather variables.  

Results show that non-standardized RR outperforms PCA in feature discrimination, while the CNN-based regression model demonstrates promising nowcasting capabilities for extreme precipitation events.  

---

## 🛠️ Citation
- link: https://repositorio.yachaytech.edu.ec/handle/123456789/388
- APA: González Vergara, J. F. (2021). A kernel-based strategy to design Convolutional Neural Network Architecture for learning spatial and temporal representation of weather variables (Bachelor's thesis, Universidad de Investigación de Tecnología Experimental Yachay).
- - bibtext: @mastersthesis{gonzalez2021kernel,
  title={A kernel-based strategy to design Convolutional Neural Network Architecture for learning spatial and temporal representation of weather variables},
  author={Gonz{\'a}lez Vergara, Juan Fernando},
  type={{B.S.} thesis},
  year={2021},
  school={Universidad de Investigaci{\'o}n de Tecnolog{\'\i}a Experimental Yachay}
}
