# 📊 Internship Project: Multi-Source Data Integration & Dashboard in Looker Studio

This project was completed during my **Data Analyst Internship at Excelerate (Remote)** in June 2025. It involved merging **six raw datasets** into a single master table using **PostgreSQL** and building an **interactive dashboard in Looker Studio** to support business decision-making.

---

## 📌 Objective

- Integrate raw data from multiple sources into a unified schema
- Clean, transform, and join data using PostgreSQL
- Create a consolidated **master table** for streamlined analysis
- Build a dashboard in **Looker Studio** with meaningful visual insights
- Document logic and visuals using a wireframe PDF with data annotations

---

## 🗃️ Datasets Used

| Table Name                   | Description                                         |
|-----------------------------|-----------------------------------------------------|
| `Learner_Raw`               | Contains learner-level information and activity     |
| `Marketing Campaign Data All Accounts` | Campaign metadata and account-level targeting |
| `Opportunity_Raw`           | Opportunity-level sales and pipeline data           |
| `Cognito_Raw2`              | Behavioral and engagement data                      |
| `LearnerOpportunity_Raw`    | Relationship mapping between learners and opportunities |
| `CohortRaw`                 | Cohort-level grouping of learners                   |

> All tables were imported into PostgreSQL and stored in structured schemas.

---

## 🧠 Key SQL Tasks Performed

- Data type casting and normalization (`TO_DATE`, `CAST`, `TRIM`, etc.)
- Handling NULLs and inconsistent entries
- Applying `INNER JOIN`, `LEFT JOIN`, and conditional joins
- Creating a **consolidated `master_table`** using relationships across datasets
- Creating helper views to assist with dashboard metrics

---

## 🧾 Deliverables

- ✅ **Master Table**: `final_marketing_master_table` (PostgreSQL)
- ✅ **Dashboard**: Built using Google Looker Studio
- ✅ **Wireframe PDF**: Includes metric definitions, chart logic, and KPI annotations

---

## 🧩 Tools Used

- **Database**: PostgreSQL (pgAdmin for table management)
- **Visualization**: Looker Studio (Google Data Studio)
- **Scripting**: SQL (Joins, CASE WHEN, CTEs)
- **Planning**: PowerPoint, Google Docs, PDF Annotations

---

## 📷 Visual & Documentation

- 📄 `wireframe_with_annotations.pdf` – Dashboard design and logic
- 📦 `master_table.sql` – Script to generate final merged table
- 📊 Dashboard screenshot or shareable link – *(optional, can be added here)*

---

## 📂 Repository Structure

📁 sql_scripts/
├── create_tables.sql
├── import_data.sql
├── clean_transform.sql
├── build_master_table.sql

📁 docs/
├── wireframe_with_annotations.pdf

📁 dashboard/
├── dashboard_notes.md (optional)


---

## 👨‍💻 Author

**Dasu Charan Teja**  
📧 charanteja1039@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/charan-teja-995a0a31a/)  
💻 [GitHub](https://github.com/cherry-10)

---

> ⭐ If this project helped or inspired you, feel free to star the repo and connect!
