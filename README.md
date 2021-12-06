# Modeling the effect of poverty level on violent crime rate using linear regression

Data was downloaded from the UCI Machine Learning Data Repository: https://archive.ics.uci.edu/ml/datasets/Communities+and+Crime

The scatter plot shows a positive correlation between poverty (percent population below poverty line, the input variable) and crime (violent crimes per capita, the output variable). This is in line with the common perception that poverty leads to high crime. 

The R squared value (0.31) shows that the relationship between the input and output is not strong. This show that the data may need transformation/pruning, a bigger dataset may be needed, or a better input variable needs to be selected. The intercept (0.08) is a low but positive value, this is in line with the expectation that even when there is no poverty, violent crimes still happen at a certain level.
