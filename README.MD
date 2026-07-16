# Marketing A/B Testing Analysis

## Objective

This project analyzes whether showing advertisements increases customer conversion rate compared with Public Service Announcement (PSA).

## Dataset

The dataset contains user-level information:

- User ID
- Test group (Ad / PSA)
- Conversion status
- Number of ads shown
- Advertisement timing

## Statistical Question

Does the advertisement group have a higher conversion rate than PSA?

## Hypothesis

Null Hypothesis:

H0: p_ad = p_psa


Alternative Hypothesis:

H1: p_ad > p_psa


## Methods

- Exploratory Data Analysis
- Conversion Rate Analysis
- Two-Proportion Z Test
- Permutation Test
- P-value Analysis


## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook


## Conclusion

The analysis determines whether the observed difference in conversion rates is statistically significant or could have happened randomly.