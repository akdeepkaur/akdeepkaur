<h1 align="center">Hey there, I'm Akdeep 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2E86C1&center=true&vCenter=true&width=600&lines=Finance+grad+turning+into+a+data+analyst+📊;Learning+Excel%2C+SQL+%26+Python+🐍;Turning+messy+data+into+clear+stories+✨;Kabaddi+runner-up.+Now+chasing+insights.+🏆" alt="Typing animation" />
</p>

<p align="center">
  <b>M.Com (EAFM)</b> · <b>B.Com (Finance)</b> · <b>Aspiring Financial Data Analyst</b>
</p>

---

## 🧬 About me, in code

```python
class Akdeep:
    def __init__(self):
        self.background = ["Finance", "Accounting", "Commerce"]
        self.python_level = "Beginner (and levelling up every week)"
        self.learning = ["Python", "NumPy", "Pandas", "Seaborn",
                         "SQL", "Advanced Excel", "Power BI"]
        self.languages = ["English", "Hindi", "Punjabi",
                          "Spanish (beginner)", "Korean (beginner)"]
        self.superpower = "Finding the story hidden in the numbers"
        self.fuel = "Curiosity + chai ☕"

    def goal(self):
        return "Land a Data / Financial Analyst role and make data useful"

me = Akdeep()
print(me.goal())
```

## 🎮 Current quest log
- 🔭 **Levelling up:** Python (beginner, now moving into data analysis), SQL, Advanced Excel and Power BI
- ✅ **Just shipped:** two dashboard projects, one in **Power BI** and one in **Excel** (see below)
- 🏗️ **Next up:** exploring the same kind of data with Pandas and Seaborn, plus a project that uses SQL
- 🎯 **Seeking:** entry-level Data Analyst / Financial Analyst roles
- 💬 **Ask me about:** financial statements, pivot tables, or how Kho-Kho strategy is basically optimisation

## 🧰 My toolkit

![Python](https://img.shields.io/badge/-Python%20Beginner-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/-Seaborn-4C72B0?style=for-the-badge)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Skills unlocked 🔓**
| Area | What I can do |
|---|---|
| 📗 Excel | Data cleaning, pivot tables, slicers, VLOOKUP/XLOOKUP, conditional formatting, data validation, interactive dashboards |
| 📊 Power BI | Multi-page dashboards, data modelling, DAX measures (MTD/QTD, YoY), maps, slicers, page navigation, KPI cards |
| 🧱 Data modelling | Power Query, Power Pivot data model (star schema), DAX measures, VBA macros |
| 🗃️ SQL | SELECT, GROUP BY, HAVING, JOINs, subqueries, views |
| 🐍 Python | Beginner level: variables, data types, conditionals, loops, functions, lists. Now learning Pandas, NumPy and Seaborn |
| 💰 Finance | Accounting, financial management, cost accounting, financial statement analysis |

## 🚀 Featured projects

### 🟡 Superstore Business Performance Dashboard (Power BI)
A **7-page interactive Power BI report** that takes leadership from a one-page executive summary down to sales, profit, orders, returns and customers, built on the Superstore sample dataset.

| | |
|---|---|
| **Tools** | Power BI · Data Model · DAX |
| **Pages** | Home · Executive Summary · Sales · Profit · Orders · Returns · Customers |

**What it does**
- 🧭 A **Home page with navigation buttons**, so the report works like a small app
- 📑 An **Executive Summary** with key insights, risks and recommended actions
- 📈 Each analysis page has **KPI cards** (including month-to-date and quarter-to-date), trend charts and tables, and slicers for **Year** and **Segment**
- 🗺️ **Maps and charts** by state, category, sub-category and segment: donut, ribbon, funnel, gauge, treemap and bar charts
- 🏆 Dynamic **"top category" and "top state"** cards for sales, profit, orders, returns and customers

**How it's built**
- **Data model:** five linked tables (Orders, Customers, Products, Returns and a Date table)
- **Measures:** about 25 DAX measures, including MTD/QTD time intelligence, average order value, return rate and top-performer measures

**💡 What the data said** *(from the Executive Summary page)*
- Sales grew **29.5%** and profit **48.4%** year over year, and orders grew **50.8%**
- **California** leads on sales, profit, orders and customers, and **Technology** is the top category
- ⚠️ **Tables and Bookcases lose money**, average order value fell **2.6%**, and returns rose **55%** year over year
- ✅ Recommended actions: fix losses in Tables and Bookcases, investigate returns, and raise basket value through cross-selling

👉 **[Project files and screenshots](https://github.com/YOUR-USERNAME/superstore-power-bi-dashboard)**

---

### 📗 Superstore Financial & Operational Dashboard (Excel)
An interactive, three-page Excel dashboard that gives leadership one view of **sales, profit and orders**, built on the same Superstore sample dataset.

| | |
|---|---|
| **Tools** | Excel · Power Query · Power Pivot (Data Model) · DAX · PivotTables & Slicers · VBA |
| **Pages** | 🟣 Sales · 🟣 Profit · 🟣 Orders · ℹ️ About |

**What it does**
- 📈 Tracks **total sales, profit, orders and profit margin**, with **year-over-year growth** for each
- 🔁 Monitors **return rate, total returns, average order value and average discount**
- 🗺️ Breaks performance down by **state, sub-category, customer segment and ship mode**
- 🏆 Highlights **top and bottom performers** (top 5 states, top 7 and bottom 7 sub-categories) and sales vs target
- 🎛️ Global **slicers** filter every page by Year, Product Category or Customer Segment, and buttons switch between pages

**How it's built**
- **Data model:** Orders, Customers, Products and Returns tables loaded with Power Query and linked in a star schema
- **Measures:** custom DAX measures, including time intelligence like `SAMEPERIODLASTYEAR` for YoY comparisons
- **Automation:** VBA macros for data shaping and table formatting
- **Design:** consistent layout and colours so the key numbers stand out

👉 **[Project files and screenshots](https://github.com/YOUR-USERNAME/superstore-excel-dashboard)**

## 🗺️ Learning roadmap
- [x] Advanced Excel: cleaning, pivot tables, lookups
- [x] SQL fundamentals: queries, joins, subqueries, views
- [x] Python basics
- [x] Power BI dashboards
- [x] Portfolio projects: Excel dashboard and Power BI report 🎉
- [ ] Python for data analysis: NumPy, Pandas, Seaborn
- [ ] A portfolio project using SQL
- [ ] A portfolio project using Python

## 🎲 Fun facts
- 🏅 Runner-up in inter-programme **Kabaddi** and **Kho-Kho** at university
- 🌍 Worked with an international team in **X-Culture**, writing a start-up business plan with students from across the world
- 🗣️ Speak 3 languages fluently and am learning 2 more (Spanish and Korean)
- 🎤 Comfortable on stage: public speaking and presentations are my thing
- 🏛️ **Red Bricks Summit** at IIM Ahmedabad

## 🎓 Education
- **M.Com (EAFM)**, University of Kota (2023–25)
- **B.Com (Finance)**, Ahmedabad University, Amrut Mody School of Management (2016–19)

## 📫 Let's connect
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akdeepkaur22@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akdeep-kaur)

<p align="center"><i>"In God we trust. All others must bring data."</i> 📊</p>
