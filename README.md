# 🏀 NBA MVP Analysis (1981–2021) — Power BI

Interactive dashboard developed to analyze the history of the **MVP (Most Valuable Player)** award in the NBA over 42 seasons, exploring performance patterns, team impact, and a comparison between the greatest players in league history.

![Cover](EN/Page%201%20-%20EN.png)

[![Download Power BI](https://img.shields.io/badge/Download%20Dashboard-.pbix-yellow?style=for-the-badge&logo=powerbi)](https://github.com/lucas-pinheiro8/NBA-MVP-Analisys/raw/main/EN/NBA%20MVP%20Analisys%20-%20EN.pbix)

---

## 📊 About the Project

This project answers real questions about what defines an NBA MVP: do individual stats make a difference? Does age matter? Does the team need to be strong? Who are the greatest of all time?

**42 seasons** (1981–2021) were analyzed, covering **198 different players**, crossing individual statistics with collective team performance.

---

## 📄 Dashboard Pages

### Page 1 — MVP Overview
![MVP Overview](EN/Page%202%20-%20EN.png)

A complete overview of the MVP history with key KPIs and trends:

- **42** seasons analyzed (1981–2021)
- **198** different players in the history
- **26.9 pts** average scoring of MVPs
- **15.5 pts** — lowest average of an MVP winner (2005)
- Evolution of MVP scoring averages over the decades
- Pie chart: 69% of MVPs were won by players older than 26
- Ranking of teams with the most MVPs: Chicago Bulls and LA Lakers lead with 6 each
- Top 14 players with most Top 5 voting appearances — **LeBron James** leads with 14

---

### Page 2 — MVP Impact on the Team
![Team Impact](EN/Page%203%20-%20EN.png)

Analysis of the relationship between having an MVP and the collective performance of the franchise:

- Win comparison between teams **with MVP** vs **without MVP** per season (1980–2021)
- Offensive production scatter plot: MVPs consistently above league average in points and USG%
- Win impact chart by team level (Elite, Good, Average, Weak)
- **Key insight:** There are no MVPs on average or weak teams — the award is directly associated with high-performance franchises
- Comparative gauge: MVP average (26.9 pts) vs Top 15 candidates average (21.8 pts)

---

### Page 3 — Legends Comparison
![Legends Comparison](EN/Page%204%20-%20EN.png)

In-depth comparison between **Michael Jordan, LeBron James, Kobe Bryant, and Stephen Curry**:

- Career scoring average per player:
  - Michael Jordan: **30.7 pts**
  - LeBron James: **26.9 pts**
  - Kobe Bryant: **27.7 pts**
  - Stephen Curry: **26.5 pts**
- Line chart showing scoring average evolution across seasons
- Bubble chart: season average vs total points, with bubble size indicating MVP seasons
- Total MVP titles won: Jordan leads with **5**, followed by LeBron with **4**

---

## 💡 Key Insights

- **Age:** 69% of MVPs were won by players older than 26 — maturity and experience matter
- **Strong team is mandatory:** No MVP in history came from an average or weak team
- **Offensive production:** MVPs have USG% and scoring averages consistently above the league
- **Greatest winner:** Michael Jordan with 5 titles and a 30.7 pts average
- **Most appearances:** LeBron James leads Top 5 voting appearances with 14 times
- **Lowest average:** The 2005 MVP won with only 15.5 pts — a historical anomaly

---

## 🛠️ Tools Used

| Tool | Usage |
|---|---|
| Power BI Desktop | Dashboard and visualization building |
| Power Query | Data cleaning and transformation |
| DAX | Custom measures and KPI calculations |
| Kaggle | Historical NBA data source |

---

## 🗂️ Data Source

- **Dataset:** [NBA MVP Voting — Kaggle]
- **Coverage:** Seasons from 1981 to 2021
- **Data included:** Individual statistics, MVP voting, team performance per season

---

## 📁 Repository Structure
```
NBA-MVP-Analisys/
├── EN/
│   ├── NBA MVP Analisys - EN.pbix  # Power BI file (English)
│   ├── Page 1 - EN.png             # Dashboard Cover
│   ├── Page 2 - EN.png             # MVP Overview
│   ├── Page 3 - EN.png             # Team Impact
│   └── Page 4 - EN.png             # Legends Comparison
├── PT - BR/
│   ├── Análise MVP NBA.pbix        # Arquivo Power BI (Português)
│   ├── Página 1.png                # Capa do Dashboard
│   ├── Página 2.png                # Visão Geral dos MVPs
│   ├── Página 3.png                # Impacto do MVP no Time
│   └── Página 4.png                # Comparativo entre Lendas
├── README.md                       # English version
└── README pt-br.md                 # Versão em português
```

---

## 👨‍💻 Author

**Lucas Pinheiro**
