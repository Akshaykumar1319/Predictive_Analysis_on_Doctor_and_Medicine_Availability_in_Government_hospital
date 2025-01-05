# Predictive Analytics on Doctor and Medicine Availability in Government Hospitals

## Overview
This repository contains the research paper and supplementary materials for the project: **"Predictive Analytics on Doctor and Medicine Availability in Government Hospitals".** The study explores the use of machine learning models like Deep Neural Networks (DNN), Random Forest, and XGBoost to optimize resource management in healthcare settings.

## Highlights
- Achieved **97.40% accuracy** for predicting doctor availability.
- Achieved **98.56% accuracy** for predicting medicine availability using the DNN model.
- Compared three machine learning models: DNN, Random Forest, and XGBoost.
- Demonstrates the potential of predictive analytics to enhance resource planning in government hospitals.

## Repository Structure
```plaintext
Predictive_Analytics/
├── paper.pdf                 # Full research paper
├── code/                     # Python scripts for model implementation
│   ├── dnn_model.py          # DNN implementation
│   ├── random_forest.py      # Random Forest implementation
│   ├── xgboost_model.py      # XGBoost implementation
├── dataset/                  # Dataset used in the research
│   ├── doctor_availability.csv
├── figures/                  # Visual results and performance graphs
│   ├── confusion_matrix_doctor.png
│   ├── confusion_matrix_medicine.png
├── README.md                 # Project documentation (this file)
```

## How to Use
1. **Prerequisites**:
   - Python 3.8 or later
   - Libraries: TensorFlow, scikit-learn, XGBoost, pandas, matplotlib

2. **Steps to Run**:
   - Clone the repository:  
     ```bash
     git clone https://github.com/yourusername/Predictive_Analytics.git
     ```
   - Navigate to the `code` directory:  
     ```bash
     cd Predictive_Analytics/code
     ```
   - Run the desired model script:  
     ```bash
     python dnn_model.py
     ```

3. **Dataset**:
   - Ensure the dataset `doctor_availability.csv` is placed in the `dataset` folder.

4. **Outputs**:
   - Predictions are generated for doctor and medicine availability.
   - Performance metrics and confusion matrices are saved in the `figures` folder.

## Key Results
| Model           | Doctor Availability Accuracy | Medicine Availability Accuracy |
|-----------------|------------------------------|--------------------------------|
| DNN Sequential  | 97.40%                       | 98.56%                         |
| Random Forest   | 86.90%                       | 50.23%                         |
| XGBoost         | 99.00%                       | 50.07%                         |

## Citation
If you use this work, please cite:
```bibtex
@article{Kumar2025PredictiveAnalysis,
  title={Predictive Analytics on Doctor and Medicine Availability in Government Hospitals},
  author={N. Akshay Kumar, Supriya H.R., Savitha P., Nutan Revani Astekar},
  year={2025},
  journal={Computers in Biology and Medicine},
  note={Manuscript under review},
  url={https://github.com/Akshaykumar1319/Predictive_Analysis_on_Doctor_and_Medicine_Availability_in_Government_hospital/upload/main}
}
```

## Contact
For questions or collaboration, feel free to contact:
- **N. Akshay Kumar**: [eminemakshay38@gmail.com](mailto:eminemakshay38@gmail.com)
- **Supriya H. R.**: [supriyahr7892@gmail.com](mailto:supriyahr7892@gmail.com)
- **Savitha P.**: [savitha13052000@gmail.com](mailto:savitha13052000@gmail.com)
- **Nutan Revani Astekar**: [rekharastekar12@gmail.com](mailto:rekharastekar12@gmail.com)


# Predictive_Analysis_on_Doctor_and_Medicine_Availability_in_Government_hospital
