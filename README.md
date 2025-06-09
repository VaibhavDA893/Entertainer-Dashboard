Entertainer Data Analysis Dashboard | Power BI + DAX + Excel + SQL

This project is a comprehensive Entertainer Data Analysis Dashboard built using Power BI, powered by DAX, SQL, and Excel. The dashboard gives meaningful insights into the performance of entertainers across various metrics like views, ratings, type of content, and more.

 The goal of this project is to provide a clean, interactive, and analytical dashboard that could be used by media analysts, content platforms, or talent agencies to understand what works in the entertainment industry.

 🧠 Key Insights Provided

 🔝 Top Entertainers based on Ratings, Views, and Engagement
 🎬 Content Type Distribution (e.g., Movie, Series, Web Show, Music)
  📊 Ratings vs Views Analysis
 🗓️ Year-wise Trends  Growth of content and viewer interest
 🎯 Targeted Filters for deep drill-downs based on Year, Type, and Genre



 🛠️ Tools & Technologies Used

| Tool           | Purpose                                      |
|----------------|----------------------------------------------|
| Power BI   | Dashboard creation and interactive visuals   |
| DAX        | Advanced calculations, KPIs, and measures    |
| Excel      | Data cleaning and structuring                |
| SQL        | Initial data querying & transformation       |

## 🧮 DAX Measures (Used in Power BI)

Some custom DAX measures used in this dashboard include:

- Total Views = SUM(Data[Views])
- Average Rating = AVERAGE(Data[Rating])
- Top Entertainers = CALCULATE(SUM(Data[Views]), FILTER(...))
- Content Count by Type = COUNTROWS(FILTER(Data, Data[Type] = "Movie"))

These calculations allow us to generate dynamic and insightful KPIs for various stakeholder needs.
 📝 Data Preparation

- Raw data was collected in .xlsx format.
- Cleaned and preprocessed in Excel: removed duplicates, handled nulls, converted data types.
- Imported into Power BI using **SQL queries** and cleaned further with **Power Query Editor.
- DAX formulas used to create visual KPIs, trend lines, and aggregation measures.



 📈 Dashboard Preview

[Dashboard Preview](https://github.com/VaibhavDA893/assests/blob/main/Screenshot%202025-05-02%20170958.png)

The dashboard features:

- Dynamic slicers (Year, Content Type)
- Stacked bar charts, KPI cards, and clustered column visuals
- Clean, professional layout with color-coded categories
 🧩 Use Cases

- Media houses tracking audience interest
- Content platforms (like Netflix, YouTube) analyzing performance
- Talent managers comparing entertainer impact
- Academic or portfolio demonstration for data visualization skill


