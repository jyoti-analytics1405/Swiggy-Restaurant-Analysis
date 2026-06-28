# Swiggy-Restaurant-Analysis
Excel-based Data Analysis on 8,673 Swiggy restaurants across 9 Indian cities | Power Query • Pivot Tables • Dashboard • Data Cleaning
🍕 Swiggy Restaurant Analysis — My First Excel Project
Hey there! 👋 Welcome to my very first data analytics project.

I'm Jyoti — a BSc Life Science graduate who is currently transitioning into Data Analytics. This project is part of my learning journey at Physics Wallah, and honestly, it taught me SO much more than just Excel formulas!


💡 Why This Project?
When I started learning data analytics, I wanted to work on something real — not just dummy numbers. Swiggy is something we all use daily, so analyzing restaurant data from 9 Indian cities felt exciting and relatable. I wanted to answer questions like:

Which city has the most restaurants on Swiggy?
What cuisines are most popular where?
Do expensive restaurants get better ratings?
How does delivery time vary across cities?

📊 Dataset Overview
Detail
Info
Total Restaurants
8,673
Cities Covered
9
Total Columns
10
Source
Swiggy Public Data
Cities: Bangalore • Hyderabad • Mumbai • Pune • Kolkata • Delhi • Chennai • Ahmedabad • Surat


🗂️ Project Structure
SWIGGY-RESTAURANT-ANALYSIS/
│
├── 📋 Raw Dataset → Original uncleaned data (8673 rows)
├── 🧹 Clean Data → Cleaned + new columns added
├── 🏙️ Summary of City → City-wise price stats & rankings
├── 🍽️ Food Performance → Top cuisines, ratings pivot table
├── 🚀 Cuisine Expanded → Power Query expanded cuisine data
├── ⭐ Delivery & Rating → Rating distribution analysis
└── 📈 Dashboard → Final interactive dashboard


🛠️ What I Did — Step by Step
1️⃣ Data Cleaning
Checked for missing values and duplicates
Fixed floating point errors in rating column
Added Price Flag column (valid/invalid)
Created Price Bucket — Budget / Mid / Premium
Extracted Primary Food Type from comma-separated cuisines
Added Delivery Time Bracket — Fast / Slow
2️⃣ City-wise Analysis
Compared Max, Min, Average price across 9 cities
Ranked cities by restaurant count
Created Price Bucket distribution per city
3️⃣ Food Category Performance
Used Power Query to expand comma-separated cuisine data
Built City × Cuisine heatmap using Pivot Table
Found top 10 cuisines by restaurant count
4️⃣ Delivery & Rating Analysis
Grouped ratings into ranges (1.0-1.9, 2.0-2.4, etc.)
Analyzed delivery time patterns
5️⃣ Dashboard
Built interactive dashboard with Slicers
Added KPI cards — Total Restaurants, Avg Rating, Avg Price, Avg Delivery Time
Created Dual-Axis Combo Chart (Average Price vs Restaurant Count)
Added Donut Chart for Price Bucket Distribution

🔍 Key Insights I Found
"Kolkata has the most restaurants (1,346) but one of the lowest average prices (₹362) — making it the most affordable food city on Swiggy!"
"Mumbai restaurants are the most expensive on average (₹393) but also have high restaurant count (1,275) — competitive market!"
"Surat has the least restaurants (511) and lowest average price (₹270) — smallest but budget-friendly market."
"North Indian cuisine dominates across most cities — it's India's favorite food category on Swiggy!"
"Most restaurants (64%) fall in the Budget price category — Swiggy caters mostly to budget-conscious customers."

🧰 Tools & Skills Used
Tool/Skill
Used For
Microsoft Excel
Everything!
Power Query
Expanding comma-separated cuisine data
Pivot Tables
City × Cuisine heatmap, summaries
COUNTIF / XLOOKUP / IF
Data cleaning & categorization
Conditional Formatting
Heatmap visualization
Charts (Combo, Donut, Bar)
Dashboard visualizations
Slicers
Interactive filtering

📈 Dashboard Preview
The dashboard includes:
![Swiggy Dashboard](dashboard-screenshot.png)
✅ 4 KPI Cards
✅ Top 5 Cities Bar Chart (with City Slicer)
✅ Price Bucket Donut Chart
✅ Average Price vs Restaurant Count Dual-Axis Chart
✅ Rating Distribution Chart

🌱 What I Learned
This project was genuinely challenging — especially the Power Query part where I had to split comma-separated cuisine values into individual rows. It took multiple attempts but I figured it out!

I also learned that data is never clean in real life — and that's exactly what makes data analytics interesting. Every error taught me something new.


🙋‍♀️ About Me
I'm Jyoti, an aspiring Data Analyst currently learning Excel, SQL, Power BI, and Python from Physics Wallah. I come from a background in medical backend operations and social media management, and I'm now channeling all that experience into building a career in data.

This is just the beginning! More projects coming soon. 🚀


📬 Connect With Me



Made with ❤️ and lots of Excel errors that taught me everything! 😄
