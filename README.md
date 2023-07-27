# Rainfall Comparison
Final Project for Data Analysis 2 with Code Kentucky

For the final project of Code Kentucky's Data Analysis Course, I utilized OpenMeteo's Historical Weather API to pull in data from the European Center for Medium-Range Weather Forecast's ERA5 for 6 weeks in 2022 and 2023. ERA5 is the fifth generation ECMWF reanalysis for the global climate and weather for the past 8 decades. The 6 weeks I chose were the same 6 weeks covered by my recently purchased ACU*RITE rain gauge. I wanted to compare what my personal rain gauge's calculations to those of ERA5.  

The easiest way to run this program is to select the blue "Open in Colab" button at the top of the Rainfall_Comparison.ipynb, especially if you would like to view the embedded Tableau dashboard which can also be found at: https://public.tableau.com/views/RainfallDataDashboard_16904141579260/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link.

**Required features included in my final project**
* Read in two datasets with an API
* Clean data and perform an SQL join
* Tableau dashboard
* Custom data dictionary included in this README

**Conclusions**
>For the six weeks measured, I found that my personal rain gauge typically measured more rainfall than what was recorded by ERA5. I also found that 50% of the weeks measured by my personal rain gauge were over 1 inch, which is the amount required to sustain a vegetable garden. 

**Definitions**
* df_hw22weekly - The final cleaned dataframe for the ERA5 data from 2022.
* rain_sum_22 - Daily and weekly rain totals for the ERA5 data from 2022.
* week_date - The date displayed by full weeks based on the start of the week.
* month_day - The weekly date displayed with out the year for easier joining.
* df_hw22weekly - The final cleaned dataframe for the Era5 data from 2023.
* rain_sum23a - Daily and weekly rain totals for the ERA5 data from 2023.
* month_day23a - The weekly date displayed by full weeks based on the start of the week for the ERA5 data from 2023.
* gauge_df23 - The final clean dataframe for my personal ACURITE rain gauge data.
* rain_sum23b - Weekly rain totals from my personal rain gauge.
* month_day23b - The weekly date displayed by full weeks based on the start of the week for my rain gauge.
