OLA RIDE INSIGHTS
PROJECT REPORT
Ride-Sharing & Mobility Analytics
Python  •  SQL  •  Power BI  •  Streamlit
Prepared by: Manjula M
Internship / Capstone Project Submission
 
Executive Summary
OLA Ride Insights is a ride-sharing and mobility analytics project focused on exploring booking activity, ride outcomes, vehicle usage, revenue patterns, cancellations and service ratings. The project brief describes a workflow that combines data understanding and preprocessing, exploratory analysis, SQL query development, interactive Power BI dashboards and a Streamlit application.
The Power BI requirement is organised into five report views: Overall, Vehicle Type, Revenue, Cancellation and Ratings. The supplied screenshot reference contains seven visual captures that are included in this report as project evidence.
Project at a Glance
Project element	Details
Project title	Ola Ride Insights
Domain	Ride-Sharing & Mobility Analytics
Skills covered	SQL querying, data preprocessing, Power BI visualization, Streamlit app development and business intelligence insights
Tools / technologies	Python, Pandas, NumPy, Matplotlib, Seaborn, SQL, Power BI and Streamlit
Primary analytical themes	Ride volume, booking status, vehicle type, revenue, cancellations and ratings
Power BI structure	Five views: Overall, Vehicle Type, Revenue, Cancellation and Ratings
Prepared by	Manjula M
Project Objectives
•	Explore the ride-booking dataset and identify the key fields required for analysis.
•	Clean and preprocess the data by handling missing or inconsistent values and standardising data types.
•	Use SQL queries to answer business questions about successful rides, vehicle types, cancellations, customers, payments and ratings.
•	Build interactive Power BI report pages with clear visuals, KPIs, filters and slicers.
•	Develop a Streamlit application to present SQL results with interactive filters and search options.
•	Communicate findings using business-focused explanations and project documentation.
 
STAGE 0 — Project Goal & Problem Statement
1. Project Goal
The goal is to analyse OLA ride-booking data and convert raw booking records into useful operational and customer insights. The analysis is intended to help understand demand patterns, booking outcomes, vehicle usage, revenue, cancellations and ratings.
2. Problem Statement
The rise of ride-sharing platforms has transformed urban mobility, offering convenience and affordability to users. OLA generates data related to ride bookings, driver availability, fare calculations and customer preferences. The project brief identifies the challenge of deriving actionable insights from this data. It proposes data analytics, visualization and an interactive application to support operational efficiency, customer satisfaction and informed business decisions.
3. Business Use Cases
•	Identify peak demand hours and support better driver allocation.
•	Analyse customer behaviour for possible personalised marketing strategies.
•	Understand pricing patterns and surge-pricing effectiveness.
•	Detect unusual patterns or potential fraudulent activity in ride data.
4. Role of Each Tool
Tool	Role described in the project
Python	Data loading, cleaning, preprocessing and exploratory data analysis.
Pandas / NumPy	Tabular data manipulation and numerical processing.
Matplotlib / Seaborn	Exploratory data visualisation.
SQL	Filtering, aggregation and querying booking, cancellation, payment and rating data.
Power BI	Interactive dashboards, KPIs, charts, slicers and business insights.
Streamlit	User-friendly application for displaying SQL results, filters and search options.
 
STAGE 1 — Data Understanding & Preprocessing
1. Data Understanding
The project brief identifies ride status, payment method and ratings as important variables to inspect during initial exploration. The dataset is referred to in the brief as “OLA PROJECT”. The source document does not state the dataset row count, column count or detailed missing-value totals; these should be taken from the actual cleaned dataset or notebook rather than estimated.
2. Data Cleaning & Preprocessing
The specified preparation activities are:
•	Handle missing or inconsistent values.
•	Convert columns to appropriate data types and standardise formats.
•	Create derived features when they are useful for analysis.
•	Retain clean and consistent fields for SQL queries and Power BI visuals.
3. Validation
The project guidelines call for validating SQL outputs against the dataset. Before final submission, check that date fields, booking identifiers, ride status, vehicle type, payment method, booking value, ride distance and rating fields are interpreted consistently across Python, SQL and Power BI.
4. Data Quality Evidence to Record
Validation item	What to verify
Missing values	Identify missing values and document the treatment applied.
Data types	Confirm dates, numeric values, identifiers and category fields use suitable types.
Duplicates	Check whether duplicate booking records exist and document the handling.
Categories	Standardise booking status, vehicle type and payment method labels.
Numeric fields	Check ride distance, booking value and rating ranges for invalid values.
 
STAGE 2 — SQL Query Development
The project brief specifies ten SQL business questions. These questions focus on successful rides, vehicle-level distance, customer and driver cancellations, customer booking frequency, driver ratings, UPI payments, customer ratings, successful booking value and incomplete rides.
1.	Retrieve all successful bookings.
2.	Find the average ride distance for each vehicle type.
3.	Get the total number of cancelled rides by customers.
4.	List the top 5 customers who booked the highest number of rides.
5.	Get the number of rides cancelled by drivers due to personal and car-related issues.
6.	Find the maximum and minimum driver ratings for Prime Sedan bookings.
7.	Retrieve all rides where payment was made using UPI.
8.	Find the average customer rating per vehicle type.
9.	Calculate the total booking value of rides completed successfully.
10.	List all incomplete rides along with the reason.
SQL Validation Approach
•	Use the correct booking status and cancellation-reason categories from the dataset.
•	Check aggregation logic and grouping columns for each query.
•	Validate record counts and totals against the source data.
•	Keep query names and output columns clear so results can be reused in documentation and Streamlit.
 
STAGE 3 — Power BI Dashboard Development
The project brief lists ten Power BI / Tableau analysis questions and groups them into five report views. The five-view structure below follows the exact “Segregation of the views” section in the provided OLA project brief.
Power BI view	Required analysis
1. Overall	Ride Volume Over Time; Booking Status Breakdown
2. Vehicle Type	Top 5 Vehicle Types by Ride Distance
3. Revenue	Revenue by Payment Method; Top 5 Customers by Total Booking Value; Ride Distance Distribution Per Day
4. Cancellation	Cancelled Rides Reasons (Customer); Cancelled Rides Reasons (Drivers)
5. Ratings	Driver Ratings; Customer Ratings
Ten Required Power BI Questions
11.	Ride Volume Over Time
12.	Booking Status Breakdown
13.	Top 5 Vehicle Types by Ride Distance
14.	Average Customer Ratings by Vehicle Type
15.	Canceled Rides Reasons
16.	Revenue by Payment Method
17.	Top 5 Customers by Total Booking Value
18.	Ride Distance Distribution Per Day
19.	Driver Ratings Distribution
20.	Customer vs. Driver Ratings
Dashboard Design Principles
•	Keep the five report views clearly named and easy to navigate.
•	Use consistent colours, titles, number formats and spacing across pages.
•	Make sure chart titles and axis labels are readable.
•	Use slicers and filters to support dynamic exploration.
•	Avoid clipped KPI cards, truncated legends and overlapping data labels.
•	Validate displayed totals against the underlying data before submission.
Screenshot note: the supplied Overall Dashboard screenshot visibly shows a date selection from 1 November 2025 to 30 November 2025 and a Total Bookings card displaying 100000. The adjacent booking-value card is clipped in the supplied capture, so its full value is not transcribed here.
 
STAGE 4 — Power BI Dashboard Screenshots
The following seven screenshots are reproduced from the supplied Power BI screenshot reference document. They are presented as visual evidence and retain the reference order and headings.
Figure 1 — Overall Dashboard
Executive overview page showing the date filter, KPI cards, booking-status breakdown and ride-volume trend.
 
Power BI reference screenshot 1
 
Figure 2 — Booking Status Analysis
Visual analysis of the distribution of booking outcomes.
 
Power BI reference screenshot 2
 
Figure 3 — Ride Volume Over Time
Time-based view of ride booking volume.
 
Power BI reference screenshot 3
 
Figure 4 — Vehicle Type Analysis
Vehicle-category analysis included in the supplied reference.
 
Power BI reference screenshot 4
 
Figure 5 — Revenue and Payment Analysis
Revenue and payment-related analysis included in the supplied reference.
 
Power BI reference screenshot 5
 
Figure 6 — Cancellation Analysis
Cancellation-related analysis included in the supplied reference.
 
Power BI reference screenshot 6
 
Figure 7 — Ratings Analysis
Ratings-related analysis included in the supplied reference.
 
Power BI reference screenshot 7
 
STAGE 5 — Streamlit Application Development
The project brief requires a user-friendly Streamlit interface that displays SQL query results. It also specifies interactive filters and search options, and describes embedding Power BI visuals for a combined analytics experience.
Application Requirements
•	Display selected SQL query results in a clear and readable format.
•	Provide interactive filters and search options.
•	Present relevant booking trends, ratings and revenue analysis.
•	Embed Power BI visuals where the integration and access settings permit.
•	Keep the application responsive and straightforward to use.
Project Documentation & Deployment
The brief asks for documented insights, queries and dashboard explanations, along with a deployed and accessible Streamlit application. It also asks for clean, well-documented code and Git version control.
 
STAGE 6 — Expected Results & Evaluation
Expected Results in the Project Brief
•	An interactive dashboard and application showcasing key insights.
•	Streamlined access to booking trends, ratings and revenue analysis.
•	Actionable insights that can support improvements in ride experience and service efficiency.
Project Evaluation Metrics
Evaluation area	Evaluation focus
SQL	Accuracy of SQL queries and insights.
Power BI	Effectiveness of Power BI visualisations.
Streamlit	Usability and responsiveness of the application.
Business Interpretation Framework
When presenting the completed analysis, explain what the visuals show, which segment or period is most notable, and what operational question the result may help answer. Do not present a pattern as a proven cause unless the data and analysis support that conclusion.
 
Conclusion
OLA Ride Insights demonstrates an end-to-end analytics workflow for ride-sharing data. The project brief connects data cleaning and exploratory analysis with SQL-based business questions, five Power BI report views and a Streamlit application. Together, these components are intended to make booking, vehicle, revenue, cancellation and rating information easier to explore and communicate.
The screenshots included in this report provide visual evidence from the supplied Power BI reference. For final submission, the dashboard pages, SQL outputs and Streamlit application should be checked against the actual dataset so that all displayed values and interpretations are accurate.
Final Submission Checklist
•	☐ Raw and cleaned OLA dataset saved.
•	☐ Data-cleaning and EDA code saved and documented.
•	☐ All ten SQL questions answered with saved queries and outputs.
•	☐ Power BI report contains the five required views: Overall, Vehicle Type, Revenue, Cancellation and Ratings.
•	☐ Power BI visuals, titles, slicers and displayed values checked for readability and accuracy.
•	☐ Streamlit application includes SQL results, filters and search options.
•	☐ Power BI visuals embedded in Streamlit where required and technically available.
•	☐ Code documented and maintained using Git version control.
•	☐ Seven reference screenshots included in the project report.
•	☐ Final project files and findings prepared for submission.
Project Reference
Primary source: OLA RIDE project brief supplied by the user. The dashboard screenshot evidence is taken from the user-supplied “New Microsoft Word Document (5).docx”. The report follows the five-view Power BI segregation and ten SQL / ten Power BI questions listed in the project brief.
