# Amazon Vine Analysis

---

The purpose of this analysis is to predict credit risk for loan borrowers by building and evaluation multiple models to see how well they predict data.

---

# Naive Random Oversampling 

![naive_random_oversampling](https://user-images.githubusercontent.com/92961267/162644579-11b93c03-51f2-45d2-a5de-72ff915615d0.png)

---

# Easy Ensemble ADA Classifier

![easy_ensemble_ada_classifier](https://user-images.githubusercontent.com/92961267/162644580-ab669283-2f0e-4f26-8d91-bf9a35fa0f28.png)

---

# Combination Sampling

![combination_sampling](https://user-images.githubusercontent.com/92961267/162644582-f5bb3306-d17c-45d1-8f48-c9d7ffa04da4.png)

---

# Balanced Random Forest Classifier
![balanced_random_forest_classifier](https://user-images.githubusercontent.com/92961267/162644583-0c7932a5-ec16-4f36-8cdd-8630aac82d6d.png)

---

# SMOTE Oversampling

![smot_oversampling](https://user-images.githubusercontent.com/92961267/162644585-b761447e-31f2-46e3-8734-9327f18d87bd.png)

---

# Undersampling

![undersampling](https://user-images.githubusercontent.com/92961267/162644586-621174ce-faec-423d-a9d9-d0c13fe2222e.png)

---

# Summary

The methods tested follow similar trends where the model predicted with higher accuracy for low-risk borrowers, and slightly lower accuracy for high-risk borrowers hence producing the possibility of consumers defaulting on a loan. The only methods that does not follow this trend are naive random oversampling and combination sampling. The method with highest accuracy is easy ensemble ADA classifier with the lowest accuracy per method being undersampling. With this information, it is strongly recommended to use the easy ensemble ADA classifier method as it has achieved higher accuracy for future models.
