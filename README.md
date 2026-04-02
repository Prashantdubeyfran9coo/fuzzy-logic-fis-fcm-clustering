# Fuzzy Logic Controller and Fuzzy C-Means Clustering

This project implements fuzzy logic systems and fuzzy clustering algorithms from scratch using Python.

The work demonstrates the design of a fuzzy controller and clustering techniques used in machine learning and soft computing.

---

# Topics Covered

• Mamdani Fuzzy Inference System
• Fuzzy C-Means Clustering
• Effect of fuzzifier parameter
• Comparison with K-Means clustering

---

# Task 1 – Mamdani Fuzzy Inference System

A fuzzy controller was designed to correct a variable to its target value using two inputs:

Input variables

Error (e)
Range: [-10, 10]

Error rate (ė)
Range: approximately [-1.2, 1.2]

Output variable

Control action (u)
Range: [-100, 100]

Seven triangular membership functions were defined:

NL – Negative Large
NM – Negative Medium
NS – Negative Small
AZ – About Zero
PS – Positive Small
PM – Positive Medium
PL – Positive Large

Inference method used:

AND operator → minimum
Aggregation → maximum

Defuzzification method:

Centroid (center of area)

The system was tested using multiple input pairs to observe the aggregated output membership functions.

---

# Task 2 – Fuzzy C-Means Clustering

Fuzzy C-Means clustering was implemented from scratch.

Key features:

• Membership matrix initialization
• Cluster center update
• Objective function minimization
• Iterative convergence

Datasets used:

D1 – Land Mines dataset
D2 – Synthetic two-moons dataset with outliers

The clustering results are visualized along with cluster centers and membership strengths.

---

# Effect of Fuzzifier Parameter

The algorithm was tested with different values of fuzzifier parameter:

m ∈ {1.25, 1.5, 2, 3}

Metrics used for evaluation:

Partition Coefficient (PC)

Classification Entropy (CE)

Plots show how increasing the fuzzifier produces more diffuse cluster memberships.

---

# Comparison with K-Means

Fuzzy C-Means clustering was compared with standard K-Means clustering.

Steps performed:

• Convert fuzzy memberships to crisp labels
• Align clusters using Hungarian matching
• Compute mismatch rate

The comparison highlights the advantage of fuzzy clustering for ambiguous or overlapping data points.

---

# Technologies Used

Python
NumPy
Matplotlib
Scikit-learn

---

# How to Run

Install required libraries

pip install numpy matplotlib scikit-learn

Run the notebook

jupyter notebook assignment3fuzzy.ipynb

---

# Author

Prashant Dubey
Undergraduate Student

GitHub
https://github.com/Prashantdubeyfran9coo



#Images

<img width="1189" height="490" alt="image" src="https://github.com/user-attachments/assets/05e10390-32a8-48ea-be7c-34aba38f0df4" />
<img width="825" height="526" alt="image" src="https://github.com/user-attachments/assets/efe6fe66-4848-4c31-9af1-8a81800544d5" />
<img width="644" height="656" alt="image" src="https://github.com/user-attachments/assets/a4530f37-1313-401c-864e-d0044b44273f" />


