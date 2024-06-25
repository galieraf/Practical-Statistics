# Second Semester Project: Exploring the Dependence of a Specific Variable on Various Regressors

The aim of the second semester project is to explore the dependence of a specific variable on various regressors
from the assigned dataset.

The data sets can be found in R in the Sleuth2 library. Each set contains one explained variable and several other possible regressors.

## Task 1 (5 points)
Load the dataset and perform basic statistical investigations:

- Briefly describe the data and individual variables.
- Determine the most important statistical measures that best characterize the data.
- Represent the data appropriately using selected graphs.

## Task 2 (5 points)
Select one numerical variable as a regressor.

- Using a linear regression model or its variants (quadratic regression, etc.), examine the dependence of the explained variable on this regressor.
- Display the outputs graphically.
- Practically interpret the estimated values of the regression coefficients.
- Evaluate the quality of the model - does the chosen regressor explain the behavior of the explained variable well?

## Task 3 (5 points)
Select one categorical variable as a regressor.

- Using an analysis of variance (ANOVA) model, examine the dependence of the explained variable on this regressor.
- Practically interpret the value of the regression coefficients.
- Evaluate the quality of the model.

## Task 4 (5 points)
Consider a regression model that includes both regressors from the previous points, including their interaction.

- Estimate its parameters and interpret them.
- Examine the significance of individual components.
- Appropriately display the regression dependence graphically.

## Task 5 (5 points)
Consider a model with the previous two regressors and at least one additional regressor from the examined dataset.

- Examine which regressors are significant for the model and which are not.
- Using appropriate tools, try to find a suitable final model that explains the behavior of the examined variable well but does not include insignificant components.
- Explain your procedure and justify your choice.
- Practically interpret the resulting model.

## Task 6 (5 points)
For the final model, verify the assumptions of the methods you used using appropriate tests.