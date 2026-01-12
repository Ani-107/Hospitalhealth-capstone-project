# Hospitalhealth Quality Analysis (2025)-capstone-project

🏥 U.S. Hospital Quality Analysis (2025)
📌 Project Overview

This project analyzes 5,421 U.S. hospitals to understand how quality ratings vary by state, ownership type, and hospital structure.
The goal is to uncover systemic patterns in healthcare performance and highlight where improvement opportunities exist nationwide.

The analysis is presented through an interactive Tableau dashboard, supported by calculated fields and Level of Detail (LoD) expressions to ensure consistent and reliable comparisons.

🎯 Problem Statement

Healthcare quality in the U.S. varies widely, but it’s not always clear why.

This project answers three key questions:

How are hospitals distributed across national quality tiers?

How do average hospital ratings vary by state?

How does hospital ownership (Non-Profit, For-Profit, Government) impact quality outcomes?

📊 Key Insights
1️⃣ Quality Rating Distribution

Most U.S. hospitals fall into the Average (3-star) and Above Average (4-star) tiers.

Excellent (5-star) hospitals represent a relatively small segment.

A noticeable number of hospitals remain Not Rated, especially smaller or rural facilities.

Insight:
While care is generally stable nationwide, there is significant room for improvement in achieving top-tier performance, particularly outside major urban centers.

2️⃣ State-Level Quality Performance (LoD Analysis)

States such as Texas, California, Ohio, Pennsylvania, and Florida show higher average hospital ratings.

These states benefit from larger hospital networks and stronger healthcare infrastructure.

More rural states display lower or more variable averages.

Technical Note:
A FIXED Level of Detail (LoD) expression was used to calculate state averages, ensuring results remain stable even when filters change.

3️⃣ Ownership vs Quality Outcomes

Non-Profit hospitals consistently outperform For-Profit and Government-owned hospitals.

They show stronger representation in 4-star and 5-star categories.

For-Profit hospitals display higher variability.

Government hospitals show mixed results, often influenced by funding and regional demand.

Insight:
Ownership structure plays a significant role in healthcare quality outcomes, with Non-Profit systems delivering more reliable performance.

4️⃣ Hospital Type Performance

Acute Care hospitals perform more consistently across states.

Critical Access hospitals show wider variability due to rural location and resource constraints.

🧠 Analytical Approach

Calculated Fields

Quality Tier (Below Average, Average, Above Average, Excellent, Not Rated)

Ownership Category (Non-Profit, For-Profit, Government)

Level of Detail (LoD) Expression

FIXED [State] : AVG([Hospital Overall Rating])


Used to maintain consistent state-level benchmarks.

Visualizations

Quality tier distribution

State-wise average quality comparison

Ownership vs quality performance

Hospital type analysis across top states

🛠 Tools Used

Tableau – Dashboard creation & data visualization

Calculated Fields & LoD Expressions – Reliable aggregation logic

U.S. Hospital Quality Dataset (CMS-based)

📈 Final Conclusion

Hospital quality in the U.S. is not evenly distributed.
It varies significantly based on:

State

Ownership structure

Hospital type

Non-Profit and Acute Care hospitals contribute most strongly to high-performing states, while Critical Access and some For-Profit hospitals face structural challenges. These insights point toward opportunities for targeted policy intervention, resource allocation, and healthcare system improvements.
