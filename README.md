# Impact of Noise on Medical Datasets

This repository contains the code and datasets used in our research paper,  
**"Comparing Classifiers in the Presence of Noise in True Labels in Medical Datasets."**  
Our study systematically investigates how varying levels of label noise (0–40%) affect the performance of several machine learning classifiers across diverse medical datasets.

---

## Repository Contents

- **Code:**  
  Python scripts and Jupyter notebooks for data processing, noise simulation, model training, and evaluation.
  
- **Datasets:**  
  The study includes the following datasets:
  - **MIMIC-IV (Sepsis Prediction):** Contains 95,000 ICU patient samples with vital signs and lab results for predicting sepsis onset.
  - **GSE2034 (Breast Cancer Prognosis):** A gene expression microarray dataset with 286 samples used to predict distant metastasis in node-negative breast cancer.
  - Additional datasets include stroke prediction, UCI Heart Disease, and Pima Indians Diabetes datasets.

- **Results:**  
  Tables, graphs, and plots that illustrate the impact of label noise on performance metrics such as accuracy, TPR, TNR, PPV, and F1 score.

---


MIMIC-IV (Sepsis Prediction)
	•	Citation (PhysioNet version):
 @article{johnson2023mimic,
  title={MIMIC-IV, a freely accessible electronic health record dataset},
  author={Johnson, Alistair EW and Bulgarelli, Lucas and Shen, Lu and Gayles, Alvin and Shammout, Ayad and Horng, Steven and Pollard, Tom J and Hao, Sicheng and Moody, Benjamin and Gow, Brian and others},
  journal={Scientific data},
  volume={10},
  number={1},
  pages={1},
  year={2023},
  publisher={Nature Publishing Group UK London}
}


GSE2034 (Breast Cancer Prognosis)
	•	Citation:
@article{wang2005gene,
  title={Gene-expression profiles to predict distant metastasis of lymph-node-negative primary breast cancer},
  author={Wang, Yixin and Klijn, Jan GM and Zhang, Yi and Sieuwerts, Anieta M and Look, Maxime P and Yang, Fei and Talantov, Dmitri and Timmermans, Mieke and Meijer-van Gelder, Marion E and Yu, Jack and others},
  journal={The Lancet},
  volume={365},
  number={9460},
  pages={671--679},
  year={2005},
  publisher={Elsevier}
}
