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

![pandabar](https://github.com/SivangiRaychoudhury/data_visualization-challenge/assets/133824318/0da9843c-6669-4271-b31b-89af0d16e218)
![pybar](https://github.com/SivangiRaychoudhury/data_visualization-challenge/assets/133824318/2854983e-6b43-475d-acf3-29363297504b)

Pie charts were created by using both Pandas' DataFrame.plot() method. as well as using Matplotlib's pyplot method.Pie charts showed the distribution of female vs male mice. 

![pandapie](https://github.com/SivangiRaychoudhury/data_visualization-challenge/assets/133824318/518ff83b-44f0-4cbf-ac3d-0bd539bb7414)
![pypie](https://github.com/SivangiRaychoudhury/data_visualization-challenge/assets/133824318/7c53fd18-978d-4e69-b9af-ff8ec637878f)


STEP 4: Calculate the quartiles, find outliers, and create box plot

The final tumor volume of each mice was calculated for four drug regimens : Capomulin, Ramicane, Infubinol and Ceftamin. Then the quartiles, IQR were calculated to determine any possible outliers across all the four treatment regimens.

Box plot for the Final tumor volume of each mouse across four regimens.
![box](https://github.com/SivangiRaychoudhury/data_visualization-challenge/assets/133824318/37ca04f2-a8ae-462b-86a9-0fed415e75bd)


STEP 5: Create a Line plot and a Scatter plot

A single mouse with ID l509, that was treated with Capomulin was taken and a line plot was generated with tumor volume vs timepoint.
![volVsTime](https://github.com/SivangiRaychoudhury/data_visualization-challenge/assets/133824318/9434548f-aff5-42e7-9db7-e53e014d0443)

A scatter plot was generated of mouse weight vs average observed tumor volume for the entire Capomulin treatment regimen. 
![wtVsVol](https://github.com/SivangiRaychoudhury/data_visualization-challenge/assets/133824318/fc7e2d62-ee05-403b-b686-bce13ce13e65)


STEP 6: Calculate the Coorelation and Regression

The coorelation coefficient and linear regression model between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen were calculated. A plot with linear regression model on top of the scatter plot was presented. 
![correg](https://github.com/SivangiRaychoudhury/data_visualization-challenge/assets/133824318/6d1608a1-7544-4f54-8a6b-763a1fc22d8f)


STEP 7: Final analysis

Final analysis was submitted. 
