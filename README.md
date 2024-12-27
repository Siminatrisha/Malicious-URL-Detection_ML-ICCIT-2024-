# Malicious URL Detection Using Ensemble Machine Learning

![Overall Architecture](https://github.com/Siminatrisha/Malicious-URL-Detection_ML-ICCIT-2024-/blob/main/Overall_Architecture.PNG?raw=true)

## Overview
Social networks have become an integral part of modern life, with billions of users globally. However, their popularity has made them a prime target for fraudsters utilizing malicious URLs. Traditional URL-classification methods often fall short due to the dynamic and ever-changing strategies employed by attackers. 

This project proposes a novel **Ensemble Machine Learning approach** to detect malicious URLs effectively and efficiently. By leveraging advanced feature selection techniques, we aim to enhance detection accuracy and computational performance.

---

## Key Features
- **Ensemble Machine Learning Model**:
  - Combines Decision Tree, Random Forest, Extra Tree, and XGBoost algorithms.
- **Feature Selection with Particle Swarm Optimization (PSO)**:
  - Improves model performance and reduces computational complexity.
- **Evaluation on ISCX-URL2016 Dataset**:
  - Achieved an accuracy of **98.46%** with the proposed method.
- **Performance Analysis**:
  - Demonstrates better accuracy and runtime efficiency compared to deep learning methods and existing approaches.
- **Efficient Computation**:
  - Total execution time of **56.98 seconds** with optimized feature selection.

---

## Methodology
1. **Feature Selection**:
   - Applied Particle Swarm Optimization (PSO) to refine feature subsets.
2. **Ensemble Learning**:
   - Combined the strengths of Decision Tree, Random Forest, Extra Tree, and XGBoost.
3. **Comparison with Deep Learning**:
   - Benchmarked performance against popular deep learning models.
4. **Dataset**:
   - Utilized the ISCX-URL2016 dataset for evaluation.

---

## Results
- **Accuracy**: 98.46%
- **Runtime**: 56.98 seconds with selected features.
- Outperformed existing methods and deep learning techniques in both accuracy and efficiency.

---

## Project Structure
- `src/`: Contains code implementation for the proposed model.
- `data/`: Includes the ISCX-URL2016 dataset (not provided here due to size constraints).
- `results/`: Outputs and visualizations of the experiments.
- `Overall_Architecture.PNG`: Visual representation of the architecture.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Siminatrisha/Malicious-URL-Detection_ML-ICCIT-2024-
