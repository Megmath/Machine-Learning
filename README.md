# Machine-Learning
Meghna Mathur

Python version:
C:\Users\hp\.spyder-py3>python
Python 3.7.0 (v3.7.0:1bf9cc5093, Jun 27 2018, 04:59:51) [MSC v.1914 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.

Install pandas:
C:\Users\hp\.spyder-py3>py -m pip install --user pandas

Run example:
C:\Users\hp\.spyder-py3>python DecisionTree.py
Enter training set path: C:/Users/hp/Documents/Python Scripts/data_sets2/training_set.csv
Enter test set path: C:/Users/hp/Documents/Python Scripts/data_sets2/test_set.csv
Enter validation set path: C:/Users/hp/Documents/Python Scripts/data_sets2/validation_set.csv
L: 5
K: 9
to_print: yes

****************************************************************************************************
Print Tree condition:
if to_print = 'yes' : trees will be printed
if to_print = 'no' : trees will not be printed

****************************************************************************************************
Order of output program execution:

---Tree built using entropy---

1. Tree built using training data set 
2. Accuracy calculated on original tree using test data set
3. Pruning performed using validation data set
4. Best pruned tree selected based on maximum accuracy
5. Accuracy calculated for best tree using test data set

---Tree built using variance impurity---

1. Tree built using training data set 
2. Accuracy calculated on original tree using test data set
3. Pruning performed using validation data set
4. Best pruned tree selected based on maximum accuracy
5. Accuracy calculated for best tree using test data set
