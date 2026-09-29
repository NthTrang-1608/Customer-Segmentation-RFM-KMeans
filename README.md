E-Commerce Customer Segmentation: RFM Analysis & K-Means Clustering.
An end-to-end data analytics project combining statistical modeling and machine learning to segment e-commerce customer, enabling personalized data-driven marketing strategies and maximizing Customer Lifetime Value (CLV).
Excutive Summary:
In e-commerce, a "one-size-fits-all" marketing approach leads to high customer acquisition costs and low retention. This project processes transactional records (540,000+ rows) using Python and applies RFM Analysis coupled with K-Means Clustering (k = 4) to classify customers into actionable business segments. The insights are deployed into an interactive Power BI Dashboard to assist marketing teams in budgeting and campaign targeting.
Interactive Power BI Dashboard:
Key Business Metrics at a Glance
Total number of customers: 4,338
Total revenue (USD): $8.91M
Average purchase frequency (Orders/Customer): 4.27 orders/ customer.
Tech Stack & Methodology:
Language & Data Processing: Python (Pandas, NumPy)
Machine Learning & Preprocessing: Scikit-Learn (Log Transformation, StandardScaler, K-Means Clustering, Elbow Method & Silhouette Score)
Visualization & BI: Power BI, Matplotlib, Seaborn
RFM & K-Means Segmentation Breakdown
Segment | Share of customers | Revenue COntribution | Average order value | Behavioral Profile | Recommended Marketing action
VIP/ Champions | 16.5% | 64.9% ($5.78M) | $8,074 | High frequency, every recent purchases, substantial basket size. | VIP loyalty perks, early access to new releases, dedicated account support.
Potential Loyalists | 27.0% | 23.7% ($2.11M) | $1,803 | Moderate spending, regular repeat purchases with strong growth potential. | Upselling/ Cross-selling campaigns, loyalty tier incentives.
Recent/ New | 19.3% | 5.2% ($0.46M) | %552 | Purchased recently with low order frequency | Onboarding email series, 2nd-purchase discounts, social proof marketing.
At risk/ Hibernating | 37.2% | 6.2% ($0.55M) | $343 | Long inactive periods (>200 days), low engagement. | Win-back/ Reactivation discounts, automated re-engagement surveys.
Strategic marketing insights (Actionable ROI)
1. Pareto principle validated: The top 16.5% of customers (VIP/ Champions) drive almost 65% of total business revenue. Retention of this segment must be the top priority.
2. Growth opportunities: The Potential Loyalists segment represents 27% of the customer base. Nurturing 15-20% of them into VIPs can increase gross merchandise volume (GMV) by double digits.
3. Optimizing ad spend: Cease generic retargeting ads for At-Risk customers; instead, deploy cost-effective automated email win-back sequences to minimize CAC waste.
Repository structure:
├── Dashboard Customer_Segmentation.png   # Dashboard screenshot
├── rfm_segmented_customers.ipynb        # Jupyter Notebook with full analysis & ML pipeline
├── rfm_segmented_customers.csv          # Processed customer-level dataset
└── README.md                            # Project documentation & business report
How to run the project
1. Clone this repository:
git clone [https://github.com/NthTrang-1608/Customer-Segmentation-RFM-KMeans.git](https://github.com/NthTrang-1608/Customer-Segmentation-RFM-KMeans.git)
2. Install required dependencies:
pip install pandas numpy scikit-learn matplotlib seaborn
3. Run the Notebook:
Open rfm_segmented_customers.ipynb in Jupyter Notebook or Google Colab and run all cells sequentially.
