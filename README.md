# bank-transaction-analysis

This repository contains the full analytical workflow for a bank transaction dataset — from the Excel data cleaning to a  Power BI dashboard. The project answers six core business questions about channel performance, customer spending behaviour, account wealth by age group, transaction timing, and security risk.

## The Six Business Questions and Answers

Q1	Which channel drives the highest average transaction amount?	ATM — $307.72

Q2	At what hour do transactions peak — does it differ by channel?	4 PM (Hour 16), all channels identical

Q3	How does account balance vary by age group?	Peaks at Middle Age ($6,583), not Old age

Q4	What channel do different occupations prefer?	All groups are surprisingly uniform — no channel dominates

Q5	How many transactions had >1 login attempt, and how large were they?	122 (4.9%) — avg $289, BELOW the overall mean

Q6	Which occupation spends the most per transaction?	Student — $313.22 (counterintuitive outlier)

## Key Findings
ATM leads on per-transaction value ($307.72) — not because ATM users are wealthier, but because ATM transactions are intentional. Customers arrive knowing exactly what they need.

Transaction volume drops 71% between 4 PM and 6 PM. All three channels decline identically — the bank has no meaningful evening engagement despite serving a digitally capable customer base.

Middle-aged customers hold the highest balances ($6,583), not older customers. The wealth arc peaks in peak earning years, not retirement.

Students spend the most per transaction ($313.22) — outspending doctors and engineers. When students transact, the amounts are large: tuition, accommodation, equipment. Their per-transaction average is misleadingly hidden by lower overall transaction frequency.

Students use Online the least — a paradox for a digitally native demographic. This points to a product design gap, not a demographic preference.

High-risk login transactions average $289 — below the dataset mean. A standard amount-based fraud detection system would miss all 122 of them. Behaviour, not amount, is the correct detection signal.
