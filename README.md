
#  Store Annual Report -Dashboard

### Dashboard Link : https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/70c02fd2-c0d2-4930-bc26-1e5eee3fce32


## Problem Statement

This dashboard helps the  understand their customers better. It helps the airlines know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the average delay & departure time, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these unwanted delays.

Since, number of neutral/dissatisfied customers (almost 57 %) are more than satisfied customers (around 43 %), thus in all they must work on improving their services. 

Also since average delay in arrival & departure both is 15 minutes, thus they must try to reduce it.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".
- Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
- Step 10 : A bar chart was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers. While creating this visual, field named "Gender" was also added to the Legends bucket, thus number of customers are also seggregated according the gender. 
- Step 11 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Baggage Handling

  (b) Check-in Services
  
  (c) Cleanliness
  
  (d) Ease of online booking
  
  (e) Food & Drink
  
  (f) In-flight Entertainment

  (g) In-flight Service
  
  (h) In-flight wifi service
  
  (i) Leg Room service
  
  (j) On-board service
  
  (k) Online boarding
  
  (l) Seat comfort
  
  (m) Departure & arrival time convenience
  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

- Step 12 : In the report view, under the insert tab, two text boxes were added to the canvas, in one of them name of the airlines was mentioned & in the other one company's tagline was written.
- Step 13 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 
- Step 14 : Calculated column was created in which, customers were grouped into various age groups
        

        
- Step 15 : New measure was created to find total count of customers.




        
A card visual was used to represent count of customers.

![Screenshot 2024-01-29 184704](https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/c225d80b-879b-49b0-80cd-76a8322daaad)
        
 - Step 16 : New measure was created to find  % of customers,
 
 Following DAX expression was written to find % of customers,
 
         % Customers = (DIVIDE(airline_passenger_satisfaction[Count of Customers], 129880)*100)
 
 A card visual was used to represent this perecntage.
 
 Snap of % of customers who preferred business class
 
![Screenshot 2024-01-29 184719](https://github.com/akashsingh62/Annual-report-project-2024/assets/155260152/46087256-f408-4420-9544-9b8f69e87a33)

 
 - Step 17 : New measure was created to calculate total distance travelled by flights & a card visual was used to represent total distance.
 
 
    
 A card visual was used to represent this total distance.
 
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
           


