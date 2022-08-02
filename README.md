# Logistic-Regression
This is a basic program that applies the mathematical concept of Linear Regression to a data set that has been provided along in the repository.</br>
The data is for breast cancer tumor classification, and uses 9 parameters:</br>
  1. Clump Thickness</br>
  2. Uniformity of Cell Size</br>
  3. Uniformity of Cell Shape</br>
  4. Marginal Adhesion</br>
  5. Single Epithelial Cell Size</br>
  6. Bare Nuclei</br>
  7. Bland Chromatin</br>
  8. Normal Nucleoli</br>
  9. Mitoses</br>
  
To classify the tumor into 2 categories (2-benign, 4- malignant), which is converted into 0,1 format for ease of use.</br>
The program tries to come up with the best line of the form y = W.x + B, via the concept of Gradient Descent. The user has to input the learning rate and number of Epochs.</br>
The program then uses the prebuilt Linear Regression library of Sklearn, and applies the same data set to it as well.</br>
The accuracy of the model is predicted using the R squared value of the model.</br>
