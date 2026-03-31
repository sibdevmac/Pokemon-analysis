# 🐉 Pokémon Data Analysis & Battle Simulation

## 📊 Project Overview

“Gotta catch them all!” — Inspired by this iconic Pokémon tagline, this project explores Pokémon creatures, their attributes, and battle strategies using data analysis.

The project focuses on:
- Understanding Pokémon strength and characteristics
- Identifying battle strategies
- Simulating outcomes using Python
- Creating a **hypothetical geographical mapping** of Pokémon types

---

## 📁 Dataset

🔗 Dataset: https://www.kaggle.com/datasets/abcsds/pokemon  
---

## 🎯 Objectives

The analysis is driven by the following key questions:

- Compare legendary and non-legendary Pokémon  
- Identify the strongest Pokémon  
- Determine factors influencing strength  
- Analyze generational trends  
- Cluster Pokémon based on Attack–Defense  
- Create a geographical distribution model  
- Build the best battle team  
- Simulate battle outcomes  

---

## ⚠️ Assumptions

- Analysis is **purely data-driven** (no external bias)  
- Geographical mapping is **hypothetical**, based on Pokémon types  
- Battle simulation is based on **dataset logic**, not actual game mechanics  

---

## 🔍 Key Findings

---

### 🥇 1. Legendary vs Non-Legendary

- Legendary Avg Total → **637**
- Non-Legendary Avg Total → **417**

📌 Insight:
> Legendary Pokémon significantly outperform others in **Attack, Defense, and Speed**

---

### 🐲 2. Strongest Pokémon

Top performers include:
- Rayquaza  
- Salamence  
- Kyurem  

📌 Insight:
> Dragon-type Pokémon dominate due to high overall stats.

---

### 📊 3. Factors Driving Strength

From correlation analysis:

- 🥇 Special Attack → strongest contributor  
- 🥈 Attack → core offensive power  
- 🥉 Special Defense → endurance factor  
- ⚠️ Speed → lowest correlation (~0.57)

📌 Insight:
> Strategy and power matter more than just speed.

---

### 📈 4. Generational Trends

- Strength varies across generations  
- Peak observed around **Generation 4**

📌 Insight:
> Game designers likely balance power across generations to maintain fairness.

---

### 🔵 5. Clustering (KMeans)

Three clusters identified:

- **Cluster 0 → Attackers**
- **Cluster 1 → Tanks (Defense)**
- **Cluster 2 → Balanced**

📌 Insight:
> Different battle scenarios require different Pokémon roles.

---

### 🌍 6. Geographical Mapping (Hypothetical)

- Water → Australia  
- Dragon → China  
- Other mappings based on ecological analogy  

📌 Insight:
> Pokémon distribution reflects **type frequency and environmental assumptions**, not real-world biology.

⚠️ Observation:
> Mapping shows bias toward Western regions; less representation for Africa and Egypt.

---

### ⚔️ 7. Best Battle Team

Team composition:
- 2 Attackers  
- 1 Tank  
- 2 Balanced  
- 1 Legendary  

🏆 Final Team Highlights:
- Rayquaza → High power finisher  
- Kyogre → Special attacker  
- Groudon → Strong offense + defense  
- Blissey → Defensive support  
- Deoxys → Speed-based attacker  

---

### 🎯 Battle Strategy

1. **Early Game** → Deoxys (fast strike)  
2. **Mid Game** → Groudon + Kyogre (control battlefield)  
3. **End Game** → Rayquaza (finisher)  
4. **Defense Phase** → Switch to Blissey  

---

### 🧪 8. Battle Simulation

- Custom `battle(p1, p2)` function:
  - Determines attack order via Speed  
  - Calculates damage using Attack & Defense  
  - Simulates until one Pokémon faints  

- `team_battle()` function:
  - Simulates full team battles  

opponent = df.sample(6, random_state=42)
Simulation rounds: 10
Win Rate: 80%

### 🧪 9. Conclusion

This project demonstrates how data analysis and simulation can:

Optimize battle strategies
Identify powerful Pokémon combinations
Improve decision-making using data

### Author

Sibankar Saha
