# 📊 Client License Optimization & Risk Insights Dashboard

This project combines business intelligence and data science principles to identify underutilized software licenses and proactively flag at-risk clients in the mechanical software space. Built using Python and Power BI, it showcases how data can drive strategic account management.

## 🧠 Goals
- Optimize license usage across enterprise clients
- Detect early churn signals based on usage, support trends, and engagement
- Deliver actionable insights through visual dashboards

## 🛠️ Tools & Techniques
- Python (Pandas, Seaborn, Matplotlib)
- Power BI for interactive dashboards
- Data modeling with mock CSVs

## 🗃️ Data Overview
| Dataset             | Description                                 |
|---------------------|---------------------------------------------|
| CustomerProfile     | Client size, industry, contracts, licenses  |
| LicenseUsage        | User login logs by product and time         |
| SupportTickets      | Ticket volume and average resolution time   |
| EngagementData      | Meetings, demos, QBRs, follow-ups           |

## 📈 Key Features
- Tier segmentation based on license usage
- “Engagement score” combining qualitative customer activity
- Rule-based risk logic combining low usage, low engagement, and high support
- Idle license heatmaps, usage trends, and risk flags in dashboard

## 💡 Insights Generated
- 30% of purchased licenses idle across 4 major clients
- High support volume correlates with low engagement in 2 accounts
- 25% of clients flagged as “⚠️ At Risk” based on behavioral signals

## 🎯 Future Scope
- Add churn prediction models using Scikit-learn
- Live CRM/ERP integration with Power BI API connectors
- Expand to include ARR impact and upsell forecasting

---

⚙️ Project developed and maintained by [Parth Jani](#).  
📎 All data used is fictional and created for demonstration purposes.
