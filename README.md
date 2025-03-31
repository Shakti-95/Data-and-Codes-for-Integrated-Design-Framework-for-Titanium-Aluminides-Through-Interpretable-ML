# Data and Codes for Integrated Design Framework for Titanium Aluminides Through Interpretable Machine Learning

This repository contains the data and codes for the research work "_**Integrated Design Framework for Titanium Aluminides Through Interpretable Machine Learning**_" authored by _Shakti P. Padhy, Karl P. Davidson, Li Ping Tan, Vijaykumar B. Varma, Vinay K. Sharma, Xiao Tan, Yuefan Wei, Xuesong Xu, Kedar Hippalgaonkar, Mark H. Jhon, & R. V. Ramanujan_ which is currently submitted to Applied Materials Today.

This work addresses the challenge of designing better performance structural materials using incomplete and heterogeneous data in terms of property measurements and different processing conditions of samples, respectively. A machine learning-based imputation technique is developed, inspired from "_**Experimentally Validated Inverse design of Multi-Property Fe-Co-Ni alloys**_" (https://github.com/Shakti-95/Data-and-Codes-for-Experimentally-Validated-Inverse-design-of-Multi-Property-Fe-Co-Ni-alloys), for which the codes are available in the ``2-Imputation`` folder.

The original curated database is present in ``TiAl_prep-db_2.xlsx`` file and the final imputed database is present in ``TiAl_prep-db_YS-ET_TS-final_El_imp-3.csv`` file.

Further, various multi-property models are developed and the best (Random Forest Regressor) and second best (Deep Neural Network) model was selected for further performance study.

Lastly, the inverse design of Ti-Al-Cr-Nb alloy compositions was done using one-shot Multi-Property Bayesian optimization in which mechanical properties and cost of material target sets were given based on reference Ti-4822 alloy (Ti - 48 at% Al - 2 at% Cr - 2 at% Nb). The predicted compositions and predicted property values were experimentally validated.

All of these codes are available in the ``3-Multi-property ML and BO`` folder.

# Cite us
If you used the database or the codes for your research, consider citing our GitHub repository

## GitHub repository citation
```
@dataset{padhy_2025_15114898,
  author       = {Padhy, Shakti Prasad and
                  Davidson, Karl and
                  Tan, Li Ping and
                  Varma, Vijaykumar and
                  Sharma, Vinay kumar and
                  Tan, Xiao and
                  Wei, Yuefan and
                  Xu, Xuesong and
                  Hippalgaonkar, Kedar and
                  Jhon, Mark and
                  Ramanujan, Raju V.},
  title        = {Data-and-Codes-for-Integrated-Design-
                   Framework-for-Titanium-Aluminides-Through-
                   Interpretable-ML: Data and codes release\_v1.0.1
                  },
  month        = mar,
  year         = 2025,
  publisher    = {Zenodo},
  version      = {v1.0.1},
  doi          = {10.5281/zenodo.15114898},
  url          = {https://doi.org/10.5281/zenodo.15114898},
}
```
