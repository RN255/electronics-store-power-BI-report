# electronics store power BI report

This is based on a project by Maven Anlytics

## Task
- Present data regarding sales of electronic items at various electronics stores

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](../main/Screenshot%202025-09-30%20143359.jpg)

## Workflow

- get GPT to create some CSV files
- edit the data to make it a bit more realistic and more suitable to the British context
  
- import the CSV files in the power BI query editor
- check for data type issues, check for errors
- Use column profile tools to check for errors help decide which is primary key and secondary key
  
- add start of month and start of week to calendar table.

- go to data modelling view and make sure the tables are connected correctly
- check one to many relationships
- check the star schema
- create a date hierarchy that includes start of month and start of week

- add columns to sales table to work out costs, revenue and profit from each sale
- create a measure for total sales count

- add KPI card visuals
- add bar chart for total orders
- add line chart for revenue
- adjust titles and formatting
- Change graph so 0 is low and 400 is high, better comparisons between stores and products
