# README

## Project Title: A Multivariate Study on the Contributing Factors of Anxiety

### Description:
This project investigates how various life factors influence anxiety among elderly individuals. The study utilizes data from the ELSA Wave 7 dataset, applying statistical techniques like Chi-square tests and binary logistic regression to identify significant factors.

### Files Included:
1. **Multivariate Study on Anxiety - ELSA Wave 7.pdf**: A detailed report explaining the study's hypotheses, methodology, and results.
2. **Output1.spv**: Contains all the statistical tests performed for the study, including:
   - Chi-square tests to determine associations between independent variables and anxiety.
     ![image](https://github.com/user-attachments/assets/e28b8376-e977-406f-9d08-1a134021d234)

   - Binary logistic regression outputs to evaluate the strength of significant factors.
     ![image](https://github.com/user-attachments/assets/9a01c8d6-b9a6-498e-af6d-1263e50e81d3)

   - Additional summary statistics and results generated during the analysis.

### Hypotheses Tested:
1. **H0**: Age and sex are significantly associated with anxiety.
2. **H1**: Isolation is significantly associated with anxiety.
3. **H2**: Loneliness is significantly associated with anxiety.
4. **H3**: Mood swings are significantly associated with anxiety.
5. **H4**: Life satisfaction is significantly associated with anxiety.
6. **H5**: Socialisation is significantly associated with anxiety.

### Key Findings:
1. **Non-significant factors**:
   - Age (p = 0.757)
   - Sex (p = 0.262)
   - Loneliness (p = 0.270)
2. **Significant factors**:
   - Mood swings (p < 0.001): Strong association; individuals with mood swings are more likely to experience anxiety.
   - Social participation (p = 0.035): Lack of participation increases anxiety risk by 40%.
   - Isolation (p = 0.014): Frequent isolation correlates with higher anxiety levels.
   - Life satisfaction (p = 0.017): Lower satisfaction levels show trends of association with anxiety.

### Dataset:
- **Source**: ELSA Wave 7 (2002-2015), a longitudinal study of aging in England.
- **Sample Size**: 1,011 individuals who underwent psychiatric evaluation.
- **Variables**:
  - Dependent: Anxiety
  - Independent: Age, sex, mood swings, isolation, loneliness, life satisfaction, social participation.

### Statistical Analysis:
1. **Chi-Square Tests**: Identify significant associations between categorical variables and anxiety.
2. **Binary Logistic Regression**: Predict the likelihood of anxiety based on significant factors, with a 95% confidence interval.

### Practical Implications:
- Addressing mood swings and promoting social participation can significantly reduce anxiety.
- Strategies to combat social isolation and enhance life satisfaction are vital for elderly mental health.

### How to Use:
The SPV file, **Output1.spv**, contains detailed outputs of all tests performed and can be reviewed using SPSS software for further insights or validation.
