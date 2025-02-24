
## Goals When Selecting charts
### The type of chart depends on the type of question you are asking
few of the more common goals for charts are to show the following:
- Composition—Composition is what makes up the whole of an entity under consideration. as great example is a bar chart as  it makes up the whole entity 
-  Ranking—Ranking is the relative order of items. We sort the categories by bar length, which is proportional to the amounts allocated. 
- Correlation/Relationship—Correlation is how two variables are related to one another. An example of this is the relationship between average low temperature and average annual snowfall for various cities in the United States.
- Distribution—Distribution is how items are dispersed. An example of this is the number of calls received by a call center in a day, measured on an hourly basis. 
### Goal: To Show a Relationship
To show a relationship between two quantitative variables, we recommend a scatter chart. An example is the temperature and snowfall data shown in a scatter chart in Figure 2.7. When dealing with three quantitative variables, a bubble chart can be used. Line charts can be used to emphasize the pattern across consecutive data points and are commonly used to display relationships over time. Stock charts show the relationship between time and stock price. Column charts, bar charts, and heat maps can be used to show the relationships that exist between categories.
An illustration shows icons of seven charts that show a relationship: Scatter, bubble, line, stock, column, bar, and heat map.
![](Icon1.png)

### Goal: To Show Distribution
In addition to being useful for showing the relationships between quantitative variables, scatter and bubble charts can be useful for showing how the quantitative variable values are distributed over the range for each variable. Other chart types useful for showing how data are distributed that rely on more advanced statistical concepts are discussed in Chapter 5.

Column and bar charts can be used to show the distribution of a variable of interest over discrete categories or time periods. For example, Figure 2.5 shows the distribution of zoo attendance by time (month). As previously mentioned, column charts rather than bar charts should be used for distribution over time, as it is more natural represent the progression of time from left to right. A choropleth map shows the distribution of a quantitative or categorical viable over a geographic space. Figures 2.19 and 2.21 are examples of these.
![](Icon2.png)

### Goal: To Show Composition
When the goal is to show the composition of an entity, a good choice is a bar chart, sorted by contribution to the whole. An example is the New York City budget in Figure 2.2. A stacked bar chart is appropriate for showing the composition of different categories, and a stacked column chart is good for showing composition over a time series. Figure 2.17, the sales for Cheetah Sports by region, is a good example of a stacked column chart with time series data.While the goal of a pie chart is to show composition, for reasons discussed in the next section, we do not recommend the use of pie charts.

A treemap shows composition in a situation where there is a hierarchical structure among categorical variables. In Figure 2.26, we see the brand values (the quantitative variable of interest) for companies within industry sectors. For example, the technology sector is composed of six brands in the top ten. All other sectors are composed of only a single brand.

A waterfall chart shows the composition of a quantitative variable of interest over time or category. For example, Figure 2.30 shows the composition of the final value of gross profit over time. A funnel chart also shows composition in the sense that going from the bottom of the funnel to the top gives the composition of the original set at the top of the funnel. The funnel chart for the hiring process in Figure 2.34 is an example.
![](Icon3.png)

### Goal: To Show Ranking
Bar charts and column charts, sorted on the cross-sectional quantitative data of interest across categories, can be used to effectively show the rank order of categories on the quantitative variable. An example is the ten categories ranked by spending allocation in the New York City budget shown in Figure 

When trying to select a chart type, we recommend starting with understanding the needs of the audience to determine the goal of the chart, understanding the types of data you have, and then selecting a chart based on the guidance provided in this section. Like most analytics tools, it is important to experiment with different approaches before arriving at a final decision on your data visualization. 
An illustration shows icons of two charts that show ranking: Bar and column.
![](Icon4.png)
## Bubble chart
used for exploring relationships between two quantitative variables. More appropriate for when trying to show a relationships with more than two quantitative variables. The idea is we are comparing three variables here. One which is rate per day, the second being wait time, and the third being the size of the airport aka expected millions of people
![shows the relationship between three or more variables](BubbleChart.png)
## Choropleth map
uses shades of color and unique colors and symbols to show quantitative or categorical variables on the map . The easiest example of this is a map of the United States showcasing population with darker regions indicating a denser population. 
![](ChoroplethMap.png)
## Clustered bar chart
![](StackedColumnChart.png)
A great way to see both the growth and the overall value of the sales. This is a great way to compare subset growth to the total size of a data source.
## Clustered column chart
when we to create charts with multiple variables side by side and compare their magnitude together Its also best denoted with different colors
![](ClusteredColumnChart.png)
## Column chart
Are more appropriate when we are summarizing data about categorize
- A column chart displays a quantitative variable by category or time period using vertical bars to display the magnitude of a quantitative variable
- vs the lines chart which is better at showing a trend rather then magnitude 

## Combo chart
![](CombindChart.png)
This Chart is good because it shows the overall trend of cost and revenue leading to an understanding of the big picture. However if we wanted to know specifics metrics and days for data. This chart makes it hard to see that thus we can combined this chart with a table 
![](CombindChart2.png)
Now we have combined the chart we can see the exact values for key points in time. This gives us the best of both worlds. The big picture and the 
## Funnel chart

![](CS%20491/Chapter%202/Images/FunnelChart.png)
A funnel chart is often used to show the progression of sales leads that are converted through a series of steps to an eventual sale, but any progression of larger values to smaller values over a series of nested categories can be illustrated with a funnel chart. As an illustration, let us consider a company whose goal is to grow the number of well-qualified members on its data science team. The hiring process involves the following steps: 
(1) post the job ad; candidates apply and are then referred to as applicants
(2) applicants are given a technical test; those who pass are deemed technically qualified
(3) the technically qualified set of applicants are invited to do Zoom interviews, and based on the Zoom interviews, a subset of the technically qualified applicants are deemed finalists and are invited for on-site interviews
(4) based on test scores and the on-site interviews, a subset of the finalists are offered employment, and (5) those who accept are hired.
## Heat map
2d that uses shades of color to indicate magnitude. Best used for identifying trends and patterns and patterns. It can be used to effectively convey data over different arreas, across time or both as we see here. 
![](HeatMapChart.png)
## Line chart
- A line chart uses a point to represent a pair of quantitative variable values, one value along the horizontal axis and the other on the vertical axis, with a line connecting the points. Line charts are very useful for time series data
## Radar chart

Another chart to be avoided is a radar chart. A radar chart is a chart that displays multiple quantitative variables on a polar grid with an axis for each variable. The quantitative values on each axis are connected with lines for a given category. Multiple categories can be overlaid on the same radar chart.

Let us consider data on four suppliers of a component needed by Newton Industries. Newton manufactures high-performance desktop computers and has started to vet four possible suppliers of one of the components needed for its computers. Newton’s management needs to select a supplier to provide the component and has collected data on the percentage of late shipments, the percentage of defective components delivered, and the cost per unit each supplier would charge. These data are in the file newton suppliers and are shown in Figure 2.35. Figure 2.36 is the radar chart created from these data.

The radar chart in Figure 2.36 has three axes corresponding to the three columns of data in Figure 2.35. Luckily, the three variables are of roughly the same magnitude. Variables of very different scales can distort a radar chart. The four suppliers each have their own color, and their data are connected by lines. Since Newton presumably wants low values for percentage late, percentage of defective components, and cost per unit, a dominant supplier’s rectangle would be completely inside its competitors. It appears from Figure 2.36 that the supplier Foster might be the best choice, but it is difficult to distinguish the cost per unit. Even with this very small data set, the radar chart is quite busy and difficult for an audience to interpret.

Perhaps a better choice is the clustered column chart shown in Figure 2.37. Here, we can see that Foster is clearly better on percentage late and percentage defective and competitive on price. We do note that for more suppliers, even the clustered column chart will become cluttered. Not surprisingly, manufacturers will often develop a scoring model so a single score can be computed and used to compare suppliers. 
![](RadarChart.png)
## Scatter chart
The relationship between two quantitative data sets makes scatter charts a good choice .
think about money per square foot 
- Time Series Horizontal being the time 
-  A scatter chart is appropriate for better understanding the relationship between two quantitative variables.

## Stock chart
![](StockChart.png)
A stock chart is a graphical display of stock prices over time. Let us consider the stock price data for the telecommunication company Verizon Communications given in the file Verizon. As shown in Figure 2.31, this data set lists, for five trading days in April, the date, opening price per share (price per share at the beginning of the trading day), the high price (highest price per share observed during the trading day), the low price (the lowest price per share observed during the trading day), and the closing price (the price per share at the end of the trading day). Excel provides four different types of stock charts. We illustrate the simplest one here, the high-low-close stock chart. A high-low-close stock chart is a chart that shows the high value, low value, and closing value of the price of a share of a stock at several points in time. The difference between the highest and lowest share prices for each point in time is represented by a vertical bar, and the closing share price by a marker on the bar. 
## Treemap
![](TreeMapsCharts.png)
uses size color and arrangement of rectangles to display the magnitudes of a quantitative variable for different categories. the larger the rectangle the greater the magnitude. Data that is composed of further subcategories can use the tree map rather effectively and are called hierarchical data
![](TreeMapsCharts2.png)
## Waterfall chart
![](WaterFallChart.png)
A waterfall chart is a visual display that shows the cumulative effect of positive and negative changes on a variable of interest. The changes in a variable of interest are reported for a series of categories (such as time periods), and the magnitude of each change is represented by a column anchored at the cumulative height of the changes in the preceding categories.
## Summary
### Chapter Summary: Data Visualization and Chart Selection in Excel
In this chapter, we explored how the objective of data analysis and the nature of the data should guide chart selection. We provided step-by-step instructions on creating and modifying charts in Excel and examined various commonly used chart types, discussing their purposes and best use cases.
#### **Scatter, Bubble, and Line Charts**
- A **scatter chart** is ideal for visualizing relationships between two quantitative variables, making it particularly useful for identifying patterns and correlations.
- A **bubble chart** extends the scatter chart by incorporating a third quantitative variable, represented through the varying sizes of the bubbles.
- A **line chart** is essentially a scatter chart with data points connected by lines, making it especially effective for time-series data. By linking points, line charts provide a clearer sense of continuity and trend progression than scatter plots.
#### **Column and Bar Charts**
- A **column chart** represents a quantitative variable using vertical bars, where the height signifies the magnitude of the data for a given category or time period.
    - A **clustered column chart** displays multiple quantitative variables side by side using different colors for comparison.
    - A **stacked column chart** illustrates the composition of a total by stacking segments in different colors within each column to show subcategory contributions.
- A **bar chart** serves the same purpose as a column chart but uses horizontal bars instead of vertical columns.
    - **Clustered bar charts** and **stacked bar charts** function similarly to their column-chart counterparts but provide a different visual orientation.
#### **Map-Based Visualizations**
- A **choropleth map** is a geographic visualization that uses color shades, distinct colors, or symbols to represent data values across different regions.
- A **heat map** is a two-dimensional representation that uses varying shades of color to indicate the magnitude of a variable across different areas.
- A **treemap** displays hierarchical data using nested rectangles of varying sizes and colors to represent proportions and relationships within categories.
#### **Specialized Charts**
- A **waterfall chart** demonstrates the cumulative impact of positive and negative changes on a particular variable, making it useful for financial analysis and tracking net values.
- A **stock chart** visualizes stock price fluctuations over time. A high-low-close stock chart, for example, tracks the high, low, and closing prices of a stock over a given period.
- A **funnel chart** illustrates the progressive reduction of a quantitative variable across different stages or categories, often used in sales and marketing analytics.

#### **Chart Selection and Best Practices**

We provided guidelines for selecting the most appropriate chart type based on the analytical goal and data characteristics. Additionally, we covered scenarios where tables or a combination of tables and charts might be preferable—particularly when exact values are required. Furthermore, we highlighted certain chart types that are best avoided due to potential misinterpretation or inefficiency.

Finally, we introduced the **Recommended Charts** tool in Excel, which helps users choose suitable visualizations based on their data structure and intended insights.

By understanding the strengths and applications of various chart types, users can create more effective and insightful data visualizations, enhancing their ability to communicate complex information clearly and accurately.