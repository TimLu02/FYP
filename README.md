# FYP
Active 18 hosts the Unet model with cross entropy as the loss function and groupnorm as the normalization layer
Active 20 hosts the Unet model with dice loss as the loss function and batchnorm2d as the normalization layer
Active 21 hosts the Unet model with dice loss and ReLU as activation function 
Active 22 hosts the Unet model with dice loss function as well as different groupnorm parameters, and has the best performance.
baseline_1 and baseline_2 uses the age features from the survival data to generate regression and classification prediction, and their 
performances will serve as the base line.
Compute_mask_feature_selection... uses pyradiomic package to conduct feature extraction using the results generated by the best model from Active 22
Prediction_computed_mask conduct feature selection and generate predictions
