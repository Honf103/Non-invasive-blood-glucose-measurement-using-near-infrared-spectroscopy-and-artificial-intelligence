<img width="755" height="365" alt="image" src="https://github.com/user-attachments/assets/d8e017e0-db8e-47f5-aea4-f7a3762a7e20" /># NON-INVASIVE-BLOOD-GLUCOSE-MEASUREMENT-USING-NEAR--INFRAME-SPECTROSCOPY-AND-ARTIFICIAL-INTELLIGENCE
This project is thesis [📄 Thesis](https://drive.google.com/file/d/1J9sLnxg-8vdfhpK4DywxVm-kVhrDq6bC/view?usp=sharing) and publish at MAPR2023[📄 Paper](https://ieeexplore.ieee.org/abstract/document/10289110)

Abstract: Diabetes is an increasingly prevalent chronic disease that leads to severe complications and poses significant societal challenges. As no definitive cure currently exists, regular monitoring of blood glucose levels is essential—especially for diabetic patients—to maintain safe glycemic ranges and reduce the risk of complications. Conventional glucose monitoring methods are primarily invasive or minimally invasive. While invasive methods are widely used due to their accuracy and affordability, they require needle-based blood sampling, causing discomfort and inconvenience. Minimally invasive approaches partially address these limitations but remain costly and do not fully eliminate skin contact. To overcome these challenges, this study proposes the design and development of a non-invasive blood glucose monitoring system based on VIS–NIR spectroscopy and the Beer–Lambert law of light absorption. The proposed system achieves a measurement deviation of only 5.681% compared to the invasive ACCU-CHEK Instant device. Among the evaluated models, Random Forest Regression delivers the best performance, with an R² of 0.86, RMSE of 7.32 mg/dL, and 96.552% of predictions located in Zone A of the Clarke Error Grid, with no points in Zones C, D, or E. Experimental results further indicate that seven wavelengths—585 nm, 610 nm, 645 nm, 680 nm, 705 nm, 730 nm, and 900 nm—have significant influence on glucose estimation. Additionally, the system integrates IoT technology, enabling real-time monitoring and storage of glucose data for up to 30 days, thereby supporting long-term tracking and timely health management decisions.

<p align="center">
  <img width="847" height="474" alt="image" src="https://github.com/user-attachments/assets/ccb32f30-e32e-4a39-94a4-9b847a27824c" />
  <br>
  <em>Figure 1: Hardware Setup</em>
</p>

<p align="center">
  <img width="740" height="291" alt="image" src="https://github.com/user-attachments/assets/6abc89b0-47a6-4303-8e43-af297b1e14f6" />
  <br>
  <em>Figure 2: The algorithm flowchart of the device.</em>
</p>

<p align="center">
  <img width="833" height="456" alt="image" src="https://github.com/user-attachments/assets/94cd0fe6-f943-4602-9b39-948ba8b07902" />  <br>
  <em>Figure 3: The diagram illustrates the process for predicting glucose concentration.</em>
</p>


<p align="center">
  <img width="755" height="365" alt="image" src="https://github.com/user-attachments/assets/c1c338b6-9fac-4e63-81d0-fb284ec8167a" />
  <em>Figure 4: Feature Distribution</em>
</p>

<p align="center">
  <img width="649" height="429" alt="image" src="https://github.com/user-attachments/assets/fab8c5d8-6b8b-4936-9470-31fec6047fc6" />
  <em>Figure 5: FScore of Features</em>
</p>

<p align="center">
<img width="794" height="319" alt="image" src="https://github.com/user-attachments/assets/179030e0-5547-4ece-89d9-afa289ffef88" />
  <em>Figure 6: Distribution in CGE with the entire dataset. (a) GPR, (b) RF, (c) SVR</em>
</p>

In conclusion, this study successfully collected a dataset from 102 volunteers, comprising 431 samples with 18 wavelength features and corresponding reference glucose values. F-test analysis identified seven key wavelengths (585, 610, 645, 680, 705, 730, and 900 nm) that significantly influence glucose estimation. Three machine learning models—Support Vector Regression, Gaussian Process Regression, and Random Forest Regression—were evaluated, all achieving strong performance (R² > 0.80 and over 95% of predictions in Zone A of the Clarke Error Grid). Among them, Random Forest Regression demonstrated the best results (R² = 0.86, RMSE = 7.32 mg/dL, 96.552% in Zone A) and was deployed on a Raspberry Pi 4 Model B for real-time prediction. The proposed system achieved an average deviation of 5.681% compared to the ACCU-CHEK Instant invasive device. Additionally, a smartphone application was developed to enable monitoring and storage of glucose measurements for up to 30 days, supporting practical and continuous health management.




