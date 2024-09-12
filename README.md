
# Data_Professional_Analysis

### Dashboard Link: https://github.com/Madhav-Analyst/Data_Professional_Analysis

![Dashboard_Picture](https://github.com/user-attachments/assets/7ba8ba3b-7fff-46c3-b420-6e3a3b258176)

#### Problem Statement
This dashboard provides insights into the current trends in popular programming languages. It helps developers, recruiters, and organizations understand which programming languages are in high demand, enabling them to make informed decisions about hiring, training, and future development strategies.

The dashboard aggregates data on the usage, demand, and growth trends of various programming languages across different industries. It also includes key metrics like job openings requiring specific languages, popularity in open-source projects, and community engagement.

Given the fast-changing technology landscape, it is essential to stay updated on which languages are emerging as dominant players. This dashboard provides a comprehensive view of these trends.

### Steps Followed
Step 1: Load data into Power BI Desktop from a dataset (e.g., Stack Overflow developer survey, GitHub, job market data).

Step 2: Open Power Query Editor and ensure data quality by checking column distribution, column quality, and column profile options.

Step 3: Clean the data by handling missing values and removing irrelevant columns. For example, columns like "Unused Libraries" were dropped.

![Screenshot 2024-09-12 181740](https://github.com/user-attachments/assets/0987efc1-5e53-4dc5-ba38-d6c68904bb6d)


Step 4: Created calculated columns to group languages by their category (e.g., general-purpose, mobile development, web development).

Step 5: Used DAX to create new measures for key metrics such as:

✒️Total Job Postings: Count of job openings requiring each language.

✒️Total Repositories: Sum of GitHub repositories associated with each language.

✒️Community Engagement Score: Calculated based on forum activity and Q&A volume for each language.

![Screenshot 2024-09-12 181722](https://github.com/user-attachments/assets/bf08e662-ad40-46cd-944f-0718156c60b4)

Step 6: Visualized language usage trends using line charts to show growth over time. Data segmented by year, industry, and application type.

Step 7: Added slicers to filter data by region, application type (e.g., web development, AI/ML), and language proficiency level.

Step 8: Created pie charts and bar graphs representing the distribution of programming languages across various industries (e.g., healthcare, fintech, e-commerce).

Step 9: Added KPIs for most popular languages based on community engagement, job demand, and overall growth rate. Metrics include:

Top 5 Programming Languages by growth rate
Most In-Demand Languages in the job market

Fastest Growing Languages in open-source projects

Step 10: Used a matrix visualization to compare languages across various parameters, such as performance, community support, and ease of learning.

Step 11: Included a tree map to represent language popularity by the number of developers using each language globally.

Step 12: Published the report to Power BI Service for easy access and sharing across teams and stakeholders.

### Insights
The dashboard provides key insights into the state of programming languages:

#### ✒️Most In-Demand Languages (2024)
📍Python: 35% of job postings

📍JavaScript: 30% of job postings

📍Java: 20% of job postings

📍C#: 10% of job postings

📍Go: 5% of job postings

#### ✒️Fastest Growing Languages

📍Rust: 40% year-over-year growth

📍TypeScript: 30% growth

📍Kotlin: 25% growth

📍Swift: 20% growth

![Screenshot 2024-09-12 181735](https://github.com/user-attachments/assets/db2b985b-0ccf-42be-8d88-8b1029170091)


#### ✒️Language Usage Across Industries

📍Healthcare: Python (45%), Java (20%), JavaScript (15%)

📍Fintech: Python (40%), C# (30%), Go (20%)

📍E-commerce: JavaScript (50%), Python (25%), PHP (15%)
#### ✒️Community Engagement
📍Python: Highest community engagement with 50% of active Q&A posts.

📍JavaScript: Strong open-source project contribution, with over 40% of repositories created in the last year.

📍Rust: Emerging as a language with high satisfaction rates among developers (over 90% positive feedback).

#### ✒️Conclusion
This dashboard enables a clear understanding of which programming languages are trending, helping stakeholders make data-driven decisions about learning, hiring, and developing in specific languages. The data reveals Python’s dominance, followed by the growing popularity of Rust and TypeScript, making them key languages to watch in 2024.
