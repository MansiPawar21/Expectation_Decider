# Expectation Decider – Mathematics & Advanced Statistics

## Project Overview

The **Expectation Decider** project uses probability and statistical techniques to analyze student performance and estimate the likelihood of passing a competitive mathematics examination.

This project is based on a dataset of **200 students**, containing study hours, attendance percentage, group discussion participation, previous test scores, and final examination results.

The analysis is performed using Python in Jupyter Notebook as part of the PR1 Mathematics and Advanced Statistics project.

## Objectives

- Understand probability and its key terminology.
- Calculate empirical and theoretical probabilities.
- Construct a probability distribution for the number of students passing out of three randomly selected students.
- Calculate the mean and variance of a random variable.
- Visualize student conditions using a Venn diagram.
- Create a contingency table and calculate joint, marginal, and conditional probabilities.
- Analyze the relationship between group discussion participation and examination results.
- Apply Bayes' theorem to calculate the probability of passing given high attendance.
- Summarize the factors associated with student performance.

## Dataset Description

The dataset contains 200 student records with the following columns:

| Column | Description |
|---|---|
| `study_hours` | Hours studied per week |
| `attendance` | Lecture attendance percentage |
| `group_discussion` | Participation in group discussions (Yes/No) |
| `previous_test_score` | Previous test marks out of 100 |
| `final_exam_pass` | Final examination result (Pass/Fail) |

The dataset is generated using Python with a fixed random seed for reproducibility.

## Technologies Used

- **Python** – Programming and statistical calculations
- **Pandas** – Dataset creation and data analysis
- **NumPy** – Numerical calculations and random data generation
- **Matplotlib** – Charts and visualizations
- **SciPy** – Probability distribution calculations
- **Jupyter Notebook** – Interactive analysis environment

## Project Tasks and Analysis

### 1. Understanding Probability
Explains probability and calculates the probabilities of passing, studying more than 10 hours per week, having attendance above 80%, and participating in group discussions.

### 2. Types of Probability
Calculates empirical probability using the generated dataset and demonstrates theoretical probability using an equal-likelihood assumption.

### 3. Random Variable and Probability Distribution
Defines a random variable representing the number of students passing out of three selected students. Constructs the probability distribution and calculates its mean and variance.

### 4. Venn Diagram
Visualizes students who study more than 10 hours per week, students with attendance above 80%, and students satisfying both conditions.

### 5. Contingency Table
Analyzes group discussion participation against final examination results and calculates joint, marginal, and conditional probabilities.

### 6. Understanding Relationships
Uses conditional and marginal probabilities to assess the relationship between group discussion participation and passing the examination.

### 7. Bayes' Theorem
Uses the historical probabilities provided in the project instructions to calculate the probability that a student passed, given that the student had high attendance.

## How to Run the Project

1. Download or clone this repository.
2. Install Python and Jupyter Notebook.
3. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib scipy jupyter
   ```

4. Open `Pr1 Expectation Decider.ipynb` in Jupyter Notebook.
5. Run all cells from top to bottom.
6. Review the generated dataset, probability calculations, tables, and visualizations.

## Repository Structure

```text
Expectation-Decider/
│
├── Pr1 Expectation Decider.ipynb
├── expectation_decider_dataset.csv
├── PR1_Theory.pdf
└── README.md
```

## Conclusion

The Expectation Decider project demonstrates how probability and statistical methods can be applied to educational data. It explores student study habits, attendance, group discussion participation, and previous test performance in relation to final examination results.

The project provides practical experience in data generation, probability calculations, statistical distributions, visualization, contingency tables, and Bayes' theorem.

**Note:** The dataset is synthetically generated for educational purposes. The results illustrate probability concepts and should not be treated as validated predictions of real students' examination outcomes.
 
# Mathematics & Advanced Statistics – Project-"Expectation Decider"
