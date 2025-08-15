# 🧠 Syracuse Womens Lacrosse Dataset 2025: Claude vs ChatGPT - Model Analysis

This project compares responses from **Claude AI** and **ChatGPT (GPT-4o)** on a shared dataset: the **2025 Syracuse Women’s Lacrosse** season statistics. The goal is to evaluate data accuracy, analytical depth, and interpretation reliability.

---

## ✅ Areas of Agreement

| Question | Claude & ChatGPT Summary |
|---------|---------------------------|
| **1. Leadership Potential** | Both selected **Emma Ward** as future captain, citing high usage (76 points, 46 assists) and full season presence. Also acknowledged **Emma Muchnick** as a strong two-way option. |
| **2. Bounce-Back Player** | Both correctly stated the dataset lacks game-by-game data; refrained from speculation. |
| **3. Unsung Heroes** | **Coco Vandiver** and **Kaci Benoit** praised for defense (caused turnovers, ground balls). |
| **4. Shot Discipline** | **Emma Ward** had a lower shooting percentage (39%) than team average (43.7%); **Mileena Cotter** near average (42%). |
| **5. Weak Matchups** | Both cited the **Boston College** game (2–17 loss) as worst defeat. UNC and Stanford playoff loss also noted. |

---

## ❌ Key Differences in Responses

| Topic | Claude | ChatGPT | Verdict |
|-------|--------|---------|---------|
| **Under Pressure Performance** | **Olivia Adamson** (5.33 PPG, 3 games) | **Caroline Trinkaus** (4 game-winning goals) | ✅ **ChatGPT** - Stronger context using clutch stats |
| **Draw Control Specialist** | **Alexa Vogelman** (31 DCs) | **Joely Caramelli** (team-leading 39 DCs) | ❌ **Claude Error** - ChatGPT correct |
| **Possession Efficiency** | **Molly Guzik** (0.74 TO/game) | **Coco Vandiver** (3 TOs in 19 games) | ✅ **ChatGPT** - Total TOs more impactful |
| **Offensive ROI** | **Carlie Desimone** (1.00 ROI, 12 shots) | **Emma Ward** (0.987), **Adamson** (0.889) | ✅ **ChatGPT** - Prioritized sustainable volume |
| **Impact Per Minute (IPM)** | Estimated minutes (not in dataset) | Based on dataset fields: `(G + A + GB + CT - TO) ÷ GP` | ✅ **ChatGPT** - Transparent, reproducible metric |

---

## 🔍 Summary of Methodological Differences

| Dimension | Claude | ChatGPT | Strength |
|----------|--------|---------|----------|
| Pressure Stats | Small sample (Adamson) | Game-winning stats (Trinkaus) | 🎯 ChatGPT |
| Data Validity | Estimated minutes, assumed leaders | Used raw totals, leaderboard validation | 📊 ChatGPT |
| Metric Design | Custom formulas not grounded in data | Reproducible stats-driven metrics | ✅ ChatGPT |
| Risk of Overgeneralization | High in low-sample insights | Conservative, data-bound insights | 🔐 ChatGPT |

---

## 🎓 Conclusion

While **Claude** generated plausible narratives, it occasionally relied on:
- Estimated fields (e.g., minutes played)
- Lower-volume samples for high-stakes metrics
- Inaccurate leaderboard assumptions

**ChatGPT** consistently:
- Used complete and correct datasets
- Cited raw leaderboard numbers and percentages
- Designed metrics based on accessible fields

> **Final Verdict**: For sports-based analytical precision, **ChatGPT (GPT-4o)** delivered superior and reproducible insights.

---

## 📝 Author

**Prepared by**: Shreshth Shetty  
**Project**: LLM-Based Data Reasoning Comparison  
**Date**: August 2025  


---

