# nhanes_inferential_2023
NHANES 2021-2023 Inferential Analytics Assignment


## Instructions

1. **Create Your GitHub Repository**
   - Create a new GitHub repository titled `nhanes_inferential_2023`.
   - Include a `README.md` file that briefly describes the project and the analyses you are performing for each of the questions.

2. **Complete the Analysis in Google Colab**
   - Use Google Colab to conduct your analysis. Your notebook should be well-documented with explanations of each step just as like we have done in the class notebooks.

3. **Questions for Analysis**

   Use the questions below to guide your analysis. Remember to transform or recode variables where needed as specified, and determine the appropriate statistical tests that should be performed based on the question and variables.

   - **Question 1**: "Is there an association between marital status (married or not married) and education level (bachelor’s degree or higher vs. less than a bachelor’s degree)?"  
     - Variables: `DMDMARTZ` (marital status) and `DMDEDUC2` (education level). Recode as specified.

   - **Question 2**: "Is there a difference in the mean sedentary behavior time between those who are married and those who are not married?"  
     - Variables: `DMDMARTZ` (marital status, recoded) and `PAD680` (sedentary behavior time, cleaned).

   - **Question 3**: "How do age and marital status affect systolic blood pressure?"  
     - Variables: `RIDAGEYR` (age), `DMDMARTZ` (marital status, recoded), and `BPXOSY3` (systolic blood pressure).

   - **Question 4**: "Is there a correlation between self-reported weight and minutes of sedentary behavior?"  
     - Variables: `WHD020` (self-reported weight, cleaned) and `PAD680` (sedentary behavior time, cleaned).

   - **Question 5 (Creative Analysis)**: Develop your own unique question using at least one of the variables listed above. Ensure that your question can be answered using one of the following tests: chi-square, t-test, ANOVA, or correlation. Clearly state your question, explain why you chose the test, and document your findings.

4. **Deliverables**

   - A completed Google Colab notebook (`.ipynb` file) with:
     - Data loading and preparation steps
     - Analysis and any transformations
     - Visualizations of descriptives/results (if relevant)
     - Brief summaries of your findings for each question
   - Submit the link to your GitHub repository titled `nhanes_inferential_2023`.
