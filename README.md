# NHS Appointment Trends & Missed Appointments Analysis - 89% Final Grade

This project was completed as part of the LSE Data Analytics Career Accelerator (Course 2). I explored appointment data across England’s NHS system to understand utilisation trends, staffing needs, and missed appointments. The focus was on providing strategic recommendations that improve service efficiency without increasing capacity.

## 🔧 Tools Used
- **Python** (Pandas, Matplotlib, Seaborn)
- **Excel** (Data validation, quick exploration)

---

## 📂 Files

- 📘 [Presentation Slides](./NHS%20Presentation.pdf)  
- 📄 [Project Report](./NHS%20Report.pdf)  
- 📓 [Analysis Notebook](./NHS%20Notebook.ipynb)

---

## 🧠 Business Problem

Missed GP appointments cost the NHS over £216M annually. At the same time, stakeholders debated whether current staffing and infrastructure are sufficient. My task was to explore:

- Actual utilisation across NHS networks
- Trends in missed appointments and their drivers
- Whether current capacity is sufficient or needs expansion

## 📊 Analytical Approach Highlights

- **Data Cleaning & Merging**  
  Cleaned and combined `appointments_regional.csv`, `actual_duration.csv`,`national_categories.xlsx`, and ICB reference data to support trend analysis.

- **Exploratory Data Analysis**  
  Used Python to uncover trends across appointment modes, lead times, and healthcare roles.

- **Data Quality Considerations**  
  Flagged and retained 'Unknown' entries to reflect limitations in NHS data collection practices.

- **Focused Scope**  
  Excluded datasets that were too short (7 months) or uninformative (Twitter data) to maintain clarity and relevance.

## 📌 Key Insights

- **GPs handle the highest demand**, highlighting their central role in NHS operations.
- **Face-to-face care is still preferred**, even post-COVID, despite the availability of remote options.
- **Missed appointments increase with long lead times** — especially bookings >21 days in advance.
- **Remote modes (Video/Home Visits) have the highest DNA rates**, pointing to engagement and tech barriers.
- **Utilisation remains under 85%**, suggesting scheduling inefficiencies, not capacity limits, are the issue.

## ✅ Recommendations

1. **Reduce DNAs in Remote Care**  
   Use reminders, app confirmations, and tech support to improve video/online attendance.

2. **Smarter Scheduling**  
   Allocate more same-day slots and use predictive analytics to identify high-risk no-shows.

3. **Fix Data Quality Issues**  
   Standardise dropdown input fields and reduce unknown classifications by 30% in 12 months.

---

## 🧭 Professional Development

This project sharpened my ability to:

- Translate open-ended business issues into clear, actionable questions
- Apply data analytics in a healthcare setting with operational complexity
- Combine strategic thinking and communication to present stakeholder-ready insights

I approached the problem as both a marketing strategist and data analyst—balancing user behaviour, systemic limitations, and practical recommendations.

