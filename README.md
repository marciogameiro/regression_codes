# regression_codes
Welcome to my repository: "regression_codes". This repository is organized in 2 folders: "Predator_prey_equation" and "Ginzburg_Landau_equation". Below we present the description of each folder.
 
 **Ginzburg_Landau_equation** This folder is organized in 8 folder:
    **Figures** : "Regression_beta_feature_10_50_ginzburg_vectorization.pdf", "Regression_beta_feature_3_20_ginzburg_vectorization_7train_10test.pdf" and "Regression_beta_feature_3_20_ginzburg_new_vectorization_7train_10test.pdf" show average R^2 values with RMSE error bars as a function of the parameter m for KNeighbors and SVR regressor for the Ginzburg-Landau equation using the vectorization proposed (binning approach) where the first figure shows all values of β were used for training and testing, the second figure shows the 5 values of the parameter β ∈ {0.1, 1.0, 1.4, 1.6, 4.2} were using for training and the data corresponding to the values of β ∈ {1.2, 1.8} were used only for testing after the model was validated, and the last figure uses the persistence density feature vector where the 5 values of the parameter β ∈ {0.1, 1.0, 1.4, 1.6, 4.2} were using for training and the data corresponding to the values of β ∈ {1.2, 1.8} were used only for testing after the model was validated.
  **File4_CSV, File5_CSV, File6_CSV** : these folders contain the input files *.csv that will be used in python code. File4_CSV and File5_CSV contain files using the vectorization (binning approach), where the first folder contains all values of β were used for training and testing, the second folder contains the 5 values of the parameter β ∈ {0.1, 1.0, 1.4, 1.6, 4.2} were using for training and the data corresponding to the values of β ∈ {1.2, 1.8} were used only for testing after the model was validated. File6_CSV contains files using the persistence density feature vector where the 5 values of the parameter β ∈ {0.1, 1.0, 1.4, 1.6, 4.2} were using for training and the data corresponding to the values of β ∈ {1.2, 1.8} were used only for testing after the model was validated.
  **Results-files4, Results-files5, Results-files6** : these folders contain the output files *.txt after using the code in python. Results-files4 and Results-files5 contain files using the vectorization (binning approach), where the first folder contains all values of β were used for training and testing, the second folder contains the 5 values of the parameter β ∈ {0.1, 1.0, 1.4, 1.6, 4.2} were using for training and the data corresponding to the values of β ∈ {1.2, 1.8} were used only for testing after the model was validated, Results-files6 contains files using the persistence density feature vector where the 5 values of the parameter β ∈ {0.1, 1.0, 1.4, 1.6, 4.2} were using for training and the data corresponding to the values of β ∈ {1.2, 1.8} were used only for testing after the model was validated.
  ***python-code** : This folder contains the code in python: "Ginzburg_regression_code_model1.py"  uses the vectorization (binning approach) and it uses all values of β for training and testing, "Ginzburg_regression_code_model2.py" uses the vectorization (binning approach) and it uses the 5 values of the parameter β ∈ {0.1, 1.0, 1.4, 1.6, 4.2} for training and the data corresponding to the values of β ∈ {1.2, 1.8} were used only for testing after the model was validated, "Ginzburg_regression_code_model3.py" uses the persistence density feature vector where the 5 values of the parameter β ∈ {0.1, 1.0, 1.4, 1.6, 4.2} for training and the data corresponding to the values of β ∈ {1.2, 1.8} were used only for testing after the model was validated.
  
  
  **Predator_prey_equation** This folder is organized in 8 folder:
    **Figures** :  "Regression_beta_feature_10_50_predator_vectorization.pdf", "Regression_beta_feature_3_20_predator_vectorization_7train_10test.pdf" and "Regression_beta_feature_3_20_predator_new_vectorization_7train_10test.pdf" show average R^2 values with RMSE error bars as a function of the parameter m for KNeighbors and SVR regressor for the predator-prey system using the vectorization proposed (binning approach), where the first figure shows all values of β were used for training and testing, the second figure shows the 7 values of the parameter β ∈ {1.80, 1.85, 1.90, 1.95, 2.05, 2.10, 2.15} using for training and the data corresponding to the values of β ∈ {1.75, 2.00, 2.20} for testing after the model was validated, and the last figure uses the persistence density feature vector where the 7 values of the parameter β ∈ {1.80, 1.85, 1.90, 1.95, 2.05, 2.10, 2.15} were using for training and the data corresponding to the values of β ∈ {1.75, 2.00, 2.20} were used only for testing after the model was validated.
   **File1_CSV, File2_CSV, File3_CSV** : these folders contain the input files *.csv that will be used in python code. File1_CSV and File2_CSV contain files using the vectorization (binning approach), where the first folder contains all values of β were used for training and testing, the second folder contains the 7 values of the parameter β ∈ {1.80, 1.85, 1.90, 1.95, 2.05, 2.10, 2.15} were using for training and the data corresponding to the values of β ∈ {1.75, 2.00, 2.20} for testing after the model was validated. File3_CSV contains files using the persistence density feature vector where the 7 values of the parameter β ∈ {1.80, 1.85, 1.90, 1.95, 2.05, 2.10, 2.15} were using for training and the data corresponding to the values of β ∈ {1.75, 2.00, 2.20} for testing after the model was validated.
   **Results-files1, Results-files2, Results-files3** : these folders contain the output files *.txt after using the code in python. Results-files1 and Results-files2 contain files using the vectorization (binning approach), where the first folder contains all values of β were used for training and testing, the second folder contains the 7 values of the parameter β ∈ {1.80, 1.85, 1.90, 1.95, 2.05, 2.10, 2.15} were using for training and the data corresponding to the values of β ∈ {1.75, 2.00, 2.20} were used only for testing after the model was validated. Results-files3 contains files using the persistence density feature vector where the 7 values of the parameter β ∈ {1.80, 1.85, 1.90, 1.95, 2.05, 2.10, 2.15} were using for training and the data corresponding to the values of β ∈ {1.75, 2.00, 2.20} were used only for testing after the model was validated.
   **python-code** : This folder contains the code in python: "predator_prey_regression_codel_model1.py" uses the vectorization (binning approach) and it uses all values of β for training and testing, "predator_prey_regression_codel_model2.py" uses the vectorization (binning approach) and it uses the 7 values of the parameter β ∈ {1.80, 1.85, 1.90, 1.95, 2.05, 2.10, 2.15} for training and the data corresponding to the values of β ∈ {1.75, 2.00, 2.20} were used only for testing after the model was validated, "predator_prey_regression_codel_model3.py" uses the persistence density feature vector where the 7 values of the parameter β ∈ {1.80, 1.85, 1.90, 1.95, 2.05, 2.10, 2.15} were using for training and the data corresponding to the values of β ∈ {1.75, 2.00, 2.20} were used only for testing after the model was validated.
   
