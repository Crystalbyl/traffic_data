### 同济大学 交通数据分析与应用课程 R语言部分作业要求

#### Assignment 01 
Read the tidyverse style guide and Chapter 5 of R for data science (click)
Load your own .csvfile into R, report the dimension of your data frame, then generate a scatter plot using the plot()function.
Hint: check slides 21 and 58
Write a loop to calculate the mean value of a random numeric vector of length 50
Prepare your solution in a Rscriptfile and report your outputs in a MS Word document.
Hint: Contain your R code in a .Rfile
Familiarize with the syntax of Markdown and R Markdown or (Quarto) (ch21 of r4ds or ch28 of r4ds 2ed)

#### Assignment 02 

##### 1. Using the iri dateset
Get a subset with STATE_CODE 6 and SHRP_ID starting with 050.
Obtain the summary statistics of IRI of each section: min, max, and mean
Sort the summarized data by the averaged IRI in a descending order (report results for one section only)
Generate a scatter plot for the averaged IRI against the time for a selected section, and then give your interpretation of the plot:
• HINT 1: mean IRI vs. date
• HINT 2: STATE_CODE and SHRP_ID together to form a primary key that uniquely identifies a section.
##### 2. Using the CRSS datasets in 2017
Get the intersection of the datasets accident and person
Tabulate the total number of observations in each injury severity (INJ_SEV)
• HINT: use summarise() and group_by()
Merge the accident dataset with the vehicle dataset, and report the dimension of your results and number of missing values in one
variable of the right dataset
• HINT: left_join()


#### Additional

Push your homework to a git repository (bonus problem for 5 points)
Provide a link to your repository as well as a screenshot of your repository
You can use an IDE or use the command line interface of git
Rstudio has a Git tab next to Connections and Tutorial

关于本课程的建议
本课程的内容 (数据处理的技术、数据应用的算法等)
编程语言与编程工具


#### Requirements
Contain your R scripts, analysis, and plots in a word document.
R Markdown files are welcome!!! (go to Help -> Markdown Quick References) or
• R Markdown: the Definitive Guide (click to linked page)
• Five bonus points will be given for R markdown solutions

**Due by 11/16/2023, Before class**
