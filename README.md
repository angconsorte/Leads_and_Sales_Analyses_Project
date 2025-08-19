# Customer & Leads Analytics (Power BI)  
_Operationalizing a self-initiated analysis into a live, API-driven sales intelligence tool_

> **Note on data privacy:** All screenshots below are **representative**; the production dashboard contains confidential data from Microsoft Dynamics NAV and cannot be disclosed.

---

## 📌 Project Summary
I proposed and built an analytics solution to explore customer, lead, and proposal data originally exported from **Microsoft Dynamics NAV**.  
What began as a one-off exploration in **Power BI** (using spreadsheet extracts) evolved. After a successful demo to ADS' **VP of Sales** this project turned into a **production, API-connected dashboard** used by sales leadership and managers to track pipeline, territory performance, and others.

---

## 🎯 Goals
- Centralize scattered sales, lead, and customer information
- Provide **actionable** insights for Sales & Marketing (territories, channels, products)
- Transition from **static exports** to a **live** and **reliable** data product

---

## 🧰 Tech & Skills
- **Power BI Desktop & Service**
- **Power Query (ETL):** cleansing, type enforcement, normalization
- **DAX Measures:** KPI cards, % shares, trend lines
- **Dynamics NAV APIs:** live connection (in collaboration with IT/Dev)
- **Data Modeling:** relationships and role-playing date dimension
- **UX:** bookmarks, drill-through, slicers, responsive layout, accessibility contrast

---

## 🔄 Process & Methodology
1. **Discovery:** Met with Sales & Marketing to capture questions (top locations, mix Res/Comm, lead and proposal patterns, territory gaps).  
2. **Data Prep (ETL):**  
   - Removed duplicates & nulls, standardized region/city names  
   - Derived columns
   - Cleaned and combined address information

3. **Measures & KPIs (DAX):** `Total Leads`, `Total Proposals`, `Proposal/Sale%`, `Commercial % VS Residential%`, `Top N Locations`.  
4. **Visualization:** Iterative design reviews with stakeholders; added drill-throughs for territory and rep views.  
5. **Operationalization:** Partnered with IT/Dev to replace flat-file refreshes with **NAV API pipelines**; deployed to **Power BI Service** with scheduled refresh, row-level filters for manager views.  
6. **Adoption:** Presented to VP of Sales; rolled out to managers.

---

## 📊 What the Dashboard Shows
- **Geospatial footprint:** where leads and customers are concentrated  
- **Top markets & territories:** ranked by leads, proposals, and conversion  
- **Account mix:** **Residential vs. Commercial** share  
- **Trend analysis:** proposals by any given date, seasonality  
- **Sales motion:** lead sources, rep performance, and funnel progression

---

## 🖼️ Screens & Captions

> Replace the image paths with your own redacted screenshots or mock data visuals.

### 1) Dashboard Overview
![Overview](images/dashboard.png)  
<sub>**Figure 1.** Note on data privacy: All screenshots are representative; the production dashboard contains confidential data  and cannot be disclosed.</sub>

### 2) Spreadsheet Overview
![Leads Map](images/spreadsheet.png)  
<sub>**Figure 2.** Note on data privacy: All screenshots are representative; the production dashboard contains confidential data  and cannot be disclosed.</sub>

## ✅ Conclusion

This initiative transformed a one-off exploration into a governed, always-current **sales intelligence product**. By combining **Power Query ETL**, clean **data modeling**, and targeted **DAX** with stakeholder-driven design, I was able to create a solution that delivers actionable insights in several different verticals.

By Partnering with IT to integrate **NAV APIs** and deploy in **Power BI Service** (scheduled refresh + RLS) we were able to embed the dashboard into the sales operating rhythm.

**Takeaway:** This project demonstrates end-to-end **Power BI proficiency**, from discovery and ETL through modeling, DAX, UX, and enterprise rollout while upholding data privacy and governance.