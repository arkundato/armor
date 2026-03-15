Supplementary Material Section B

B.5.4 Configuration Accuracy Ranking Against the Ensemble Mean
To identify which individual simulation best reproduces the ensemble-averaged behaviour, each retained configuration was ranked by its deviation from the ensemble mean curve using three complementary stress-space metrics evaluated over the full common strain range:
RMSE: Root mean-square error of the stress residuals (GPa), emphasising large localised deviations.
MAE: Mean absolute error of the stress residuals (GPa), providing a robust average deviation measure.
MaxAE: Maximum absolute error (GPa), identifying the worst-case point-wise deviation anywhere along the curve.

Figure Fig.B.1 shows the Young's modulus of three AlTiV matrix material configurations for different seeds. The simulated material input data are data1.txt, data2.txt and data3.txt. Do run the python code to compoute Young's modulus.

  Rank  File                      E(GPa) RMSE    MAE      MaxAE    R²_fit     
  ----  -------------------------- --------  -----------  ----------  -----------  ----------     
     1  data2.txt                  98.57   0.03724  0.02954 0.08070  0.99823  
     2  data1.txt                  98.89   0.05074  0.04290 0.10791  0.99672  
     3  data3.txt                  99.09   0.06761  0.05255  0.15427 0.99418  
  Young Modulus mean   : 98.85 GPa
  Std deviation        : 0.12 GPa
  95% CI               : [98.57, 99.09] GPa
