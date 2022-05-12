# My-Tableau-Notes
This a repository on my takeaways from exploring, learning and using Tableau.

## Introduction
Tableau is a data visualization tool that allows you to create and share dashboards and reports.

## Data sources
Tableau uses a host of data sources such as Excel, CSV, and JSON. And can also connect to multiples servers such as SQL Server, MySQL, and Oracle.
However, in order to connect to data sources outside of Tableau, there are drivers that has to be installed. 
The available drivers could be found on tableau.com support page.

## Tableau File Types
Tableau uses multiple types of files:

- **Tableau Workbooks (.twb)**: they stores the visualization without including the source data.

- **Tableau Datasources (.tds)**: they store the source data (server address, password, and other information required to access a datasource).

- **Tableau Bookmarks (.tbm)**: they store a connection to a worksheet in another Tableau Workbook.

- **Tableau Data Extract (.tde)**: they store Tableau data as a filtered and aggregated extract.

- **Tableau Package Workbook (.twbx)**: they store extracted data and visualizations for viewing in Tableau or Tableau Reader.

## Table Join
Tableau allows you to join data from different sources.
When you join data, you can also specify how to join the data.
However, by default, Tableau will perform an inner join.
Tableau even let users join data sources with inconsistent name by identifying fields that each sheet has in common.

## Cleaning Data
Tableau allows you to clean data. For example, you can remove rows that contain missing values. A very quick and smart way to do this is to use the **Data Intepreter Tool**. In fact, if Tableau detects unique formatting or extra information after you set up the data source, the Data Interpreter option becomes available.

## Stories
Tableau is a powerful tool that allows you to create stories.
A story is a collection of visualizations that you can share with others.
Stories are useful for conveying a persuasive narrative about the user's insights and understanding of the data.

## Formatting Guidelines
Always give a **title** to your visualizations (on top of the chart) and with a bigger font size than anything else.

Give **informative title** to the variables that are both on the x-axis and y-axis.

Provide a **legend** that describes the meaning of the data.

Use **colors** and **fonts** to increase legibility.

## Dashboards
A dashboard is a collection of several visualizations that makes it easy to compare data and help encover key insights.
As the data is connected to the worksheets in the workbook, the dashboard will automatically update when the data is changed.
Dashboards are interactive and allow users to drill down, explore, and interact with the data in order to discover insights.

## Stories
A story is a sequence of visualizations that could be used to convey a persuasive narrative about the user's insights and understanding of the data.
Those visualization could be a chart, a table, a map, a video, or a combination of several visualizations that work together to convey information. Each individual story is called a **story point**.
Because they tell narrative, stories can be used to make a compelling business case.




