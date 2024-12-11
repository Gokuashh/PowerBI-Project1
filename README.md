# AtliQ Grands Business & Data Intelligence Dashboard (PowerBI Project 1)

## Objective

AtliQ Grands, a prominent hotel chain in India, has been facing challenges in maintaining its market share and revenue within the luxury/business hotel sector. With competitors gaining traction and internal management inefficiencies, the company decided to incorporate "Business and Data Intelligence" to better understand their market and regain lost ground. The objective of this project is to help AtliQ Grands utilize historical data for actionable insights that can drive strategic decisions, improve revenue, and optimize performance across various hotel properties.

## Key Features

The Power BI dashboard created as part of this project offers a wide range of key features to analyze and visualize the performance of AtliQ Grands hotels:

- **Trends by Key Metrics**: Visual representation of performance trends over time, including revenue, occupancy, ADR (Average Daily Rate), and RevPAR (Revenue per Available Room).
- **Revenue % by Category**: A breakdown of the total revenue percentage contribution from different categories such as room type, hotel category, or service type.
- **Performance by Property**: Insights into how individual hotel properties are performing in comparison to others based on key metrics like revenue, occupancy, ADR, and RevPAR.
- **City/Room Type/Category Filter**: Allows users to drill down and filter the data based on different factors such as city, room type, hotel category, etc., to tailor insights to specific needs.
- **Charts for Weekly Revenue, Occupancy, ADR**: Interactive charts showing trends in revenue, occupancy %, and ADR, based on week numbers and hotel categories.
- **Interactive Dashboard**: A highly interactive Power BI dashboard enabling easy navigation, real-time data filtering, and intuitive visual representation of complex data.

## Process

1. **Data Collection**: The historical hotel data was sourced from Excel files containing multiple sheets, each representing data for different properties or categories.
2. **Data Cleaning**: The raw data was cleaned and transformed in the Power BI Query Editor. This process involved:
   - Removing unnecessary columns and rows.
   - Handling missing or inconsistent data.
   - Aggregating data at the property level and time intervals.
3. **Data Transformation**: Key calculated metrics such as revenue percentages, occupancy %, and ADR were derived using Power BI’s DAX (Data Analysis Expressions) to provide deeper insights.
4. **Dashboard Development**: Using Power BI’s interactive visualization tools, several charts, tables, and graphs were created to represent the key metrics and trends.
5. **User Interaction**: Filters and slicers were implemented to allow dynamic changes based on user selections (e.g., selecting a specific city, room type, or category to see filtered insights).

## Technologies Used

- **Power BI**: The primary tool used for creating interactive dashboards, data visualizations, and deriving key insights from historical data.
- **Excel**: Source of raw data, which was imported into Power BI for analysis and reporting.
- **Power BI Query Editor**: Used for data cleaning, transformation, and aggregation of data.
- **DAX (Data Analysis Expressions)**: Used to create custom metrics, calculations, and key performance indicators (KPIs).

## Files and Structure

- **Data File**:
- <a href="https://github.com/Gokuashh/PowerBI-Project1/blob/main/dim_date.csv" Dates<a/>
-
-
-
-  The raw data in Excel format used for analysis.
- **Power BI File**: `AtliQ_Grands_Dashboard.pbix` – The Power BI file containing the interactive dashboard and all related visualizations.
- **README.md** – This file.

## How to Use

1. Clone this repository to your local machine.
2. Open the `AtliQ_Grands_Dashboard.pbix` file in Power BI Desktop.
3. Ensure that the Excel data file is available in the same directory or update the data source path if necessary.
4. Interact with the dashboard by using filters to customize the view based on different properties, room types, cities, and categories.

## Future Improvements

- **Real-time Data Integration**: Integration of real-time data sources could provide up-to-date insights on hotel performance.
- **Predictive Analytics**: Leveraging machine learning models for forecasting future trends in revenue, occupancy, and ADR.
- **More Granular Data**: Additional data points, such as customer demographics or competitor pricing, could be integrated for deeper analysis.
  
 ## Conclusion

This Power BI dashboard empowers the management team at AtliQ Grands to make data-driven decisions based on actionable insights from their historical performance. By focusing on key metrics like revenue, occupancy, and ADR, and by offering granular filtering options, the dashboard facilitates better understanding of the business and the competitive landscape. This tool enables the hotel chain to identify trends, pinpoint areas for improvement, and develop strategies to optimize revenue and market share.

With this solution, AtliQ Grands can regain its competitive edge, drive strategic decisions, and improve operational performance across its properties.

