# Imputation

The strategy for imputation used in this work is as follows:
1. Best ML model mapping from *Compostion and Test Temperature* to *log<sub>10</sub> σ<sub>y</sub>* with best performance (high **R_2** and low **MAE** and **RMSE**) is used to fill up the gaps in *log<sub>10</sub> σ<sub>y</sub>* column (**Extra Trees**)
2. Best ML model mapping from *log<sub>10</sub> σ<sub>y</sub>* to *log<sub>10</sub> σ* with best performance is used to fill up the gaps in *log<sub>10</sub> σ* column with respect to filled column of *log<sub>10</sub> σ<sub>y</sub>* (**Deep Neural Network**)
3. Best ML model mapping from *Compostion and Test Temperature* to *log<sub>10</sub> σ* with best performance is used to fill up the gaps in *log<sub>10</sub> σ* column (**Extra Trees**)
4. Best ML model mapping from *Compostion and Test Temperature* to *log<sub>10</sub> δ* with best performance is used to fill up the gaps in *log<sub>10</sub> δ* column (**XGBoost**)

For each step, the values of performance metrics for each model are compiled and stored in excel files.

5-Imputation Results.ipnyb: This jupyter notebook is used for comparing all the performance metrics' values of 12 different models used for the 4 different steps and generating the heat map (shown below).

![Figure 4](https://github.com/user-attachments/assets/91e6e8d8-1b04-4d86-8974-cfa917fbc1d7)
