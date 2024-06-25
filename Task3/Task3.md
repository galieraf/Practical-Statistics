# Semestral Project3: Analysis of Gross Domestic Product of European Countries

Gross Domestic Product (GDP) is one of the important indicators of economic prosperity. This project will focus on examining the GDP of European countries in a specific year. GDP data can be found in the Eurostat database in the table `nama_10_pc` here:

[Eurostat GDP Data](https://ec.europa.eu/eurostat/databrowser/view/nama_10_pc/default/table?lang=en)

There are several ways to calculate GDP; we will be interested in the calculation at market prices (na_item=="B1GQ") and expressed in euros per capita (unit=="CP_EUR_HAB").

## Task 1:
- Briefly present the distribution of GDP and its characteristics both numerically and graphically.
- Discuss which country-specific data might influence GDP.

## Task 2:
- For the examined countries, suitably select four data points available from Eurostat databases or other external sources. These can be demographic, geographic, or economic indicators. At least one variable should be numerical, and at least one categorical (e.g., whether the country has access to the sea, whether the Euro is used, whether it is a monarchy or a republic, etc.).
- These data points will serve as regressors, so choose them in such a way that they at least minimally determine the modeled variable. Verify the relationship to GDP.
- Present the important properties of the selected indicators both numerically and graphically.
- Examine the dependencies between the regressors using appropriate tests.

## Task 3:
- Using a linear regression model or its variants, examine the dependence of GDP on all regressors.
- Practically interpret the estimated values of the regression coefficients.
- Evaluate the quality of the model.
- Identify outliers and examine multicollinearity.
- Test the assumptions of the model - if they are not met, propose and test methods that compensate for or do without these assumptions.
- Using appropriate tools, try to find a final (sub-)model that explains the behavior of GDP well but does not include insignificant components. Practically interpret the obtained results.
