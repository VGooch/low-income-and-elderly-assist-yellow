### Interactive Excel Dashboard For Informing Low Income and Elderly Assistance Grants

You have been tasked with creating an interactive dashboard for Hand Up America, an organization that provides assistance for low income and elderly taxpayers. You have been asked to create this dashboard using the provided 2016 IRS individual tax return data. HUA would like the dashboard to include state level information, and how those data compare to the national picture. Below are a series of questions to help you think about what visualizations would be helpful in your dashboard. You will give a 10-15 minute presentation on your dashboard to the HUA board to show them how to use it and what insights your dashboard can provide.

Started by creating a table containing the state names, the number of total returns filed, and the number of elderly returns filed. Create a calculated column for the percentage of elderly returns out of total returns filed. Create this table in a new worksheet any way you'd like (recall `tidy data`, where each row is an observation and each column is a variable). One function I found helpful for the task was the `OFFSET()` function.

```
OFFSET(reference, rows, columns, [height], [width])
reference: starting point
rows: number of rows down from the starting point
columns: number of columns to the right of the starting point
height: height of the returned reference (optional)
width: width of the returned reference (optional)
```
![offset examples](/assets/offset.png)


Use your findings from the above exercise and any other analyses you think of to create charts or visualizations that might help guide the decision making at HUA. Remember that HUA's goal is to `provide assistance for low income and elderly taxpayers`. Your deliverable will be a single dashboard that captures what you think are the most important factors for HUA to consider.

![Final Dashboard](/assets/Hand_Up_Final.PNG)
