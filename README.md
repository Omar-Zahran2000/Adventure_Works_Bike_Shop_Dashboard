#  AdventureWorks Power BI Analytics Dashboard

##  Project Overview
This Power BI project leverages the AdventureWorks retail dataset to create an enterprise-ready suite of dashboards that uncover insights into sales performance, customer behavior, and regional trends. The goal is to simulate a real-world business intelligence solution using interactive, drillable visualizations.

##  Objectives
- Import and clean data from multiple Excel and CSV sources (2020–2022).
- Build a semantic model with appropriate relationships and DAX measures.
- Design multi-page dashboards for executive, regional, customer, and product-level views.
- Empower users with AI visuals, drill-through, slicers, and dynamic field parameters.

##  Data Source
The dataset is derived from AdventureWorks, a simulated business dataset with:
- Sales and revenue transactions
- Customer demographics
- Product categories and subcategories
- Date and territory dimensions

##  Tools & Techniques

| Tool / Feature       | Purpose                                                   |
|----------------------|-----------------------------------------------------------|
| Power BI Desktop     | Main reporting and modeling environment                   |
| Power Query Editor   | Data transformation, cleanup, and shaping                |
| DAX                  | Custom KPIs, time intelligence, calculated columns        |
| Model View           | Relationship building and normalization                   |
| Drill-through        | Navigate to product or customer detail views              |
| Field Parameters     | User toggle between metrics (Total Customers vs. Revenue per Customer) |
| AI Visuals           | Smart narrative, Q&A, and decomposition trees             |

##  Dashboards & Pages

###  Executive Dashboard
- Total revenue, profit, returns, and return rate
- Weekly order trends from 2020–2022
![alt text](<Maven Market.GIF 1.gif>)

###  Product Detail (Drill-through)
- Trends by product: orders, profit, revenue
- User-defined price adjustment
- Monthly profit with line and area charts
![alt text](<5. Product Detail (1).JPG>)

###  Customer Detail (Drill-through)
- Top 100 customers by order volume and revenue
- Demographics by occupation and income
- Dynamic metric switch (via field parameter)
- Most valuable customer over time
![alt text](<6. Customer Detail.JPG>)

###  Map View
- Total orders by country (United States, UK, Canada, France, Australia)
- Region slicer to filter map by continent
![alt text](<4. Map.JPG>)

###  Q&A
- Natural language visual generation (e.g., “orders by month in 2021”)
- Responsive visual cards and charts
![alt text](<4. Map-1.JPG>)

###  Decomposition Tree
- Drill into return rate by category > subcategory > product
![alt text](<4. Map-2.JPG>)

##  Key Insights

### Sustained Growth
Order volume grew sharply mid-2021 and remained strong into 2022, signaling operational scaling or marketing success.

### Dominant Markets
- United States leads in volume.
- Europe shows potential (notably UK and France).
- Australia underperforms in both revenue and volume.

### Product Standouts
- High-volume performers include Patch Kit/8 Patches,  Water Bottle-30oz, and Mountain Tire Tube.
- Accessories consistently show low return rates, suggesting good customer satisfaction.

### Customer Profiles
- High-value customers often come from skilled manual or professional roles.
- Repeat orders clustered within middle-income groups.

### Engagement Enablers
- Field parameters, dynamic slicers, and drill-through increase report flexibility.
- Executive users can filter by region, year, product, and customer persona to quickly answer strategic questions.

##  Learning Outcomes
- Built full-stack Power BI dashboards from raw data
- Applied advanced DAX for custom metrics, filters, and time-based logic
- Created a modular layout supporting high-level KPIs and granular deep dives
- Leveraged AI visuals to support exploratory data analysis

## Conclusion
This project demonstrates how Power BI can be used to deliver a business-ready, interactive reporting system that mimics real enterprise analytics environments. From modeling to storytelling, it exemplifies the power of data visualization for decision-making.
