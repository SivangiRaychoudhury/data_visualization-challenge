# data_visualization-challenge
 
A new pharmaceutical company, Pymaceuticals Inc., began screening for the potential treatments for squamous cell carcinoma(a commonly occuring skin cancer). In this study, 249 mice indentified with SSC tumor growth were treated with a variety of drug regimens, over a time period of 45 days. Their development of tumor was observed and measured. The purpose of this study was to compare the performance of the Drug of Interest, "Capomulin" with other drug regimens. 

Following are the tables and figures generated from the provided datasets, followed by the analysis.

STEP 1: Prepare the data

Two datasets were provided, which were merged and cleaned first. Before cleaning the number of mice was 249. After cleaning it came to 248. 

STEP 2: Generate summary statistics

Two summary statistics tables were generated. The first one was by using the groupby method to generate the mean, median, variance, standard deviation and SEM of the tumor volume for each drug regimen. 

The second table generated the same summary statistics by using the aggregation method. 

STEP 3: Create Bar charts and Pie charts

Bar charts were created by using both Pandas' DataFrame.plot() method. as well as using Matplotlib's pyplot method. Bar charts showed the total number of timepoints for all mice tested for each drug regimen.


Pie charts were created by using both Pandas' DataFrame.plot() method. as well as using Matplotlib's pyplot method.Pie charts showed the distribution of female vs male mice. 

STEP 4: Calculate the quartiles, find outliers, and create box plot

The final tumor volume of each mice was calculated for four drug regimens : Capomulin, Ramicane, Infubinol and Ceftamin. Then the quartiles, IQR were calculated to determine any possible outliers across all the four treatment regimens.

Box plot for the Final tumor volume of each mouse across four regimens.

STEP 5: Create a Line plot and a Scatter plot

A single mouse with ID l509, that was treated with Capomulin was taken and a line plot was generated with tumor volume vs timepoint.

A scatter plot was generated of mouse weight vs average observed tumor volume for the entire Capomulin treatment regimen. 

STEP 6: Calculate the Coorelation and Regression

The coorelation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen were calculated. A plot with linear regression model on top of the scatter plot was presented. 

STEP 7: Final analysis

Final analysis was submitted. 