# Applied Statistics 
## Tasks and Project  

### **Overview**   
This repository contains a series of tasks and a project related to applied statistics using Python.   
The tasks cover key concepts such as permutations and combinations, the normal distribution, t-tests, and ANOVA. All tasks are completed in a Jupyter notebook (tasks.ipynb) with code and explanations in Markdown cells.  
The project completed in a Jupyter notebook (project.ipynb). It focuses on statistical analysis using the PlantGrowth dataset and involves t-tests and ANOVA.

### **Table of Contents:**  

Jupyter notebook [(tasks.ipynb)](https://github.com/OlgaKnut/applied_statistics/blob/main/tasks.ipynb):  
>Task 1: Permutations and Combinations  
>Task 2: Numpy's Normal Distribution  
>Task 3: t-Test Calculation  
>Task 4: ANOVA

Jupyter notebook [(project.ipynb)](https://github.com/OlgaKnut/applied_statistics/blob/main/project.ipynb)  
>Project: PlantGrowth Dataset Analysis

### **Tasks description**  
#### Task 1: Permutations and Combinations
![Lady Tasting Tea ](c:\Users\knuto\OneDrive\Desktop\fisher-considers-how-to-test-the-claim-l.jpg)  

In this task, we explore the Lady Tasting Tea experiment altered to involve twelve cups of tea: six with milk first and six with tea first. The task involves calculating probabilities related to guessing the correct cups:

Part 1: Calculate the probability that a person guessing randomly selects the six cups with milk first.
Part 2: Calculate the probability of selecting at most one incorrect cup (i.e., one error allowed).
Part 3: Discuss whether two errors would be acceptable.
The probability is computed using Python, and explanations for the calculations and logic are provided.

#### Task 2: Numpy's Normal Distribution  
![alt text](image.jpg)  

In this task, we assess whether numpy.random.normal() generates values that follow a normal distribution:

Step 1: Generate a sample of 100,000 values using numpy.random.normal() with mean = 10.0 and standard deviation = 3.0.
Step 2: Use the scipy.stats.shapiro() function to perform a normality test on the sample.
Step 3: Plot a histogram of the generated values and overlay the normal distribution probability density function (PDF) for comparison.
The results of the Shapiro-Wilk test and the visual comparison are discussed in Markdown cells.

#### Task 3: t-Test Calculation  
![alt text](image.jpg)  

This task involves calculating the t-statistic for a dataset of heart rates before and after a two-week exercise program:

Dataset: Resting heart rates of 10 patients before and after exercise.
Step 1: Calculate the t-statistic for the difference in heart rates before and after the exercise program using Python.
Step 2: Compare the computed t-statistic to the value provided by scipy.stats.ttest_rel() and explain the steps involved.
The assumptions behind the t-test are also discussed, including paired samples and normality.

#### Task 4: ANOVA  
![alt text](image.jpg)  

In this task, we estimate the probability of committing a Type II error using one-way ANOVA in a simulation:

Step 1: Generate three samples with 100 values each using numpy.random.normal(). Set different means (4.9, 5.0, and 5.1) and a standard deviation of 0.1.
Step 2: Perform one-way ANOVA using scipy.stats.f_oneway() for each iteration of a loop running 10,000 times.
Step 3: Track how many times a Type II error occurs (failing to reject the null hypothesis when it is false).
The results are analyzed and summarized, with an explanation of Type I vs Type II errors.

### **Project descript**
#### PlantGrowth Dataset Analysis  
![alt text](image.jpg)  

For this project, the PlantGrowth dataset is analyzed. This dataset contains the weight of plants across three treatment groups: control, trt1, and trt2. The task involves performing t-tests and ANOVA to analyze the data and make conclusions:

Step 1: Download and save the PlantGrowth dataset in the repository.
Step 2: Describe the dataset, including a summary of its contents.
Step 3: Explain what a t-test is, how it works, and its assumptions.
Step 4: Perform a t-test to check if there's a significant difference between the two treatment groups (trt1 vs trt2).
Step 5: Perform an ANOVA to determine if there are significant differences between the three treatment groups (ctrl, trt1, trt2).
Step 6: Explain why ANOVA is more appropriate than multiple t-tests when comparing more than two groups.
The analysis is done with clear explanations and visualizations where appropriate.

Requirements
The tasks and project require the following Python libraries:

numpy
scipy
matplotlib (for plotting)
pandas (for data handling in the project)
You can install the required libraries using pip:

bash
Copy code
pip install numpy scipy matplotlib pandas
How to Run the Notebooks
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/OlgaKnut/applied_statistics.git
Navigate to the repository folder:
bash
Copy code
cd applied_statistics
Open the Jupyter notebook for each task:
bash
Copy code
jupyter notebook tasks.ipynb
For the project, open project.ipynb and follow the steps provided in the notebook.
Git Workflow


