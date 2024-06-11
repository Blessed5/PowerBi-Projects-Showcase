# PowerBi-Projects-Showcase
Includes various PowerBi Projects

# Diversity & Inclusion Analysis 

## Link to Dashboard
<iframe title="HR Report" width="1140" height="541.25" src="https://app.powerbi.com/reportEmbed?reportId=35bb435c-d3df-4795-ac9d-2bff7ab75ac8&autoAuth=true&ctid=e632f263-3f46-4111-aa5c-d54126f95105" frameborder="0" allowFullScreen="true"></iframe>

## Problem Statement

This dashboard helps the HR Consulting understand their workforce better. It helps them to see how their workforce meets their KPIs in terms of Gender and Age distribution accress the various roles. Through different KPIs, they can identify areas of improvement,and serious shortfall that needs urgent attention. The project highlights an analysis on the following: distribution of roles by age, and gender, average hires and average promotions, it also provide a view into performance rating and leavers during the Financial Year 2020 and 2021.  

The analysis shows that 88% of Executive Hires are Male, against the 12% of the opposite gender, thus proving that they must improve in their recruitment strategy. 



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average rating, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Performance Rating") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 

![Image 1](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/d499ee84-cce3-448f-9d27-eb42c9de3ce9)

- Step 8 : Visual filters (Slicers) were added for four fields named "Department", "Job Level", "Age Group" & "Region".

![Image 4](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/fbaa833b-0acf-4828-8ef8-af3b1517746d)

- Step 9 : Varios measures were created to obtain "Total count of Employees", "Turnover" and "Averages" for Male and Female. 

![Image 2](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/9d229e59-996f-4798-ba5a-a22a6824d5a5)



           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.

- Step 10 : A bar charts, pie charts and card visuals were added to the canvas to visualise the results seggregated according the gender. 
![Image 3](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/f1a51d3a-004c-4cd9-b386-32f89039b44a)

![Image 5](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/1148b65d-6028-4d82-9efd-1030ec4e0a3c)

![Image 6](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/7a59064e-60f3-4968-8bd3-ea628cd843cd)

![Image 7](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/05d83063-067e-4b00-9bc0-15d81871d75e)
 
 - Step 11 : The report was then published to Power BI Service.
 
 ![Publication](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/aef1603f-f62d-435c-8b35-f04d28274b51)


# Snapshot of Report  Page 1 of 2 

![Page 1](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/7d2a54d6-ac91-484f-93f4-198287ab118e)
 
 # Report Report Page 2 of 2

 
![Page 2](https://github.com/Blessed5/PowerBi-Projects-Showcase/assets/75251479/a3af2227-0088-462a-96f1-79fff23fc323)

# Insights

A two pagse report was created on Power BI Desktop & it was then published to Power BI Service.



