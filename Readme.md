# Prediction of Wages and Recruitement rates in Sweden

This repository is my work on predicting Wages and Recruitement rates in municiaplities and regions Sweden. The report is in **Report.pdf**

## Key insights
- A Linear Regression model predicts Wages well for Sweden
- Recruitement Rate data seems to be very distorted. No fitted model was accurate. 
- Stockholm has higher Recruitement rates than the rest of Sweden

<object data="plots/Wages_prediction_df_all.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="plots/Wages_prediction_df_all.pdf">
        <p>This browser does not support PDFs. The Wages Prediction plot can be seen here: <a href="plots/Wages_prediction_df_all.pdf">Download PDF</a>.</p>
    </embed>
</object>



# Description of the files

The repository contains the following Files:

## Top level
- **Report.pdf** - Contains the report of the work done.
- **Readme.md** - This file
- **Average Wage.csv** - The dataset used for the Wage prediction
- **Vacancies.csv** - The dataset used for the Recruitment rate prediction

## Code
- **arend.mplstyle** A style-sheet for creating plots that look good on papers
for `matplotlib.pyplot`
- **Wages_predictor.ipynb** A jupyter notebook for the Code for Wage prediction
- **Recruitment predictor.ipynb** A jupyter notebook containing the Recruitemtn rate pred

## Plots

- **compareQuarters.pdf** The Recruitment rate, split by quarter
- **Recruitement_Time_comparison.pdf** The Recruitment rate over the whole timeseries
- **TotalSwedenSalary.pdf** Salary development of *men, women and total* in the whole of Sweden
- **Wages_prediction_df_all.pdf** The historical data and predictions for future data
- **Wages_Regions.pdf** The historical wages data for all regions.
