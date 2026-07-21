# 🧙‍♂️ The Brick Who Lived: A Harry Potter LEGO Data Chronicle

🏆 **Microsoft Power BI DataViz World Championships (Round 2 Submission)**  
🎯 **An Initiative by the Microsoft Fabric Community (60 Days of Data and AI)**  

---

## 📌 Project Overview

**The Brick Who Lived** is a highly thematic, 4-page interactive Power BI dashboard designed to analyze 25 years of LEGO building history. While the raw championship dataset encompassed a vast array of building themes, this report focuses entirely on the iconic **Harry Potter theme** to explore its evolution, historical milestones, and structural complexity across sets, characters, and individual parts.

The primary goal of this analysis is to track a quarter-century of wizarding product releases, highlight peak production years, evaluate build density trends, and index the expanding universe of minifigures and brick inventories.

---

## 📊 Dashboard Architecture & Insights

The report consists of 4 specialized, movie-inspired pages designed for seamless navigation and deep data storytelling:

* **Home (Overview):** Serves as the cinematic introductory homepage, spotlighting peak historical milestones across sets released (2018), minifigures conjured (2020), and total parts produced (2025).
* **Sets Directory:** Explores the 258 unique building kits released since 2001, tracking set production velocity over the decades, analyzing average brick density, and highlighting the most recreated iconic locations like Hogwarts Castle and Diagon Alley.
* **The Marauder's Minifigure Register:** A deep-dive character index tracking the evolution of over 900+ unique figures, offering dynamic year filtering, decade timelines, and high-resolution image rendering for individual minifigures.
* **Inventory of Magic (Parts & Bricks):** Breaks down the raw structural components behind the magic, charting the explosive growth of 124,000+ individual parts and indexing piece counts across sets.

---

## 🛠️ Technical Features & Core Functionalities

* **Custom Wizarding UI/UX:** Formatted with a dark, cinematic aesthetic using golden accent borders, movie-inspired typography, and custom page navigation designed specifically for the Harry Potter universe.
* **Image-Rendered Tables:** Utilized image URL data types (`img_url`) to render crisp, scaled minifigure prints and set box art directly inside Power BI matrix tables.
* **Dynamic Sentence Tooltips:** Configured custom DAX-driven sentence tooltips across line charts and milestone visual cards to deliver context-rich, natural language insights upon hover.
* **Data Modeling & DAX:** Applied star-schema principles to model set registries, character collections, and part inventories, utilizing DAX measures for aggregate counts, average brick density, and time intelligence trends.

---

## 🚀 How to Explore the Dashboard

* **Live Report Interactive Link:** [View My Live Report](https://community.fabric.microsoft.com/t5/Contests-Gallery/The-Brick-Who-Lived-A-Harry-Potter-LEGO-Data-Chronicle/m-p/5306684#M3620)
* **Download & Play:** Clone this repository, download the `.pbix` file, and open it using Power BI Desktop to inspect the modeling structure, custom page layouts, and DAX measures.

---

## 🔬 Credits & Author

* **Author:** Urvashi Santoki   
* **💼 Connect:** [LinkedIn](www.linkedin.com/in/urvashi-santoki-a47826295)

---

## 📂 Repository Structure

```text
├── World Champs BCN 26 - Round2.pbix        # The main Power BI report file
├── Screenshots/                             # High-resolution images of all 4 dashboard pages
├── LEGO Harry Potter Dashboard video.mp4    # Video demonstration walkthrough of the dashboard
└── README.md                                # Project documentation
