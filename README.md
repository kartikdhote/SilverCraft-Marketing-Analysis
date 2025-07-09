#SilverCraft Company: Marketing Campaign Performance Analysis
Project Overview
This project delivers a comprehensive Power BI dashboard designed for Silvercraft Company, a prominent e-commerce business specializing in premium silver asset accessories. The dashboard provides an in-depth analysis of their digital marketing campaign performance across key channels: Facebook, Instagram, and Pinterest. The primary goal is to empower stakeholders with actionable insights to track key metrics, identify top-performing channels, understand customer engagement, and make data-driven decisions for optimizing future marketing strategies and maximizing Return on Ad Spend (ROAS).

##Business Understanding & Problem Statement
Silvercraft Company launched multiple digital marketing campaigns and required a robust solution to measure their effectiveness. The challenge was to move beyond raw data to gain clear insights into which campaigns and channels were performing best, where ad spend was most efficient, and how to improve overall marketing ROI. This analysis addresses these core business questions by:

Evaluating overall campaign success based on sales, ad spend, and conversion rates.

Providing a detailed comparison of individual marketing channel performance.

Analyzing monthly trends and identifying periods of high/low performance and efficiency.

Understanding the impact of different ad types (Collection, Discount) and geographical locations (Bengaluru, Delhi, Mumbai).

Ultimately, delivering data-driven recommendations to optimize ad spend and drive revenue growth.

Data Sources & Preparation
The analysis was performed on a simulated dataset provided by my educational institution, meticulously designed to mirror real-world marketing campaign data. This dataset included comprehensive metrics such as sales figures, ad spend, campaign specifics (name, type, channel), customer engagement metrics (comments, shares, likes, conversions), geographical information, and time-series data.

Key Data Preparation Steps:

Data Acquisition: The raw data was imported into Power BI, typically from CSV format.

Data Dictionary Understanding: A marketing campaign data dictionary was utilized to ensure a thorough understanding of all metrics and dimensions.

Calendar Table Creation: A robust Date Dimension Table (Calendar Table) was created in Power BI using DAX functions (CALENDARAUTO). This table was instrumental in extracting Year, Month, Month Name, and Quarter columns, enabling flexible time-intelligence calculations and filtering.

Relationship Management: A "perfect relationship" was established between the Calendar Table and the core marketing campaign data, ensuring accurate and dynamic data filtering across all time dimensions.

Tools & Technologies
Microsoft Power BI Desktop: Utilized extensively for:

a)Advanced Data Modeling: Creating and managing relationships, including the crucial Date Dimension Table.

b)Sophisticated DAX Calculations: Developing complex measures for KPIs, Month-over-Month changes, and ROAS.

c)Interactive Dashboard Creation: Designing and implementing the multi-page, interactive dashboard.

d)Data Transformation & Cleaning: Performing necessary data cleaning and shaping within Power Query.

##Key Features & Analysis Performed
The Power BI dashboard provides a multi-faceted and interactive view of campaign performance, structured across three main pages:

*Overall Campaign Analysis
High-Level KPIs: Displays aggregated Net Sales, Total Ad Spend, Total Sales, and Conversion Rate% across all campaigns.

Channel-Specific Performance: Offers a side-by-side comparison of Facebook, Instagram, and Pinterest, detailing Net Sales, Total Sales, Total Ad Spend, Conversion Rate%, Total Comments, Total Shares, and Total Likes for each. This allows for immediate identification of top-performing and underperforming channels.

![Screenshot 2025-07-09 170204](https://github.com/user-attachments/assets/2b1d9092-617b-4aa1-89c2-0f8dc0fc29f4)

*Monthly Campaign Analysis
Time-Series Tracking: Presents Net Sales, Total Sales, Total Ad Spend, and ROAS on a monthly basis.

Month-over-Month (MoM) Changes: Crucially, includes MoM percentage changes for all key metrics, enabling quick assessment of trends and performance shifts over time.

Channel-Wise Monthly Breakdown: Provides a granular view of monthly performance for each channel, highlighting seasonal impacts and specific monthly successes or challenges.

![Screenshot 2025-07-07 115202](https://github.com/user-attachments/assets/7c2d3a25-db44-4351-baea-1e3a8091f938)


*Detailed Campaign Analysis
Granular Data Table: Features a comprehensive matrix table allowing drill-down into Channel and City/Location.

Segmented Metrics: Displays Total Sales, Total Ad Spend, Net Sales, ROAS, Conversion Rate%, Total Comments, Total Conversions, Total Likes, and Total Shares for each specific segment, enabling deep-dive analysis into particular ad types, campaigns, and geographical regions.

![Screenshot 2025-07-09 170313](https://github.com/user-attachments/assets/14304bf2-61cb-42e9-99a3-512e850a597f)

Interactive Filters:
The dashboard incorporates highly interactive slicers for Ad Type (Collection, Discount), City/Location (Bengaluru, Delhi, Mumbai), Campaign (Spring, Summer, Winter), and Month Name. These filters empower users to perform dynamic, self-service analysis and explore specific data segments.

Design & User Experience:
Designed with a strong focus on "beautification and simplification," the dashboard ensures key insights are easily digestible for business users. This includes strategic use of card visuals for prominent KPIs, carefully adjusted visual padding and alignment, and the integration of channel icons (PNGs) for enhanced visual appeal and recognition.

##Key Insights & Findings
Based on the comprehensive analysis, several critical insights were identified for Silvercraft Company:

Pinterest's Exceptional Efficiency: Pinterest consistently demonstrated the highest Conversion Rate% (26.63% overall) and ROAS (e.g., 22.27 in December), generating significant Net Sales with the lowest Total Ad Spend. This indicates it is the most efficient channel for converting ad spend into revenue.

Facebook's Engagement vs. Conversion: Facebook excelled in driving engagement (Total Comments, Total Shares, Total Likes), showing strong brand reach. However, its Conversion Rate% was comparatively lower (18.77%). This suggests a potential "bias" in ad spend towards Facebook that may not align with conversion efficiency.

Significant Monthly Volatility: The analysis revealed considerable Month-over-Month fluctuations across all channels. While the overall trend for December showed declines in sales and ad spend, Facebook notably achieved positive MoM growth in Net Sales and ROAS. Conversely, Instagram and Pinterest saw large volume drops but surprisingly improved their ROAS in December, indicating highly efficient, albeit reduced, spending.

Geographical Performance Disparities: Performance varied significantly by City/Location for specific channels and ad types. For example, Pinterest's Discount ads in Bengaluru and Delhi showed exceptionally high ROAS (e.g., 44.75), highlighting localized opportunities.

Ad Type Effectiveness: The ability to filter by Ad Type (Collection vs. Discount) allowed for identifying which ad strategies yielded better returns in specific contexts.

Recommendations
Based on these insights, the following actionable recommendations are proposed for Silvercraft Company:

Strategic Ad Spend Reallocation: Reallocate a larger portion of the marketing budget towards Pinterest, leveraging its proven high ROAS and Conversion Rate% to maximize overall campaign efficiency.

Optimize Facebook for Conversions: While Facebook is strong for brand engagement, focus on refining calls to action, landing page experiences, and targeting strategies for Facebook campaigns to improve its conversion efficiency.

Dynamic Seasonal Strategy: Develop agile campaign strategies that adapt to monthly performance trends. Investigate the drivers behind significant MoM swings (e.g., Instagram's December performance) to replicate successes and mitigate future declines.

Localized Campaign Execution: Utilize the granular city-level insights to tailor campaigns and ad spend more effectively to specific geographical markets (Bengaluru, Delhi, Mumbai), capitalizing on regional strengths.

Continuous A/B Testing: Continue A/B testing various ad types and creatives to refine strategies and identify the most impactful campaign elements for different channels and target audiences.

.
├── Marketing Campaign - data.csv        # Raw/Cleaned dataset used for analysis
├── Marketing Campaign - dictionary.csv  # Data dictionary for understanding metrics
├── Silvercraft AdCampaign.pbix          # Power BI project file
├── Snapshots - Silvercraft Dashboard/   # Folder containing dashboard screenshots
│   ├── Screenshot 2025-07-09 170204.png # Overall Campaign Analysis screenshot
│   ├── Screenshot 2025-07-07 115202.png # Monthly Campaign Analysis screenshot
│   └── Screenshot 2025-07-09 170313.png # Detailed Campaign Analysis screenshot
└── README.md                            # Project documentation (this file)

Challenges & Solutions
Throughout this project, I encountered and overcame several challenges, strengthening my analytical and technical skills:

Challenge: Ensuring Accuracy and Robustness of Time-Series Calculations.

What i did: Meticulously designed and implemented complex DAX formulas for Month-over-Month changes (e.g., NetSales_MoMChange, ROAS_MoMChange). This involved careful handling of previous period calculations and edge cases like initial months or data gaps to ensure precise and reliable trend analysis.

Challenge: Establishing a Flexible and Accurate Data Model for Time Intelligence.

What i did: Built a dedicated Calendar Table using DAX's CALENDARAUTO function and established a "perfect relationship" with the core marketing data. This foundational step was critical for enabling dynamic date filtering and accurate time-intelligence functions across the entire dashboard.

Challenge: Balancing Comprehensive Detail with Dashboard Clarity and User Experience.

What i did: Adopted a strategic design approach, presenting high-level summaries through intuitive card visuals on dedicated overview pages. For granular exploration, a detailed matrix table with drill-down capabilities was implemented on a separate page, allowing users to delve into specifics without cluttering the main views. Applied rigorous formatting standards ("beautification and simplification") including consistent sizing, optimized visual padding, and appropriate currency display to enhance readability and visual appeal.

Future Enhancements
Integrate data from additional marketing channels (e.g., Email Marketing, Google Ads, SEO performance).

Implement predictive modeling to forecast future campaign performance and optimize budget allocation.

Conduct deeper customer segmentation analysis based on campaign engagement and purchase behavior.

Develop a dynamic budget allocation model based on projected ROAS and conversion rates.

Incorporate A/B testing results directly into the dashboard for continuous optimization insights.

Contact
[Kartik Dhote]

LinkedIn: [https://www.linkedin.com/in/kartikdhote/]

GitHub: [https://github.com/kartikdhote]

