# Data-Visualization
**Name: Nha Tran**
---

This repo is where I practice projects related to data visualization. with the topics as below:

1. **Employee Performance - Google Data Studio - employee.xlsx**
https://datastudio.google.com/reporting/43fc8341-6321-48bd-b192-384d9e056fce

   Import data from employee.xlsx

   Know how to add Field (% Clients Not Seen and % of Billable Hours)

	- % Clients Not Seen - (SUM(Clients Assigned)-SUM(Clients Seen ))/SUM(Clients Assigned)
	- % of Billable Hours - SUM(Billable Hours)/SUM(Total Hours)

   Add charts:

	- Scorecard showing Total Hours, Billable Hours, Clients Seen. % Clients Not Seen, etc
	- Drop-down list to filter Name, Location, and Date
	- Table showing employee's performance
	- Donut chart showing % Clients not seen for each employee
	- Bar chart showing Billable Hours for each location
	- Line chart showing Billable Hours daily


2. **Hotel Revenue (2019-2020) - Tableau - hotel_revenue.xlsx**
https://public.tableau.com/shared/BCQ38NBFS?:display_count=n&:origin=viz_share_link

   Import data from hotel_revenue.xlsx (5 sheets including 2018, 2019, 2019, market_segment, and meal_cost)

	- Union 2018-2020 dataset together in tableau --> hotels dataset
	- Link hotels dataset with market_segment and meal_cost 
	
   Create new calculated field

	- Revenue = ([Stays In Week Nights] + [Stays In Weekend Nights])*[Adr]*[Discount]
	- Total Stays = [Stays In Week Nights]+[Stays In Weekend Nights]
  
   Add chart for each Worksheet:

	- Scorecard showing Total Revenue, Total Nights, Average Discount %, and Average Amount Day Rate
	- Line chart showing Revenue by Date of Month
	- Stacked bar chart showing  Total Nights by Hotels (City Hotel and Resort Hotel)
	- Pie chart showing Total Nights by Room Type 
	- Table showing Revenue by market segment 


3. **IBM HR Analytics Employee Attrition & Performance**
https://public.tableau.com/app/profile/nha.tran/viz/IBMHRAnalyticsEmployeeAttritionPerformance_16566458777160/Dashboard1?publish=yes

   Import data from IBM_HR_Analytics.xlsx (kaggle dataset)
  
   Add chart for each Worksheet:

	- Scorecard showing Total Employees
	- Stacked bar chart showing Churners and non-churners in each JobRole for different Departments
	- Pie chart showing Total churners and non-churners based on Business Travel
	- Bar chart showing Attrition count for each Department and Age Distribution for Churners
