# Commuter data survey analysis

### Description 

The "commuter final" folder consists of 5 different files. the 5 files are:

* commuter.csv : the original file given by Jeremey King, which consists of the survey of faculty/staff regarding their residency. File does not have names of the faculty/staff for privacy purposes

* Com_study.csv : A tidy/normalized version of the commuter.csv file that will help us import the commuter data into R for further analysis. 

* commuter.rmd : the R-Markdown file that consists of all the analysis done to obtain the longitude and latitude values of each residence. The file also contains a visual map that shows the different residences as points on a map relative to Granville, Ohio.

* commuter.html : This file contains the same things as the commuter.rmd file, but is easier to access since no pre-requisite software required to open it, as it opens in the web browser. This will help if one wants to show the analysis to someone not familiar with the R software.

* commuter_final.csv : The final csv that containes the manipulated dataset using R. It contains longitude and latitude value of each residence that helps us calculate the distance travelled by each resident to reach campus. The excel file also containes the total distance travelled per day (per_day), total distance travelled per year (per_year), and finally the total emissions per year due to staff/faculty commute (Total_emission). 

### Prerequisites

The programs that I used to work through this project is:

[R](https://cran.r-project.org/mirrors.html) in [Rstudio](https://www.rstudio.com/products/rstudio/download/) - visualizing, cleaning, and analysis of data

Microsoft Excel, csv format


### Installing

In order to install Rstudio you will first need to install R. You can install R  and you can use any of the versions to install it onto your computer. After you install R you should install Rstudio which is an inferface to code in R (we have installed the free version).


## Authors
* Carbon-Consulting



