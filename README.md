# matplotlib-challenge

## The Power of Plots

### Background: 
Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, specialises in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In a study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 


### Task:
As a senior data analyst at the company, I've been given access to the complete [data](https://github.com/catherinesloan/matplotlib-challenge/tree/main/data) from their most recent animal study and tasked to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.

### Output:
A [Python script](https://github.com/catherinesloan/matplotlib-challenge/blob/main/pymaceuticals_solution.ipynb) that first checks the data for any mouse ID with duplicate time points and removes any data associated with that mouse ID 
1. A **summary statistics table** consisting of the tumor volume for each drug regimen
2. A **bar plot** using both Pandas's DataFrame plot and Matplotlib's pyplot that shows the number of total mice for each treatment regimen throughout the course of the study
3. A **pie plot** using both Pandas's DataFrame plot and Matplotlib's pyplot that shows the distribution of female or male mice in the study
4. A calculation of the final tumor volume of each mouse across four of the most promising treatment regimens; Capomulin, Ramicane, Infubinol, and Ceftamin
5. A calculation of the quartiles and IQR, quantitatively determining if there are any potential outliers across all four treatment regimens
6. A **box and whisker plot** (generated with Matplotlib) of the final tumor volume for all four treatment regimens. Potential outliers highlighted in the plot by a change in their colour and style
7. A **line plot** of tumor volume vs. time point for mouse **x401** who was treated with Capomulin
8. A **scatter plot** of mouse weight versus average tumor volume for the Capomulin treatment regimen
9. A calculation of the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot
10. Three written observations made from the data

<img width="406" alt="Screen Shot 2021-05-29 at 5 11 35 pm" src="https://user-images.githubusercontent.com/73929301/120061543-1769a800-c0a1-11eb-81f5-2c3700624f95.png">

<img width="410" alt="Screen Shot 2021-05-29 at 5 11 49 pm" src="https://user-images.githubusercontent.com/73929301/120061545-1a649880-c0a1-11eb-947e-3cc4633c6c5c.png">

<img width="444" alt="Screen Shot 2021-05-29 at 5 11 58 pm" src="https://user-images.githubusercontent.com/73929301/120061546-1afd2f00-c0a1-11eb-8711-ca7e1800b927.png">




