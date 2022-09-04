# Multivariate Exploration
Multivariate Exploration entails visualiziation of three or more variables. However, it's not about exploration but choosing the right visualization for the variables and ensuring you have right colors, labels and legend is another thing. This documentation will look at encodings, choice of colors. faceting, plot matrices and feature engineering.

## Areas of Interest
The areas of interest will be on the following topics:
* **Non-Positional Encodings for Third Variables**

There are four major cases to consider when we want to plot three variables together:
> 1. Three numeric variables
> 2. two numeric variables and one categorical variable
> 3. one numeric variable and two categorical variables
> 4. three categorical variables

Three main non-positional encodings stand out:
> 1. color
> 2. shape
> 3. size


* **Color Palettes**

Depending on the type of data you have, you may want to change the type of color palette that you use to depict your data. There are three major classes of color palette to consider:
> 1. Qualitative
> 2. Sequential
> 3. Diverging

* **Faceting in Two Directions**

With faceting, you can actually use any plot type, allowing you to facet bivariate plots to create a multivariate visualization. The use of FacetGrid also allows for faceting a variable not just by columns, but also by rows.

* **Adaptations of Bivariate Plots**

Univariate plots can be transformed to bivariate plots by substituting count on a bar chart or histogram for the mean, median, or some other statistic of a second variable. This adaptation can also be done for bivariate plots like the heat map, clustered bar chart, and line plot, to allow them to depict multivariate relationships.

* **Plot Matrices**

In a plot matrix, a matrix of plots is generated. Each row and column represents a different variable, and a subplot against those variables is generated in each plot matrix cell. This contrasts with faceting, where rows and columns will subset the data, and the same variables are depicted in each subplot.

* **Feature Engineering**

Feature engineering is all about creating a new variable with a sum, difference, product, or ratio between those original variables that may lend a better insight into the research questions you seek to answer.
