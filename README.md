# Dynamic Incident Report


This project is a showcase of an interactive Power BI report used to report incidents/accidents using complex DAX measures  with data being pulled from a SQL Server
*Please note that areas of the report have been covered for confidentiality reasons

Main Dashboard:
Shows the landing page of the report with overall figures and stats which are filterable by location and date


Map Feature:
Shows the Map feature page of the report which displays a map with the incidents plotted using longitude and latitude. This page also features a table along with the incident reference numbers and the incident description, when the reference number is hovered over it displays where that incident occurred on the map using a tooltip.


Graphing Tool:
Shows the Graphing Tool page of the report which is a powerful dynamic graph in which the value on the graph can be changed depending on what measure the user selects. For example the graph can display the number of people in incidents per month per year but it can also be switched to show the 12-month rolling figure, as well as switching from showing the number of people to the number of total forms submitted as there can be multiple people registered on one form.


DAX Measrure for MeasureSelector for Graphing Tool:
This shows the DAX measure used to achieve the dynamic graph in the graphing tool


SQL Query for main table within Power BI report:
Showcases how one the tables within the report was pulled
