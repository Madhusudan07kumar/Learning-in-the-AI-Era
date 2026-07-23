# Learning-in-the-AI-Era
A data-driven exploration of AI's impact on education, student learning, and academic growth. Using EDA and visualizations to reveal insights into the future of learning.

**Introduction to the Project**
Artificial Intelligence is becoming one of the crucial components of modern-day education. The usage of AI tools by the students is seen in doing homework assignments, researches, learning process, preparing for exams and increasing their productivity.

This project involves the analysis of the effect of using AI tools on the academic performance, learning habits, anxiety, dependence, skills retention and burnout risk of the students through Exploratory Data Analysis.

**Objectives of the Project**
The main objective of this project is to derive insights from the raw data available for the students to increase their performance.
Through the analysis of crucial data such as attendance records, study habits, and performance habits, I will be able to get insights into what affects the academic performance of the students. The main goal is to develop an interactive dashboard which can assist teachers in making informed decisions.

Importing Libraries

This project begins by importing the essential Python libraries required for data manipulation, visualization, and environment            configuration. These libraries provide the foundation for performing Exploratory Data Analysis (EDA), cleaning the dataset, and           creating insightful visualizations.

**Libraries Used**

Library	Purpose
Pandas (pandas)	           Used for loading, cleaning, transforming, and analyzing structured data.

NumPy (numpy)	             Provides support for numerical computations and mathematical operations.

Matplotlib (matplotlib)	   Used to create static charts and visualizations.

Seaborn (seaborn)	         Builds on Matplotlib to produce attractive and informative statistical visualizations.

Warnings (warnings)	       Suppresses unnecessary warning messages for a cleaner notebook output.

                                    # Data Manipulation
                                    import pandas as pd
                                    import numpy as np
                                    
                                    # Data Visualization
                                    import matplotlib.pyplot as plt
                                    import seaborn as sns
                                    
                                    # Ignore Warnings
                                    import warnings
                                    warnings.filterwarnings("ignore")
                                    
                                    # Display Settings
                                    pd.set_option("display.max_columns", None)
                                    pd.set_option("display.max_rows", 100)
                                    
To read a CSV file with count of top 5 head and tail
                                 
                                    df = pd.read_csv("Student Data set.csv")
                                      
                                    df.head()
                                    df.tail()

<img width="949" height="473" alt="image" src="https://github.com/user-attachments/assets/2b7872e2-c889-4faf-be63-f1cb1bd3dccd" />
