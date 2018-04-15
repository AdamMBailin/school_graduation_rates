# school_graduation_rates
## Introduction:
This was the third project for the course. The first and second projects can be found [here](https://github.com/AdamMBailin/titanic-project) and [here](https://github.com/AdamMBailin/ames-housing-project). This project required a lot of data combining and munging.
The school graduation rate data and the census data came from the AT&T school graduation rate challenge. I also pulled 4 sets of school district finance data from [census.gov](https://factfinder.census.gov/faces/nav/jsf/pages/download_center.xhtml).

## Data:
There were several datasets for this project. The first dataset was the class size and graduation rate of over 11,000 school districts. This set also included the class size and graduation rate of racial and economic groups of students. The graduation rate for each group of students was dropped. The second dataset was census data for over 74,000 census tracts and had 550 features. The third dataset consisted of 105,000 observations. Each observation is the overlap of a census tract with school districts and has the overlap percentage. The remaining datasets were school district revenue, expenditures, income distribution and per pupil spending for 13,000 school districts. I calculated the demographic makeup for classes by dividing on the number of students that were part of a particular group by the class size. I also approximated the census data for each school district by multiplying the total census tract data by the tract overlap percentage and summing the resulting data for all tracts in the school district. The resulting cleaned dataset had 120 columns of finance, census data, class size, and graduation rates for over 9000 school districts.

## Objectives:
To create a model that will predict graduation rates and to make inferences based on the model.
