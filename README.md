# Anti-Money Laundering (AML) Transaction Analysis Dashboard


> **Download the full Power BI (.pbix) file [here](https://drive.google.com/drive/u/0/home?dmr=1&ec=wgc-drive-%5Bmodule%5D-goto&hl=en)**  
> (200 MB – hosted on Google Drive due to GitHub's size limit)


## Project Overview

This project is a data-driven investigation into suspected money laundering activity using transactional data. The goal is to identify laundering trends, high-risk entities, common laundering methods, and temporal patterns, and to provide actionable recommendations for AML compliance and enforcement teams.

The project uses Power BI to visualize insights and DAX to power custom KPIs, measures, and anomaly detection logic.

---

## Dataset Summary

- **Total transactions analyzed**: 10,000,000  
- **Laundered transactions**: 9,873  
- **Timeframe**: Multi-year (Exact date range not disclosed)  
- **Data fields** include:
  - Sender/Receiver Bank Info
  - Country
  - Payment Method
  - Transaction Amount
  - Date
  - Laundering flag (`Is_laundering_money`)

---

## Key Insights

- **UK accounts** are involved in **93.7% of all laundered transactions**.
- **Cross-border payments** were the top laundering method, followed by **cash deposits** and **ACH**.
- **Structuring** (breaking large amounts into smaller transactions) was the most common tactic used.
- **Most laundering occurred from January to April**, with **peaks in June and July**, and a sudden drop in October.
- **£79 billion** was transacted overall; **£364 million** was confirmed laundered (~0.46%).
- The **largest single transaction** was **£12.6 million**, sent and received within UK.

---

## Technologies Used

- **Power BI** for data modeling, visualization, and KPI dashboards
- **DAX** (Data Analysis Expressions) for calculated measures and advanced logic
- **Microsoft Excel / CSV** as data source (simulated/cleansed for analysis)
- Optional: Python for data preprocessing (not included in this repo)

---

## Recommendations

- Apply **enhanced monitoring to UK-UK transactions**, especially involving high-value amounts or unusual frequency.
- Implement rules to detect **structuring patterns**, e.g., multiple transactions just below thresholds.
- Increase scrutiny on **cross-border transactions** and monitor **sender/receiver risk scores**.
- Focus AML efforts on **Q1 and March**, where activity peaks significantly.
- Expand data coverage to include **wire transfers, SWIFT, PayPal, and crypto** to close visibility gaps.
- Recommend **tighter enforcement around UK LLPs and LTDs**, often exploited to hide beneficial ownership.

---

## Future Improvements

- Incorporate real-time transaction scoring
- Add geolocation-level analysis (city/branch)
- Expand detection of layering and integration phases
- Include regulatory policy comparison by jurisdiction

---

## Dashboard Preview

![image](https://github.com/user-attachments/assets/e52d2c54-fd1c-4b74-8e95-c334aa1a4d64)
![image](https://github.com/user-attachments/assets/116e215b-e40c-4f7c-bb29-7b51df8110bd)
![image](https://github.com/user-attachments/assets/580d6492-1b6b-49d6-bf9e-564a8760ad9f)
![image](https://github.com/user-attachments/assets/5ce502f3-35f6-4c9e-8786-67fe9725fbac)


---

## Disclaimer

This project uses **anonymized data** and is intended for **educational and analytical purposes only**. It does not reflect real-world financial activity or confidential client information.

---

## Contact

For questions, suggestions, or collaborations, feel free to [open an issue](https://github.com/TheDucky-2) or contact me directly.

