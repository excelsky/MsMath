Final Project
==============================

| **Name**  | Kicho Yu  |
|----------:|:-------------|
| **Email** | kyu12@dons.usfca.edu |

## Instruction ##
The following packages must be installed prior to running this code:
- `ggplot2`
- `plyr` 
- `RColorBrewer` 
- `reshape2` 
- `scales` 

To run this code, please enter the following commands in R:

```
library(shiny)
runGitHub("msan622", "excelsky", subdir = "final-project")
```
This will start the `shiny` app. See below for details on how to interact with the visualization.  


## Discussion ##
### Data ###
The dataset is called `adult.data` from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Adult). It is also called '1994 Census database.' It shows demographic infomation of survey participants from all around the world and eventually wants to see who earns 50K USD per year or not. Examples of demographic infomation are age, years of education, highest degree in education, occupation, race, relationship, sex, and so forth. I chose this dataset, because it is easy to obtain and is big enough to slice and dice. It has 32546 rows and is about 3.75 MB. Also, it has rich demographic information, so I could use many techniques and interactivities that we learned in class. 
