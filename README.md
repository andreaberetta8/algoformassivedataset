# algoForMassiveDataset
The project objective is to implement a system finding frequent itemsets of skills in this LinkedIn Jobs & Skills dataset (https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024).

The detector considers as baskets the sets of skills required for each job announcement and uses the A-Priori algorithm to find all the k-size frequent itemsets. The code is written for scalability using PySpark. The data are loaded in a Resilient Distributed Dataset.
