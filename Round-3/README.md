# 🎬 The Cinematic Box Office: Global Film Analytics & Studio Power

🏆 **Microsoft Power BI DataViz World Championships (Final Round Submission)**  
🎯 **An Initiative by the Microsoft Fabric Community (60 Days of Data and AI)**  

---

## 📌 Project Overview

**The Cinematic Box Office** is an interactive, 4-page Power BI analytics report designed to evaluate nearly a century of cinema data (1937–2026). Analyzing 72,379+ movies from the global TMDB dataset, this report explores how revenue is generated across legacy studios, uncovers genre profitability drivers, and tracks audience engagement trends over time.

The primary objective of this project is to uncover what drives theatrical success—examining how $825.56B in total box office revenue and $496.64B in profit are distributed across production statuses, top studios, and high-ROI niche genres.

---

## 📊 Dashboard Architecture & Insights

The dashboard contains 4 cinematic, interconnected pages designed for intuitive visual exploration and strategic data storytelling:

* **Home:** A cinematic entry page presenting core industry questions across historical revenue trajectories, audience ratings, and studio revenue share.
* **Industry Overview:** Tracks nearly a century of cinematic performance (1937–2026)—breaking down **$825.56B** in revenue, **$328.91B** in total budget, and **$496.64B** in total profit alongside a hierarchical vote decomposition tree.
* **Genre & Profit Trends:** Analyzes 19 distinct movie genres across **72,379+ titles**, mapping audience popularity against average ratings and charting profit distribution across release years.
* **Genre & Studio Financial Breakdown:** Evaluates financial performance by production status, compares budget vs. revenue via connected dot plots, and ranks the Top 10 legacy studios (led by Warner Bros., Universal Pictures, and 20th Century Fox).

---

## 🛠️ Technical Features & Core Functionalities

* **Custom Dark-Slate UI Aesthetics:** Built with a custom dark-slate layout, movie-inspired icons, and a persistent left-hand navigation pane with integrated global slicers (`Genre`, `Year`, `Month`, `Production Company`).
* **Hierarchical Decomposition Trees:** Implemented interactive vote count breakdowns by year and movie title, allowing users to drill directly into individual crowd engagement drivers.
* **Star-Schema Modeling & DAX:** Structured fact and dimension tables across bridge relationships to enable smooth multi-genre and studio aggregation across measures including profit margins, volume counts, and rating distributions.

---

## 🚀 How to Explore the Dashboard

* **Live Report Interactive Link:** [View My Live Report](https://community.fabric.microsoft.com/discussions/pbi_contestsgallery/global-box-office-the-concentrated-power-of-genres--studios/5354165)
* **Download the `.pbix` File:** Due to GitHub's file size limit of 25 MB, the original `.pbix` report file is hosted and available for direct download within the attached live report link above.

---

* **🔬 Author:** Urvashi Santoki   
* **💼 Connect:** [LinkedIn](www.linkedin.com/in/urvashi-santoki-a47826295)

---

## 📂 Repository Structure

```text
├── Screenshots/                             # High-resolution images of all 4 dashboard pages
├── Global Box Office Dashboard video.mp4    # Video demonstration walkthrough of the dashboard
└── README.md                                # Project documentation
