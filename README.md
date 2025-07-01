### **Supervised ML Regression: Making Sense of Skewed Data! 📈**

Ever tried to predict something, but your data just isn't playing nice? Sometimes, the thing you're trying to predict (your "target variable") is all skewed and weird, making it tough for traditional regression models to work their magic. That's where this project comes in! We're exploring how to transform those tricky target variables to make them more "normal" and get better predictions.

#### **Our Data Transformation Journey 🗺️**

1.  **The Problem with Skewness:** We start by looking at a dataset where the target variable is not normally distributed. This is a common issue in real-world data, and it can throw off our regression models.

2.  **Transform and Conquer! 🧙‍♀️:** The core of this project is about applying transformations to the target variable. We'll explore different techniques to make the data more symmetrical and bell-shaped (aka normally distributed). This helps our models learn more effectively.

3.  **Back to Reality (Inverse Transform):** Once we've made our predictions on the transformed data, we need to convert them back to the original scale so they make sense in the real world. We'll show you how to apply inverse transformations to get your predictions back to their original units.

#### **Tech We Used 🛠️**

*   Python
*   NumPy & Pandas
*   Matplotlib (for visualizing those transformations!)
*   Jupyter Notebook

#### **Want to Tame Your Skewed Data? 🚀**

1.  **Clone the repo:**
    ```bash
    git clone https://github.com/jackren0000/Supervised-Machine-Learning-Regression.git
    ```
2.  **Install the libraries:**
    ```bash
    pip install pandas numpy matplotlib jupyter
    ```
3.  **Run the notebook:**
    ```bash
    jupyter notebook 02a-lab-transforming-target.ipynb
    ```