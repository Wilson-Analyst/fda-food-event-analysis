# FDA Food Event Analysis Project

## 📌 Project Overview

This is an exploratory data analysis (EDA) and dashboard project based on the **FDA Center for Food Safety and Applied Nutrition (CFSAN) Adverse Event Reporting System (CAERS)**.

Unlike many other projects that use pre-cleaned datasets from platforms like Kaggle, **this project stands out by connecting directly to the FDA API to collect raw, unstructured data**. I then built the entire pipeline — from data cleaning and transformation to analysis and dashboarding — entirely from scratch.

The focus is on understanding **adverse events reported from food, beverages, and supplement products**, with a deep dive into **reactions, serious outcomes, and demographic patterns**.

---

## 🎯 Key Questions Answered

- What are the most frequently reported **adverse reactions** to food and supplements?
- Which **serious outcomes** (like death or hospitalization) are most common?
- How have these outcomes **changed over time**? (Trends and spikes)
- Are there any notable patterns by **age group**, **gender**, or **geographic region**?
- Which **brands or products** appear most frequently in reports?
- What are the most common **combinations of reactions**?
- How many outcomes are **linked to supplements vs food vs drinks**?

---

## 🛠 Tools & Technologies Used

- **Python** (for API data collection and preprocessing)
- **Excel** (initial data exploration and structure mapping)
- **Snowflake** (as cloud data warehouse)
- **MySQL** (for structured querying)
- **Power BI** (for dynamic visualization and dashboard creation)

---

## 📊 Key Visuals & Insights

<img src="screenshots/p1.png" width="700" alt="Dashboard Overview" />

- Dashboard includes trend charts for serious outcomes over time.
- Bar charts and slicers to explore adverse reactions.
- Map visual to view geographic distribution.
- Interactive filters for gender, age group, and product type.

> More screenshots available in the `/screenshots` folder.

---

## 📂 How to Use

You can download the `.pbix` Power BI report file and explore it locally:

🔗 [Download Power BI File](https://drive.google.com/file/d/1J2pMChG_9wpG3K_KKPaYBP7Kj7lCldmw/view?usp=sharing)

> Make sure to have Power BI Desktop installed to open the file.

If you're interested in the raw and cleaned data, check the `/data` folder and Jupyter notebooks in `/notebooks`.

---

## 📡 Data Source

- **FDA CFSAN Adverse Event Reporting System (CAERS)**
- Accessed via: [openFDA API](https://open.fda.gov/apis/)

---

## 🚧 Limitations & Next Steps

- Reports often contain multiple reactions per case, making modeling difficult.
- Some fields are unstructured and inconsistent (e.g., free-text reactions).
- Duplicates and missing demographic fields require careful handling.

> Next steps may include topic modeling or clustering reactions, or integrating NLP for reaction classification.

---

## 🙌 Credits

Project by **Wilson Analyst**  
For portfolio and educational purposes.  
Contact: www.linkedin.com/in/wilson-tchounna-tsabgou
