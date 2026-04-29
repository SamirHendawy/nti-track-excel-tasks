# \# 📊 NTI Data Analysis Track — Excel Tasks

# 

# > Practical Excel tasks completed as part of the \*\*NTI Data Analysis Track\*\*, covering core spreadsheet functions, pivot tables, charts, and dashboard building.

# 

# \---

# 

# \## 📁 Repository Structure

# 

# ```

# ├── assets/

# │   ├── basics\_preview.png      # Task 1 screenshot

# │   ├── engine\_preview.png      # Pivot tables \& charts sheet

# │   └── dashboard\_preview.png   # Final dashboard

# ├── Basics\_Task\_Solution.xlsx   # Task 1 — Excel Fundamentals

# ├── SampleData.xlsx             # Raw data used in Task 2

# ├── SimpleDashboard.xlsx        # Task 2 — Pivot Tables, Charts \& Dashboard

# └── README.md

# ```

# 

# \---

# 

# \## ✅ Task 1 — Excel Basics

# 

# Hands-on practice with the most essential Excel functions applied on an employee salary dataset.

# 

# \### Functions \& Features Covered

# 

# | Category | Functions / Features |

# |---|---|

# | \*\*Aggregation\*\* | `SUM`, `AVERAGE`, `MAX`, `MIN` |

# | \*\*Counting\*\* | `COUNTA`, `COUNTBLANK`, `COUNTIF` |

# | \*\*Conditional\*\* | `SUMIF`, `IF` |

# | \*\*Lookup\*\* | `VLOOKUP` / `XLOOKUP` |

# | \*\*Ranking\*\* | `RANK`, `LARGE`, `SMALL` |

# | \*\*Text\*\* | `CONCAT`, `LEN`, `LEFT`, `RIGHT` |

# | \*\*Formatting\*\* | Conditional Formatting (color-coded salary bands) |

# 

# \### Dataset Overview

# 

# \- 10 employees with First Name, Last Name, and Salary in USD

# \- Exchange rate applied to convert salaries to Egyptian Pounds (LE)

# \- Salary classification: \*\*Low / Medium / High\*\* using `IF`

# \- Summary stats: Total, AVG, MAX, MIN, 2nd Highest, 2nd Lowest

# \- VLOOKUP table mapping Emp\_ID → Full Name (lowercase \& formatted)

# 

# !\[Task 1 — Excel Basics](assets/basics\_preview.png)

# 

# \---

# 

# \## ✅ Task 2 — Pivot Tables, Charts \& Dashboard

# 

# Built a complete \*\*Sales Dashboard\*\* from raw transactional data using Power Query, Pivot Tables, and Charts — all connected to a Data Model.

# 

# \### Workflow

# 

# ```

# Raw Data (SampleData.xlsx)

# &#x20;       ↓

# &#x20; Load to Data Model (Power Query)

# &#x20;       ↓

# &#x20;  Pivot Tables (engine sheet)

# &#x20;       ↓

# &#x20; Charts + KPI Cards (engine sheet)

# &#x20;       ↓

# &#x20;  Dashboard (clean presentation layer)

# ```

# 

# \### Dashboard KPIs

# 

# | Metric | Value |

# |---|---|

# | Total Revenue | $19,627.88 |

# | Units Sold | 2,121 |

# | Average Order Value (AOV) | $456.46 |

# | Regions | 3 |

# 

# \### Visuals Included

# 

# \- 🍩 \*\*Sales by Region\*\* — Donut chart (Central 57%, East 30%, West 13%)

# \- 📊 \*\*Sales by Representative\*\* — Bar chart (Top: Kivell $3,109 / Parent $3,102)

# \- 🥧 \*\*Units Sold by Item\*\* — Pie chart (Binder 722, Pencil 716, Pen Set 395...)

# \- 📈 \*\*Monthly Sales Trend\*\* — Line chart (Jan–Dec)

# 

# \### Workbook Sheets

# 

# | Sheet | Purpose |

# |---|---|

# | `engine` | All pivot tables and chart sources (hidden from end-user) |

# | `dashboard` | Clean, interactive dashboard with slicers (Year: 2024 / 2025) |

# 

# \### Engine Sheet — Pivot Tables \& Charts

# 

# !\[Engine Sheet](assets/engine\_preview.png)

# 

# \### Final Dashboard

# 

# !\[Sales Dashboard](assets/dashboard\_preview.png)

# 

# \---

# 

# \## 🛠️ Tools Used

# 

# \- \*\*Microsoft Excel\*\* (Pivot Tables, Power Query, Data Model)

# \- Conditional Formatting

# \- Slicers for year filtering

# 

# \---

# 

# \## 📌 Notes

# 

# \- The focus of these tasks was \*\*practical application\*\*, not advanced modeling.

# \- Data is sample/demo data provided as part of the NTI course materials.

# \- Dashboard is filterable by year using built-in Excel slicers.



