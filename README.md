# **Business Intelligence:**

## -  What is Busniess Intelligence ?

### Business intelligence (BI) is the process of transforming data into actionable insights that help a company make strategic and tactical decisions. Is often used to describe a collection of resources that provide fast, easy-to-understand access to data-driven insights about an organization’s current state.

<br />

## - Why use Business Intelligance:

![1](images/1.png)
![2](images/2.png)

<br />

## - Descriptive, Predictive & Prescriptive Analytics:

![3](images/3.png)

### **1. Descriptive Analytics:** 

 + ### Descriptive analytics is often considered the first start in data analytics. Descriptive analytics takes massive amounts of historical data and turns it into digestible chunks. It is the process of deciphering what happened in the past and turning it into something interpretable for the past. It can be helpful to understand past behaviors and consider future outcomes. Most descriptive analytics falls in line with statistical modeling.
 > - (Using Visualizations and Reports).

<br />

### **2. Descriptive Analytics:**
+ ### Businesses can leverage predictive analytics by using statistics, computational modeling and machine learning to identify new sources of data and competitive insights. Using historical data as a guideline with a known set of outcomes, patterns can be found to predict future actions with a surprising degree of accuracy. It enables the business to forecast on what may happen in the future based on probabilities. Think of this data type as information that can be rolled back into multiple channels for the business. We have seen it leveraged in financial modeling, supply chain, logistics and transportation, productivity monitoring, order processing, and more. It offers the business a means to provide actionable insights with your data.

![4](images/4.png)

<br />

### **3. Prescriptive Analytics**
- ### Prescriptive analytics goes even further than descriptive and predictive analytics by allowing a data analyst or scientist to “prescribe” on possible outcomes through data insights, such as past business outcomes, new algorithms, and advanced statistical modeling. You can leverage data and prescriptive analytics to predict trends, future behavior patterns, and finally provide business decision trees to take full advantage of your data insights.

![5](images/5.png)

<br />

------------------------------------

## ***- Data Importing:***

1. ### How to import Data from CSV,Excel and Web files. ✅
2. ### After importing data we do some Visualizing. ✅
3. ### Import Real-time Streaming Data using Power bi and PubNub webpage then create a Dashboard. ✅
4. ### Install SQL Server and import data to Power BI. ✅

5. ### Import Data from OData feed and from Folders in Power BI. ✅

6. ### Dataflow and how to create Gateway and Entitiies. ✅

-------------------------------------

## **What are Dashboards:**
### A Power BI dashboard is a single page, often called a canvas, that uses visualizations to tell a story. Because it is limited to one page, a well-designed dashboard contains only the most-important elements of that story. The visualizations you see on the dashboard are called tiles and are pinned to the dashboard from reports.


![6](images/6.png)

<br />


![7](images/7.png)

<br />

## - **Dashboard Menu**:

![8](images/8.png)

<br />


------------------------------------

## ***- Data Cleaning:***

1. ### How to remove Rows. ✅
2. ### How to remove Columns. ✅
3. ### How to make rows as first headers. ✅
4. ### How to create columns. ✅
5. ### How to remove duplicates. ✅
6. ### How to unpivot columns and  split them. ✅

> ___NOTE:___  The `PIVOT` is used to convert table rows into columns, while the `UNPIVOT` converts columns back to rows.

>To finde `Unpivot Columns` we need to go to `Transform`.

7. ### How to change Data type and replace values. ✅
8. ### How to append and merge Queries by combine the files into one. (States file into one) ✅

> ___NOTE___:  
 **- Append:** means results of two (or more) queries (which are tables themselves) will be combined into one query.\
**- Merge:** is another type of combining queries which are based on matching rows, rather than columns. The output of Merge will be a single query

--------------------------------------------

## ***- Visuals:***

- ### What chats or graph is right to use ? ✅
![9](images/9.png)

<br />

- ### Visualisations Properties: ✅
![10](images/10.png)

<br />

1. ### **Bar Chart:** highlight differences between categories, clearly show trends and outliers, and reveal historical highs and lows at a glance. ✅

![11](images/11.png)

<br />

2. ###  __Line chart:__ is often used to visualize a trend in data over intervals of time – a time series – thus the line is often drawn chronologically. ✅

![12](images/12.png)


<br />

3. ### __Pie graph (or pie chart):__ is a specialized graph used in statistics. The independent variable is plotted around a circle in either a clockwise direction or a counterclockwise direction.The dependent variable (usually a percentage) is rendered as an arc whose measure is proportional to the magnitude of the quantity. ✅

![13](images/13.png)

<br />

4. ### __Stacked bar charts:__  is a graph that is used to break down and compare parts of a whole. Each bar in the chart represents a whole, and segments in the bar represent different parts or categories of that whole. ✅

![15](images/15.png)
<br />

5. ###  __Clustered column chart:__ displays more than one data series in clustered vertical columns. Each data series shares the same axis labels, so vertical bars are grouped by category. ✅

![14](images/14.png)

<br />

6. ### __Area charts:__ emphasize the magnitude of change over time, and can be used to draw attention to the total value across a trend. For example, data that represents profit over time can be plotted in an area chart to emphasize the total profit. ✅

![16](images/16.png)
![17](images/17.png)

<br />

7. ### __Combo chart:__ is the combination of two charts. A combo chart is a single visualization that combines a line chart and a column chart. Combining the 2 charts into one lets you make a quicker comparison of the data.

### -  Combo charts are a great choice:

* when you have a line chart and a column chart with the same X axis.
* to compare multiple measures with different value ranges.
* to illustrate the correlation between two measures in one visualization.
* to check whether one measure meet the target which is defined by another measure
* to conserve canvas space.

![18](images/18.png)

<br />

8. ### __Scatter chart:__ always has two value axes to show one set of numerical data along a horizontal axis and another set of numerical values along a vertical axis. The chart displays points at the intersection of an x and y numerical value, combining these values into single data points. Scatter plots are an effective way to give you a sense of trends, concentrations and outliers that will direct you to where you want to focus your investigation efforts further.

<br />

### - Scatter Charts are a great choice :
* to show relationships between 2 (scatter).
* to plot two groups of numbers as one series of xy coordinates.
* instead of a line chart when you want to change the scale of the horizontal axis
* to turn the horizontal axis into a logarithmic scale.
* to display worksheet data that includes pairs or grouped sets of values. In a scatter chart, you can adjust the independent scales of the axes to reveal more information about the grouped values.
* to show patterns in large sets of data, for example by showing linear or non-linear trends, clusters, and outliers.
* to compare large numbers of data points without regard to time. The more data that you include in a scatter chart, the better the comparisons that you can make.

<br />

9. ### __Treemaps:__ display hierarchical data as a set of nested rectangles. Each level of the hierarchy is represented by a colored rectangle (often called a "branch") containing other rectangles ("leaves"). The space inside each rectangle is allocated based on the quantitative value being measured, with the rectangles arranged in size from top left (largest) to bottom right (smallest). If you are looking to see your data at a glance and discover how the different pieces relate to the whole? Then treemaps are for you. These charts use a series of rectangles, nested within other rectangles, to show hierarchical data as a proportion to the whole.

![19](images/19.png)

<br />

![20](images/20.png)

<br />

10. ### __Funnel chart:__ helps you visualize a linear process that has sequential connected stages. At a glance, the shape of the funnel conveys the health of the process you're tracking. Each funnel stage represents a percentage of the total. So, in most cases, a funnel chart is shaped like a funnel with the first stage being the largest, and each subsequent stage smaller than its predecessor. 

![21](images/21.png)

<br />

### - Funnel charts are a great choice:
* when the data is sequential and moves through at least 4 stages.
* when the number of "items" in the first stage is expected to be greater than the number in the final stage.
* to calculate potential (revenue/sales/deals/etc.) by stages.
* to calculate and track conversion and retention rates.
* to reveal bottlenecks in a linear process.
* to track a shopping cart workflow.
* to track the progress and success of click-through advertising/marketing campaigns.

<br />

### - Funnel charts:
* Can be pinned from reports and from Q&A.
* Can be sorted.
* Support multiples.
* Can be highlighted and cross-filtered by other visualizations on the same report page.

<br />

11. ### __Card charts:__ Sometimes a single number is the most important thing you want to track in your Power BI dashboard or report, such as total sales, market share year over year, or total opportunities.

![22](images/22.png)

<br />

12. ### __Guage Chart:__ A radial gauge chart has a circular arc and displays a single value that measures progress toward a goal/KPI. The goal, or target value, is represented by the line (needle). Progress toward that goal is represented by the shading. And the value that represents that progress is shown in bold inside the arc. All possible values are spread evenly along the arc, from the minimum (left-most value) to the maximum (right-most value). Till now we are discussing visualization comparing different catetories and different values. Sometimes you want to track single value and metric that changes over time that shows you the progress towards particular target.

<br />

### - Radial gauges are a great choice to:
* show progress toward a goal.
* represent a percentile measure, like a KPI.
* show the health of a single measure.
* display information that can be quickly scanned and understood.

![23](images/23.png)

<br />

13. ### __KPIs:__A Key Performance Indicator (KPI) is a visual cue that communicates the amout of progress made toward a measureable goal. A Key Performance Indicator (KPI) is based on a specific measure and is designed to help you evaluate the current value and status of a metric against a defined target. Therefore, a KPI visual requires a base measure that evaluates to a value and a target measure or value, and a threshold or goal.

<br />

### - KPIs are a great choice:
* to measure progress (what am I ahead or behind on?)
* to measure distance to a goal (how far ahead or behind am I?)

![24](images/24.png)

<br />

14.  ### __Matrix:__ A matrix is a grid used to store or display data in a structured format. It is often used synonymously with a table, which contains horizontal rows and vertical columns. While the terms "matrix" and "table" can be used interchangeably, matrixes (or matrices) are considered more flexible than tables. For example, tables generally have a fixed number of rows and columns, while the size of a matrix may change dynamically. The term "matrix" may also be used to refer to a table that has groups of columns within a single row.

![25](images/25.png)

<br />

15. ### __Table:__ is a grid that contains related data in a logical series of rows and columns. It may also contain headers and a row for totals. Tables work well with quantitative comparisons where you are looking at many values for a single category. While the terms "matrix" and "table" can be used interchangeably, matrixes (or matrices) are considered more flexible than tables. For example, tables generally have a fixed number of rows and columns, while the size of a matrix may change dynamically. The term "matrix" may also be used to refer to a table that has groups of columns within a single row.

![26](images/26.png)

<br />

