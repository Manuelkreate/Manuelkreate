# Hi, I'm Emmanuel. I throw hands with data. 📊
I more than just write queries; I hunt for the "why" behind the numbers. My journey into data started with a simple curiosity about how systems work and evolved into a passion for uncovering the hidden patterns that drive business decisions.

---

### 🛠️ My Toolbox
* **The Languages:** SQL (Server/Postgres/BigQuery), Python.
* **The Visuals:** Power BI, Excel.
* **The Engineering:** dbt, GitHub Actions, Google Cloud Platform.
* **Strategic Focus:** Moving past surface-level totals to focus on profit margins, asset utilization, and customer stickiness.

---

### 🚀 Featured Investigations (My Projects)

#### [⚙️ Portfolio Risk Engine](https://github.com/Manuelkreate/portfolio-risk-engine)
**The Story:** Most investors track what their assets are worth. Few track whether the risk they're taking is actually worth the return. I built an automated data pipeline that answers that question — every night, automatically.

* **The Architecture:** Medallion pipeline (Bronze → Silver → Gold) in BigQuery, managed entirely by dbt. Raw prices land in Bronze, get cleaned and deduplicated in Silver, and produce rolling volatility, Sharpe Ratios, and position size recommendations in Gold — across 20, 60, and 90 day windows.
* **The Insight:** Gold (GC=F) had the best Sharpe Ratio across all windows, yet the volatility parity model recommended putting up to 40% of the portfolio in SPY. Two different questions — return efficiency vs. wealth preservation — answered simultaneously by the same pipeline.
* **The Technicals:** Python + yfinance for ingestion, dbt for transformations, GitHub Actions for nightly automation, Power BI with DirectQuery for a live dashboard. 9/9 dbt data tests passing.

#### [💳 Fintech CLV & Churn Prediction](https://github.com/Manuelkreate/Churn-Analysis-Project)
**The Story:** Analyzing 198,576 customers to find the "Retention Drop-off" point. I discovered that retention steeply declines after the first transaction, but customers who hit **5 total transactions** become significantly more loyal.

* **The Insight:** Consistent frequency (Total Transactions) is the most critical factor, contributing to 58% of the model's predictive power.
* **The Technicals:** Built a Random Forest Classifier with a **0.78 Recall** for churn, ensuring high-risk users are identified before they exit the ecosystem.

#### [📈 Fund-ify Growth Strategy](https://github.com/Manuelkreate/Fund-ify-Dashboard)
**The Story:** Developed a strategic dashboard to transition Fund-ify from volume tracking to sustainable growth. I mapped the service portfolio into a **Growth Quadrant** to identify "Habit Builders" for cross-selling and "Underperformers" for re-evaluation.

* **The Insight:** Friction and growth are inversely related — reducing friction in high-impact services like Lending and Airtime is critical for value creation.
* **The Action:** Built a **Friction Action Matrix** to pinpoint the exact service-region pairs causing the highest user frustration for immediate technical stabilization.

---

### 🌱 What's Next?
I'm currently sharpening my skills in advanced data modeling and looking for my next big challenge. When I'm not in a code editor, I'm likely gaming, listening to music, or following new scientific discoveries.

📫 **Let's Connect:** [LinkedIn](https://linkedin.com/in/emmanuel-adebowale) | [Email](mailto:emmyrex.a@gmail.com)

*"In God we trust, all others must bring data." – W. Edwards Deming*
