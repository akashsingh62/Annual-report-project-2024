
#  Store Annual Report -Dashboard

### Dashboard Link : https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/70c02fd2-c0d2-4930-bc26-1e5eee3fce32


## Problem Statement

This dashboard helps the  understand their customers better. It helps the store manager know if their customers are satisfied with their services. Through different sales and orders, they get to know their improvement area, & thus they can improve their services by identifying these area. Thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these unwanted sales.

Since, number of women (almost 64 %) and number of mens (almost 36%) they are buying more products than teenagers, thus in all they must work on improving their product and services. 

### Steps followed 

- Step 1 : Load data into Excel Desktop, dataset is a csv file.
- Step 2 : Open excel query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : For calculating top 5 sales, null values were not taken into account as only less than 1% values are null in this column. 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various sales, thus in order to represent sales in each state, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Month", "Channel", "Category".
- Step 9 : Two card visuals were added to the canvas, one representing order vs sales in month & other representing how much sales occur in month in each state.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 10 : A bar chart was also added to the report design area representing the number of Order:Age VS Gender. While creating this visual, field named "Gender" was also added to the Legends bucket, thus number of sales are also seggregated according the gender. 
- Step 11 : Ratings Visual was used to represent different Brand Sales mentioned below : 

  (a) AJIO

  (b) AMAZON
  
  (c) FLIPKART
  
  (d)MYNTRA
  
  (e) NALI
  
  (f) Others

   (g)Category : Blouse,Button,Ethnic dress,Kurta,Sarees set,etc.....
  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating sales for each of the parameters mentioned above.

- Step 14 : Calculated column was created in which, customers were grouped into various age groups
             
- Step 15 : New measure was created to find total count of customers.

A card visual was used to represent count of order ID.

![Screenshot 2024-01-29 184704](https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/c225d80b-879b-49b0-80cd-76a8322daaad)

Step 16 : This image shows the top 5 sales state in India..       

![Screenshot 2024-01-29 184719](https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/46087256-f408-4420-9544-9b8f69e87a33)

 
 - Step 17 : The image shows total cancelation and total delivered and total refunded.. 
 
 A card visual was used to represent the total order status..
 
![Screenshot 2024-01-29 184734](https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/ef905e08-b5a5-444d-bc67-e3a4583caf0b)
 
 - Step 18 : The report was then published to EXCEL Service.
![Screenshot 2024-01-29 184508](https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/00053768-5086-4453-9c60-ca995daa6626)


# Snapshot of Dashboard (EXCEL Dashboard Service)

![Screenshot 2024-01-29 184601](https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/ab0b37ab-ccbc-4078-85d3-f9408fc1f7a2)

 
 # Report Snapshot (EXCEL DESKTOP)

![Screenshot 2024-01-29 184640](https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/19b811f2-9e2b-4e97-b4cb-dfe7e891beb0)

# Insights

A single page report was created on Excel Desktop.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Customers = 31048

This project shows a store annual report for 2024, which contains various charts and data visualizations about the store's performance. Some of the important factors that can be derived from this report are:

- The store had a peak in sales in June, which could be due to seasonal factors, promotions, or customer demand.
- The store had five top sellers, with Littlejohn being the most successful, followed by Taylor, Morris, Porterfield, and Jones. These sellers could be recognized for their achievements and rewarded accordingly.
- The store had more sales from men than women, which could indicate a gender preference or gap in the store's products or marketing.
- The store had a high percentage of shipped orders, which could reflect a good delivery service and customer satisfaction. However, the store also had some returned and cancelled orders, which could indicate some issues with the product quality, customer expectations, or order processing.
- The store had more orders from web than retail or mail, which could suggest a strong online presence and convenience for customers. However, the store could also explore ways to increase its retail and mail orders, such as offering discounts, coupons, or free samples.
- The store had more orders from adults than teenagers, and more orders from women than men in both age groups. This could imply a target market or niche for the store's products .

 


           thus, higher number of customers are Adults and womens .
           


