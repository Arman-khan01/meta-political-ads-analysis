📊 Meta Ad Delivery & Market Saturation Analysis
Author: Arman Khan

Course: INT 375 (Data Science Minor) - Lovely Professional University



An end-to-end Data Engineering and Business Intelligence pipeline that extracts, cleans, and analyzes live political ad data from the Meta Ad Library API to determine the true cost-efficiency of digital election campaigns.

🎯 Project Overview
Political campaigns spend millions of rupees on digital advertising, often operating under the assumption that a massive budget guarantees massive reach. This project tackles the problem of Ad Delivery Inefficiency and Market Saturation.

Instead of using a pre-cleaned Kaggle dataset, this project pulls live data directly from the Meta API to mathematically prove whether sheer financial volume dictates campaign success, or if algorithmic targeting and organic engagement are more critical to Return on Ad Spend (ROAS).

⚙️ Tech Stack & Tools
Language: Python 3.x

Data Extraction & API: requests, json

Data Engineering & ETL: pandas, numpy, re (Regex)

Statistical Analysis & ML: scipy.stats (Z-Test), scikit-learn (Linear Regression)

Data Visualization (Python): matplotlib, seaborn

Business Intelligence (Frontend): Power BI (DAX, Power Query)

🚀 Key Features & Pipeline Workflow
1. Data Extraction (The Backend)

Built Python scripts to connect to the official Meta Ad Library API.

Extracted over 10,000 rows of live political ad metadata.

Handled API pagination, rate limits, and deprecation errors.

2. Data Engineering & Pre-processing (ETL)

Parsed highly nested JSON dictionaries and messy array strings (e.g., estimated_audience_size, publisher_platforms).

Utilized custom functions and conditional mapping (np.where) to transform raw API responses into a clean, structured 22-column continuous dataset.

3. Statistical Hypothesis Testing

Conducted a One-Sample Z-Test to compare actual political ad spends against a theoretical micro-budget baseline (₹100), mathematically proving the massive financial scale of the digital ad ecosystem.

4. Predictive Modeling (Linear Regression)

Trained a Linear Regression model (R² ≈ 0.96) to predict future ad impressions based on historical financial spend, establishing a mathematical baseline for expected campaign reach.

5. Business Intelligence Dashboard

Developed a fully interactive, SaaS-style Power BI dashboard mapping out Cost Per Mille (CPM), demographic targeting biases, and platform saturation bottlenecks.

💡 Key Strategic Insights
The "Volume vs. Viral" Disconnect: Sheer budget volume does not guarantee reach. Scatter plot and CPM analysis reveal that micro-budget campaigns with highly engaging content often beat multi-million rupee campaigns.

The Saturation Bottleneck: Campaigns targeting massive audiences (e.g., 100M+ users) frequently experience severe budget dilution and low actual delivery compared to their targets.

Platform Demographics: Financial distribution proves a heavy strategic bias toward younger demographics (18-34) on Instagram over legacy Facebook feeds.
