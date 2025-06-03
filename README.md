# 🏀 Power Five and the NBA Draft

## 📌 Summary  
This project explores whether playing in a Power Five NCAA conference affects a basketball player's chance of being drafted into the NBA.  
Using data from 2011–2021, I estimate the impact of conference affiliation using probit and instrumental variable (IV) models, while controlling for player performance and physical stats.

---

## ❓ Key Question  
**Does playing in a Power Five conference increase the chances of being drafted?**

---

## 📊 Data & Methods  

**Data:**  
- NCAA men’s basketball stats (2011–2021) from Sports Reference

**Methods:**  
- Probit regression  
- Extended probit with IV (to address endogeneity)  

**Controls:**  
- Player stats (e.g., points, assists)  
- Physical attributes (height/weight)  
- Year fixed effects  

---

## 🔍 Main Finding  
Even after controlling for performance and physical characteristics, **ACC and SEC players are significantly more likely to be drafted**.

---

## 💻 Software  
- **Stata**: Data cleaning and analysis 
