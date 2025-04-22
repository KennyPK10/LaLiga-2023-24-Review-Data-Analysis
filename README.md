# ⚽ LaLiga Player Role Clustering & Power BI Insights

This project clusters LaLiga players into tactical roles based on match performance data. It combines web scraping, feature engineering, unsupervised clustering, and interactive visualization to reveal role-based insights in professional football.

---

## Project Summary

- **Web Scraping**: Collected player stats from online football databases using Python.
- **Data Cleaning**: Removed irrelevant and highly correlated features; finalized 22 meaningful attributes.
- **Feature Transformation**: Applied log and Yeo-Johnson transformations; standardized using `StandardScaler`.
- **Classification Validation**: Used models like Logistic Regression and Random Forest to check if selected features could predict player positions.
- **Clustering**: Applied Elbow Method to determine optimal `k`, and used KMeans to group players based on role-specific performance.
- **Visualization**: Used PCA and Seaborn for cluster plots and built a detailed Power BI dashboard for role-based player analysis.

---

## 🏟️ Roles Identified in Power BI

The final Power BI report analyzes and showcases top players in tactical categories such as:

- 🥅 **Clinical & Reliable Finishers**
- 🎯 **Shadow Strikers**, **Creative Wingers**, **Inverted Wingers**
- 🧠 **Advanced Playmakers**, **Dictators**, **All-Round Midfielders**
- 🚀 **Attacking Fullbacks**, **Box Threats**, **Wide Threats**
- 📦 **Carriers from the Back**, **Progressive Carriers**
- 📡 **Short / Medium / Long Passers** (Team Play Styles)
- 🎯 **Best Crossers**, **Challengers**, **Last Line Defenders**
- 🛡️ **Shields for the Team**
- 🧤 **Shot Stoppers**, **Penalty Savers**, **Sweeper Keepers**, **Ball Playing Keepers**

## 📂 Files


`LaLiga_EDA.ipynb` : Main Jupyter notebook with cleaning, integrating, modelling, classifying, clustering
`clustered_data.csv` : Final dataset with player clusters
`LaLiga_review.pdf` : Power BI report showing tactical roles and top players with various other summarised data with visualisation for easier understanding.
`README.md` : Project documentation |

---

## 🚀 Technologies Used

- **Python** – pandas, numpy, scikit-learn, seaborn, matplotlib
- **Clustering** – KMeans, Elbow Method, PCA
- **Classification** – Random Forest, Logistic Regression (for feature validation)
- **Power BI** – Dashboard for visual storytelling
- **Web Scraping** – requests, BeautifulSoup

---

## ✨ Outcome

This project not only reveals **hidden patterns** among LaLiga players but also presents **tactical roles** in a way that can help coaches, analysts, and fans make sense of the game's data-rich side. The powerbi report visually depicts key players in various roles and position and also provides a summarised view.

---

## 📬 Contact

**Pranav Kumar K**  
## 🔗 GitHub Repository
[View the Project on GitHub](https://github.com/KennyPK10/LaLiga-2023-24-Review-Data-Analysis)
