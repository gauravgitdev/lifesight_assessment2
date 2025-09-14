# **Marketing Mix Model for Revenue Forecasting**

### **Project Author: Gaurav Kumar**

### **Contact: gauravkumar688504@gmail.com**

### **Date Updated: September 15, 2025**

This repository provides the code and documentation for a Marketing Mix Model (MMM) designed to predict weekly revenue based on marketing expenditures and other key business drivers. The final implementation uses a Two-Stage Gradient Boosting Machine to effectively model the causal relationship where social media spending influences Google search activity.

## **Repository Contents**

1. **Assessment 2- MMM weekly.csv**: The raw dataset used for this analysis.  
2. **LifeSight\_Assessment\_2\_mmm.ipynb**: A Google Colab notebook detailing the entire workflow, including data preparation, feature engineering, model training, and evaluation.  
   * **Direct Link:** [Notebook - Google Colab](https://colab.research.google.com/drive/1GbxyvUV3Ria3a0oTgxhX71idRyYl8yWF#scrollTo=kM7P5FrTBF9u)  
3. **Marketing\_Mix\_Model\_Report\_Revised.md**: A comprehensive report summarizing the project's methodology, findings, and strategic recommendations.  
4. **mmm\_gbt\_model.pkl**: The serialized machine learning model developed for this assessment.  
5. **requirements.txt**: A list of Python dependencies and their specific versions required to run the analysis.

## **Environment Setup for Reproducibility**

To ensure the analysis can be replicated, please follow these instructions to configure the necessary Python environment.

### **Prerequisites**

* Python 3.9 or higher

### **Setup Instructions**

1. Clone or Download the Repository:  
   Obtain a local copy of all project files.  
2. Create a Virtual Environment:  
   Using a virtual environment is strongly recommended to manage dependencies and avoid conflicts. Navigate to the project's root directory in your terminal and execute:  
   python \-m venv mmm\_env

3. **Activate the Virtual Environment:**  
   * **macOS/Linux:**  
     source mmm\_env/bin/activate

   * **Windows:**  
     .\\mmm\_env\\Scripts\\activate

4. Install Required Libraries:  
   All necessary Python packages are specified in the requirements.txt file. Install them using pip:  
   pip install \-r requirements.txt

### **How to Run the Analysis**

With the environment configured, you can reproduce the project's results.

1. Launch Jupyter:  
   Start Jupyter Notebook or JupyterLab from your terminal:  
   jupyter notebook  
   **Note:** Ensure that the dataset (.csv file) is located in the same directory as the Jupyter notebook for the code to run correctly.