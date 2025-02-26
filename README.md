🛍️ Amazon Potential Analyzer 🚀
Unlocking Amazon Europe for Danish Businesses
📌 Problem Statement
Many Danish businesses struggle with unsold stock and lack insights into selling 
on Amazon Europe.
They need data-driven insights to assess market potential and identify the 
best opportunities before making a move.

🎯 Target Audience
Danish companies considering expansion to Amazon.
Manufacturers with excess inventory who want to reach new markets.
E-commerce entrepreneurs looking for data-driven Amazon insights.
💡 Solution Overview
Amazon Potential Analyzer is a Shiny dashboard that helps businesses evaluate 
Amazon market potential by analyzing real sales data from:
✅ Amazon Seller Central – Sales performance, product rankings, 
and profitability data.
✅ Helium 10 – Market trends, competitor analysis, keyword insights, 
and sales forecasts.

With this app, Danish businesses can make smarter, data-driven decisions
about selling on Amazon.

⚙️ Features
📊 Market Demand Analysis – View Amazon trends, best-selling products,
and seasonality.
🔎 Competitor Insights – Analyze competitors' pricing, reviews, and market share.
💰 Profitability Estimator – Calculate revenue vs. costs based on
real Amazon sales data.
📌 Step-by-Step Action Plan – Get a roadmap for launching successfully.

🛠️ How to Set Up & Run the App
📌 Prerequisites
Before running the app, make sure you have:
✅ R and RStudio installed.
✅ Required R packages: shiny, tidyverse, DT, shinydashboard, httr, jsonlite, etc.
✅ Amazon Seller Central API access (or manual CSV exports).
✅ Helium 10 Data (via API or CSV uploads).

📌 Running the App

1️⃣ Clone the repository

git clone https://github.com/juca5Dania/Amazon-Potential-Analyzer.git
cd Amazon-Potential-Analyzer

2️⃣ Open RStudio & Load the App

shiny::runApp()

3️⃣ The app will open in your browser! 🎉

📊 Data Sources
Amazon Seller Central API – Provides real-time sales data, rankings,
and profitability insights.
Helium 10 API – Used for market research, competitor analysis, and keyword demand.
CSV Imports – Users can manually upload exported reports from Amazon Seller
Central & Helium 10 if API access is unavailable.
🔐 Security & Authentication
API Key Protection:
If using Helium 10 API or Amazon Seller Central API, API keys will be stored
securely in .Renviron instead of hardcoding them.
User Authentication (Future Plan):
If the app contains sensitive business data, we may implement authentication
using shiny-auth0 or a password-protected dashboard.
📜 Roadmap (Upcoming Features)
✅ Step 1: GitHub repository setup.
✅ Step 2: Create a wireframe for the app layout.
🔄 Step 3: Develop the core Shiny features.
🔄 Step 4: Implement Helium 10 API and Amazon Seller Central data integration.
🔄 Step 5: Deploy the app on shinyapps.io and ensure security.