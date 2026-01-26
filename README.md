# 🏥 U.S. Hospital Quality Analysis (2025)

[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)](https://www.tableau.com/)
[![Data Analysis](https://img.shields.io/badge/Data_Analysis-Healthcare-blue.svg)](https://github.com/Ani-107/Hospitalhealth-capstone-project)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**📌 Capstone Project** - Comprehensive analysis of 5,421 U.S. hospitals to understand how quality ratings vary by state, ownership type, and hospital structure. The goal is to uncover systemic patterns in healthcare performance and highlight where improvement opportunities exist nationwide.

---

## 🎯 Problem Statement

Healthcare quality in the U.S. varies widely, but it's not always clear why.

This project answers three key questions:

1. **How are hospitals distributed across national quality tiers?**
2. **How do average hospital ratings vary by state?**
3. **How does hospital ownership (Non-Profit, For-Profit, Government) impact quality outcomes?**

---

## 📊 Key Insights

### 1️⃣ Quality Rating Distribution

- Most U.S. hospitals fall into the **Average (3-star)** and **Above Average (4-star)** tiers
- **Excellent (5-star)** hospitals represent a relatively small segment
- A noticeable number of hospitals remain **Not Rated**, especially smaller or rural facilities

**Insight:** While care is generally stable nationwide, there is significant room for improvement in achieving top-tier performance, particularly outside major urban centers.

### 2️⃣ State-Level Quality Performance (LoD Analysis)

- States such as **Texas, California, Ohio, Pennsylvania, and Florida** show higher average hospital ratings
- These states benefit from larger hospital networks and stronger healthcare infrastructure
- More rural states display lower or more variable averages

**Technical Note:** A `FIXED` Level of Detail (LoD) expression was used to calculate state averages, ensuring results remain stable even when filters change.

### 3️⃣ Ownership vs Quality Outcomes

- **Non-Profit hospitals** consistently outperform For-Profit and Government-owned hospitals
- They show stronger representation in 4-star and 5-star categories
- **For-Profit hospitals** display higher variability
- **Government hospitals** show mixed results, often influenced by funding and regional demand

**Insight:** Ownership structure plays a significant role in healthcare quality outcomes, with Non-Profit systems delivering more reliable performance.

### 4️⃣ Hospital Type Performance

- **Acute Care hospitals** perform more consistently across states
- **Critical Access hospitals** show wider variability due to rural location and resource constraints

---

## 🧠 Analytical Approach

### Calculated Fields

- **Quality Tier**: Below Average, Average, Above Average, Excellent, Not Rated
- **Ownership Category**: Non-Profit, For-Profit, Government

### Level of Detail (LoD) Expression

```tableau
FIXED [State] : AVG([Hospital Overall Rating])
```

Used to maintain consistent state-level benchmarks.

### Visualizations

- Quality tier distribution
- State-wise average quality comparison
- Ownership vs quality performance
- Hospital type analysis across top states

---

## 🛠️ Tools & Technologies

- **Tableau Desktop** - Dashboard creation & data visualization
- **Calculated Fields & LoD Expressions** - Reliable aggregation logic
- **U.S. Hospital Quality Dataset** - CMS-based data source
- **Data Analysis** - Statistical analysis and pattern recognition

---

## 📂 Project Structure

```
.
├── Hospital_2025.csv                    # Source dataset
├── hospital health capstone project.twb # Tableau workbook
├── README.md                            # This file
└── LICENSE                              # MIT License
```

---

## 🚀 Getting Started

### Prerequisites

- Tableau Desktop (for viewing/editing the workbook)
- Tableau Public (free alternative for viewing)

### Viewing the Dashboard

1. **Clone the repository:**
```bash
git clone https://github.com/Ani-107/Hospitalhealth-capstone-project.git
cd Hospitalhealth-capstone-project
```

2. **Open the Tableau workbook:**
   - Open `hospital health capstone project.twb` in Tableau Desktop
   - Or upload to Tableau Public for online viewing

### Data Source

The analysis uses the **U.S. Hospital Quality Dataset (2025)** based on CMS (Centers for Medicare & Medicaid Services) data, containing:
- 5,421 hospitals
- Quality ratings (1-5 stars)
- Ownership types
- Hospital types
- Geographic distribution

---

## 📈 Final Conclusion

Hospital quality in the U.S. is not evenly distributed. It varies significantly based on:

- **State** - Geographic location and infrastructure
- **Ownership structure** - Non-Profit, For-Profit, Government
- **Hospital type** - Acute Care vs Critical Access

**Key Findings:**
- Non-Profit and Acute Care hospitals contribute most strongly to high-performing states
- Critical Access and some For-Profit hospitals face structural challenges
- These insights point toward opportunities for targeted policy intervention, resource allocation, and healthcare system improvements

---

## 🎓 Project Context

This project was completed as part of a **Data Analytics Capstone** focusing on:
- Healthcare data analysis
- Statistical pattern recognition
- Data visualization best practices
- Policy-relevant insights

---

## 📊 Dashboard Features

- **Interactive Filters**: Explore data by state, ownership, and hospital type
- **Dynamic Calculations**: Real-time aggregation using LoD expressions
- **Comparative Analysis**: Side-by-side quality comparisons
- **Visual Storytelling**: Clear narrative flow from problem to insights

---

## 🤝 Contributing

Contributions are welcome! Areas for improvement:
- Additional analysis dimensions
- Enhanced visualizations
- Updated datasets
- Documentation improvements

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Ani-107 (Anirudh Yadav Mekala)**
- GitHub: [@Ani-107](https://github.com/Ani-107)
- Profile: [View Profile](https://github.com/Ani-107)

---

## 🙏 Acknowledgments

- **CMS (Centers for Medicare & Medicaid Services)** - For providing the hospital quality dataset
- **Tableau** - For powerful data visualization tools
- **Healthcare Data Community** - For ongoing research and insights

---

## 📚 Related Projects

- [Stocks Performance Dashboard](https://github.com/Ani-107/stocks-performance-tableau-dashboard_2025) - Financial analytics dashboard
- [AI Multi-Agent Financial Analyst](https://github.com/Ani-107/Ai-multi-Agent-fin-analyst) - AI-powered financial analysis

---

<div align="center">

**Built with ❤️ for Healthcare Data Analysis**

⭐ Star this repo if you find it helpful!

</div>

