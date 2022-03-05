This is an improved Apriori algorithm and a FP-growth algorithm developed by Liwei Jiang (ljaing14 / ljiang14@u.rochester.edu) and Beilei Guo bguo5@u.rochester.edu with Python 3.7

The HW3.zip will contain the following files:

README.txt		this file
HW3.ipynb		a program include data preprocess, Apriori function, and FP-growth function
adult.data		UCI Adult Census Dataset  http://archive.ics.uci.edu/ml/datasets/Adult

Except just implemented the Apriori algorithm, we also implemented the Transaction reduction technique mentioned in Han's book's 6.2.3. Start from the second scan, the function would remove transaction with out current scanning itemsets to avoid unnecessary scan in future iteration.