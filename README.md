# Hi, I'm Emmanuel. I throw hands with data. 📊
I more than just write queries; I hunt for the "why" behind the numbers. My journey 
into data started with a simple curiosity about how systems work and evolved into a 
passion for uncovering the hidden patterns that drive business decisions.

---

### 🛠️ My Toolbox
* **The Languages:** SQL (Server/Postgres/BigQuery), Python.
* **The Visuals:** Power BI, Excel.
* **The Engineering:** dbt, Apache Airflow, FastAPI, Google Cloud Platform, GitHub Actions.
* **Strategic Focus:** Moving past surface-level totals to focus on profit margins, 
asset utilization, and customer stickiness.

---

### 🚀 Featured Investigations (My Projects)

#### [🏥 Nigeria Maternal & Newborn Health Pipeline](https://github.com/Manuelkreate/maternal-health-pipeline)
**The Story:** Nigeria has the third highest maternal mortality rate in the world. 
The data to understand why exists across multiple disconnected sources — DHS surveys, 
conflict records, health expenditure indicators. I connected them into a 
production-grade pipeline and let the findings speak.

* **The Architecture:** End-to-end pipeline — Python ingestion into Google Cloud 
Storage, BigQuery warehouse, dbt Core transformations across staging, intermediate, 
and mart layers, Apache Airflow orchestration via Docker Compose, and a FastAPI 
serving layer with endpoints mapped to five research questions.
* **The Insight:** ANC attendance predicts neonatal survival more strongly than place 
of delivery. A wealthy woman in the North-West has worse odds than a poor woman in 
the South-East. The two highest-conflict states in Nigeria — Borno and Yobe — 
actually improved ANC attendance between 2018 and 2024. Most states didn't.
* **The Technicals:** 9 raw tables ingested, 3-layer dbt model, reliability flagging 
for statistically unstable estimates, population-weighted averages enforced end-to-end, 
five-page Power BI dashboard, full analytical report with documented methodology and 
limitations.

#### [⚙️ Portfolio Risk Engine](https://github.com/Manuelkreate/portfolio-risk-engine)
**The Story:** Most investors track what their assets are worth. Few track whether 
the risk they're taking is actually worth the return. I built an automated data 
pipeline that answers that question — every night, automatically.

* **The Architecture:** Medallion pipeline (Bronze → Silver → Gold) in BigQuery, 
managed entirely by dbt. Raw prices land in Bronze, get cleaned and deduplicated in 
Silver, and produce rolling volatility, Sharpe Ratios, and position size 
recommendations in Gold — across 20, 60, and 90 day windows.
* **The Insight:** Gold (GC=F) had the best Sharpe Ratio across all windows, yet the 
volatility parity model recommended putting up to 40% of the portfolio in SPY. Two 
different questions — return efficiency vs. wealth preservation — answered 
simultaneously by the same pipeline.
* **The Technicals:** Python + yfinance for ingestion, dbt for transformations, 
GitHub Actions for nightly automation, Power BI with DirectQuery for a live 
dashboard. 9/9 dbt data tests passing.

#### [💳 Fintech CLV & Churn Prediction](https://github.com/Manuelkreate/Fintech_CLV_Churn_Analysis)
**The Story:** Analyzing 198,576 customers to find the "Retention Drop-off" point. 
I discovered that retention steeply declines after the first transaction, but 
customers who hit **5 total transactions** become significantly more loyal.

* **The Insight:** Consistent frequency (Total Transactions) is the most critical 
factor, contributing to 58% of the model's predictive power.
* **The Technicals:** Built a Random Forest Classifier with a **0.78 Recall** for 
churn, ensuring high-risk users are identified before they exit the ecosystem.

#### [📈 Fund-ify Growth Strategy](https://github.com/Manuelkreate/customer-retention-and-health-analytics)
**The Story:** Developed a strategic dashboard to transition Fund-ify from volume 
tracking to sustainable growth. I mapped the service portfolio into a **Growth 
Quadrant** to identify "Habit Builders" for cross-selling and "Underperformers" for 
re-evaluation.

* **The Insight:** Friction and growth are inversely related — reducing friction in 
high-impact services like Lending and Airtime is critical for value creation.
* **The Action:** Built a **Friction Action Matrix** to pinpoint the exact 
service-region pairs causing the highest user frustration for immediate technical 
stabilization.

---

### 🌱 What's Next?
I'm currently sharpening my skills in advanced data modeling and looking for my next 
big challenge. When I'm not in a code editor, I'm likely gaming, listening to music, 
or following new scientific discoveries.

📫 **Let's Connect:** [LinkedIn](https://linkedin.com/in/emmanuel-adebowale) | 
[Email](mailto:emmyrex.a@gmail.com)

*"In God we trust, all others must bring data." – W. Edwards Deming*
