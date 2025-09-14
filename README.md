# **Marketing Mix Model for Revenue Prediction**

### ***Project by: Manas Kumar***
### ***Email: themanaskumar1@gmail.com***

### **Date: September 14, 2025**

This repository contains the code and documentation for a Marketing Mix Model (MMM) built to explain weekly revenue as a function of marketing spend and other business levers. The final model is a Two-Stage Gradient Boosting Machine that explicitly handles the causal assumption of social media spend influencing Google search intent.

## **What are all the files:**
**1. Assessment 2- MMM eekly.csv:** This file contains the dataset provided for this specific assessment

**2. LifeSight_Assessment_2_mmm.ipynb:** This is the google colab notebook where I did all the work i.e. data preparation, feature engineering, model trainin and evaluation etc.

Google Colab Link: [MMM Notebook - Google Colab](https://colab.research.google.com/drive/1rjbpruKBo2-_9tcSd3w41WEwu2yr1lFz?usp=sharing)

**3. LifeSight_Assessment2_Report.pdf:** This file contains a detailed report on the project that I made during this assessment.

**4. mmm_gbt_model.pkl:** This is the actual ML model that was created for the fulfilment of this assessment.

**5. requirements.txt:** This contains the python dependencies and their versions used for various steps in the model training and evaluation.

## **Environment Setup & Reproducibility**

To ensure the analysis can be reproduced, please follow these steps to set up the Python environment.

### **Prerequisites**

* Python 3.9+

### **Setup Instructions**

1. Clone or Download the Repository:  
   Get a local copy of this project's files.  
2. Create a Virtual Environment:  
   It is highly recommended to use a virtual environment to avoid conflicts with other projects. Open your terminal or command prompt, navigate to the project folder, and run:  
   python \-m venv mmm\_env

3. **Activate the Virtual Environment:**  
   * On macOS/Linux:  
    `source mmm\_env/bin/activate`

   * On Windows:  
    `.\\mmm\_env\\Scripts\\activate`

4. Install Required Libraries:  
   All necessary Python libraries are listed in the requirements.txt file. Install them with a single command:  
   `pip install \-r requirements.txt`

### **How to Run the Analysis**

Once the environment is set up, you can reproduce the results:

1. Launch Jupyter Notebook or JupyterLab:  
   jupyter notebook  

> Note: Make sure to keep the dataset csv file int the same directory as the notebook.