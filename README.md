# Multiclass_Classification_Handwriting_Detection
This project aims to classify images using three different algorithms - Logistic Regression, KNN Classification, and Random Forest Classification. 


The dataset used for this project is a subset of the Kaggle English Handwritten Characters dataset, which consists of 3410 1200x900 color images with 62 classes (26 Capital & Common Letters of the English Alphabet, and Digits 0-9), with 55 images per class. (Can be accessed at: https://www.kaggle.com/datasets/dhruvildave/english-handwritten-characters-dataset?select=english.csv) However, only the English Capital Letters were used for this analysis.

### **Requirements**:
* Python 3.0 or higher
* NumPy
* Matplotlib
* Scikit-learn
* Pandas
* Pillow
* OS 

### **Installation**:
* Install the required libraries using the first command in the attached driver code.

### **Usage**:
* The program will firstly utilize a function to reduce the resolution and dimensions of the images and make them easier to process by the ML algorithms.
* A sample image will be shown before and after the modification.
* The program will load the Kaggle dataset and split it into training and testing sets.
* The three classification algorithms will be trained on the training set without any sort of optimization.
* The accuracies of each algorithm will be displayed.
* * The algorithms will be optimized via Hyperparameter Tuning & K-Fold Cross-Validation 
* The optimal parameters for each algorithm will be displayed.
* The accuracies of each optimized algorithm will also be displayed along with the precision, recall, and f1-score (classification report). A confusion matrix will not be displayed because it will be a 1530x1530 matrix which will be difficult to interpret and visualize appropriately.
* These metrics can then be used to determine the performance of each algorithm and the algorithms may be ranked based on these values.

### **Execution**:
* The program would probably take a VERY long time to run in completion (~5-7+ hours) based on your system's processing power. For the best computational time results, use a system with at least 16GB of RAM. However, once you run all cells, all results will be computed and displayed without any user interaction.

### **Acknowledgements**:
* The Kaggle dataset was obtained from https://www.kaggle.com/datasets/dhruvildave/english-handwritten-characters-dataset?select=english.csv.
* This project was inspired by the load_digits() dataset in the scikit-learn library.
