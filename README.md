# Amazon-Product-Recommendation-System
This project involves recommending the best Amazon products available to users based on past rating data using recommendation systems techniques.

# Course
Recommendation System

**Skills and Tools Covered:**

* Rank-Based Recommendation System
* Similarity-based Recommendation system
* Matrix factorization based Recommendation system

# Business Problem and Data Overview
Amazon has given the task of building a recommendation system to recommend products to customers based on their previous ratings for other products. A collection of labeled data of Amazon reviews of products is given. The goal is to extract meaningful insights from the data and build a recommendation system that helps in recommending products to online consumers.

**Dataset**

The Amazon dataset contains the following attributes:

*  **userId:** Every user identified with a unique id
*  **productId:** Every product identified with a unique id
*  **Rating:** The rating of the corresponding product by the corresponding user
*  **timestamp:** Time of the rating. We will not use this column to solve the current problem

#  Code and resources used
Jupyter notebook

Packages: numpy, pandas, matplotlib, sklearn, seaborn, statsmodels

Sources: From MIT; Data Science and Machine Learning online course

# EDA

**Statistical Analysis**

![Screenshot 2024-05-20 162819](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/8b30353f-b170-4cd9-bc79-a4caa10120a7)

**Barplot**

![Screenshot 2024-05-20 162834](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/9b331e2b-d1e3-40d0-b610-e5828180f479)

# Rank-Based model

**Recommending top 5 products with 100 minimum interactions based on popularity**

![Screenshot 2024-05-20 163423](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/44ed2ae5-2d23-4453-84a0-0017fcd7e254)

# User-user similarity-based model

![Screenshot 2024-05-20 163729](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/d752b8da-48b5-4774-9bfe-49882ee43917)

**Tuned Model**

![Screenshot 2024-05-20 163952](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/a61e5fde-cd32-48d4-a748-67e811a86522)

# Item-item similarity-based model

![Screenshot 2024-05-20 164345](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/238ab713-f47b-406b-8cdc-748949329d1c)

**Tuned Model**

![Screenshot 2024-05-20 164401](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/18dc0d6d-042c-42a5-b1c6-72ff0e99ac7c)


# Matrix Factorization based model

 **SVD**

 ![Screenshot 2024-05-20 164626](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/3a36517d-54f9-478e-9b0e-4e450aa506a8)

**Tuned Model**

![Screenshot 2024-05-20 164806](https://github.com/knowl01/Amazon-Product-Recommendation-System/assets/135021827/e7d41456-824c-4503-b1f8-0d49bfbaa1f3)
