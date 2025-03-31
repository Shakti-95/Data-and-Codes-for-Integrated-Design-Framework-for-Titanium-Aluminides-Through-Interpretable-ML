1. ``1-MPR_models-TiAl.ipnyb``: Jupyter notebook of building various multi-property regression models mapping from composition and test temperature to mechnanical properties and saving their performance metrics.

2. ``2-MPR_Results.ipynb``: Jupyter notebook to compare the performance metrics of various MPR models and visualize them using heatmap. Also, the comparison of performance metrics of Random Forest Regressor (best) and Deep Neural Network Regressor (second best). Below is the heatmap and comparison bar plots generated.

![Figure 5](https://github.com/user-attachments/assets/16b820d5-be40-483a-b085-00ef5ee4a732)

3. ``3-MPR-RF-DNNrect_BO.ipynb``: Jupter notebook to perform multi-property Bayesian optimization on the set mechanical property targets inspired from the reference Ti-4822 alloy using the 2 selected MPR models. Further, this notebook also contains the interpretability of the MPR models which is shown below.

Random Forest Regression:
![Figure 6](https://github.com/user-attachments/assets/cf519f64-24f5-43ee-8982-a0baaafe2bb9)
![Figure 7](https://github.com/user-attachments/assets/e1b852a3-8809-4723-b5a2-df9b93e14a84)

Deep Neural Network:
![DNNrect SHAP Bar Plots](https://github.com/user-attachments/assets/4b4fa1b7-e9ac-49d2-bf02-a98b9123d3fd)
![DNNrect SHAP Beeswarm Plots](https://github.com/user-attachments/assets/c5723e53-f15a-4cfc-b26e-236764642335)

4. ``4-MPR_RF_BO_Results_analysis.ipynb``: Jupter notebook to perform statistical analyze the top 10 composition predictions using MPBO and their respective properties using RFR or DNNR MPR model. Below is the figure generated in it.

![Figure 8](https://github.com/user-attachments/assets/753a2955-1fbb-4c3b-b944-ea3bd681f483)
