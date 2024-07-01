
# Using Machine Learning to Reduce Food Wastage and Fight Hunger

With so many conflicts and wars going on around the world, the worst thing that can happen to humanity is when people die of hunger, starvation, and famine. The Project aims to use machine learning techniques such as regression to study the patterns of surplus food production in the U.S., build a prediction model to estimate food wastage, and explore various ways to reduce it, thus fighting hunger and starvation. All the steps in the Project, such as EDA, Data extraction, Preparation, and Feature engineering, were done in R. Finally, Machine learning models were built using Regression algorithms such as Linear Regression and Regularized methods such as Ride, Lasso, and Elastic Net to predict the target variable – the number of meals wasted.




## Technologies Used

R libraries such as dplyr, tidyverse, and shiny were used for data manipulation. Recipe, vtreat, Caret, and factoextra were utilized for building regression models, while GGplot, plots, and maps were used for building visualizations.
## Prerequisites

The project was written in R and the code is available in the Rmd file format. You may need to install a tool that can process the .Rmd files preferrably RStudio. Rstudio can be installed on your machine using the link: https://posit.co/download/rstudio-desktop/.

After installation, you can run the file by selecting the File --> Open File option to locate the file on your local.

Also you may have to install all the required libraries before executing the code. Refer to the Deployment section to install the required packages.

Then you will have to download the source files and save them to the same location where the code is hosted. The files are available in the links: 

https://refed-roadmap.s3-us-west-2.amazonaws.com/csv/public_downloads/food_waste_monitor/ReFED_US_Food_Surplus_Summary.csv

https://www.census.gov/data/tables/time-series/demo/popest/2020s-state-total.html

https://www.census.gov/data/tables/time-series/demo/income-poverty/historical-poverty-people.html

https://datasets.omdena.com/dataset/2007-2022-homeless-populations-by-state-(usa)

The file names are:

- US_State_Food_Surplus_Detail.csv

- US_State_Food_Surplus_Summary.csv

- US_Population.xlsx

- US_Poverty_Rates.xlsx

- Homeless_Populations_by_State.xlsx


## Installation

Install the Required libraries using the below commands in R-studio

install.packages('readxl')

install.packages('dplyr')

install.packages('lubridate')

install.packages('readr')

install.packages('ggplot2')

install.packages('ggthemes')

install.packages('tidyr')

install.packages('DT')

install.packages('scales')

install.packages('stringr')

install.packages('knitr')

install.packages('FactoMineR')

install.packages('ggpubr')

install.packages('kableExtra')

install.packages('magrittr')

install.packages('ggfortify')

install.packages('reshape2')

install.packages('treemap')

install.packages('leaflet')

install.packages('plotly')

install.packages('gt')

install.packages('forcats')

install.packages('caret')

install.packages('fastDummies')

install.packages('tidyverse')

install.packages('purrr')

install.packages('vtreat')

install.packages('broom')

install.packages('tidymodels')

install.packages('tidyverse ')

install.packages('reshape2')

install.packages('plyr')

install.packages('scales')

install.packages('corrplot')

install.packages('ggthemes ')

install.packages('ggalt')

install.packages('maps')

install.packages('ggdendro ')

install.packages('crosstalk')

install.packages('zoo')

install.packages('glmnet')

install.packages('dplyr')

install.packages('psych')

install.packages('ggcorrplot')

install.packages('factoextra')

install.packages('recipes')

## FAQ

#### What does the Model Predict?

A Machine Learning Model was built to predict the amount food wasted based on inputs such as US State name, sector, subsector. The model returns the number of meals wasted. 

#### What type of Machine Learning algorithms were used?

As the Target Variable(Meals Wasted) is a continous Numeric quantity, the model was trained using Linear Regression algorithms and Regularized algorithms such as Ride, Lasso and Elastic Net.

