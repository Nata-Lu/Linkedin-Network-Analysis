# LinkedIn Network Growth Strategy: B2B Outreach Analysis and Insights

## Project Context

**Client Profile:** A B2B service provider working across multiple industrial sectors with a focus on international expansion.  
**Platform:** LinkedIn  
**Objective:** Analyze and optimize the client’s LinkedIn network growth to guide strategic outreach and content marketing.

In early 2024, a LinkedIn-based campaign was launched to develop visibility and reach within key industries. This project evaluates the results of that campaign and helps define data-informed goals for the next outreach phase.

---

## Project Goal

The objective is to:
- Assess the structure and evolution of the LinkedIn network
- Evaluate the success of 2024 outreach efforts (especially in Focus Industry 2)
- Derive actionable recommendations for continued network growth, particularly in Focus Industry 3

---

## Data Sources

The analysis is based on two complementary datasets:
- **LinkedIn Connections Export** – downloaded directly from the profile, including full metadata
- **Evaboot Export** – scraped public LinkedIn data enriched with company-level info

⚠️ Original data is not shared to protect client confidentiality. An anonymized version is included for reproducibility.

---

## Data Privacy and Anonymization

All personal and corporate identifiers were removed or pseudonymized:

| Element            | Anonymization Approach                                  |
|--------------------|----------------------------------------------------------|
| Full names         | Replaced with `Person_ID`                                |
| Company names      | Mapped to `Company_XXX` with Freelance consolidated      |
| Industries         | Mapped to LinkedIn's hierarchy + aggregated by theme     |
| Positions          | Mapped to broad functions (e.g. Management, Sales, HR)   |
| Sensitive fields   | Dropped (URLs, emails, detailed job descriptions)        |

The dataset included in this repo complies with GDPR and ethical data publication standards.

---

## Data Preparation (Not Included)

While the full notebook for data cleaning is not published (due to privacy constraints), key steps included:
- Matching and joining datasets with fuzzy logic and manual review
- Deduplicating and standardizing company names
- Aggregating and anonymizing industries
- Mapping job titles to high-level functions
- Filtering and structuring for EDA and dashboard use

---

## Key Results

### 2024 Campaign Results

- **+36% growth** in 2024 (network grew from ~410 to 557)
- **Main focus:** Focus Industry 2  
- **Target geographies:** North America and Africa  
- **Success:** Significant increase in target audience presence

### Lessons Learned

1. **Account Depth Is Shallow**  
   → Most accounts have only one contact. Only a few accounts had 2+ connections.

2. **Targeted Companies Are Large**  
   → Reaching multiple decision-makers per account is key, especially in large enterprises.

3. **Roles Reached:**  
   → Mostly Management, followed by Engineering and Operations  
   → Procurement, Marketing, and Communications underrepresented

4. **Next Steps for Focus Industry 3:**  
   → Current presence is minimal (15 contacts in 15 companies)  
   → Focus on companies with 50–5,000 employees  
   → Target Business Development, Procurement, and Management roles

---

## Deliverables

### Exploratory Data Analysis

📓 Notebook: [EDA.ipynb](EDA.ipynb)  
📁 Dataset: [linkedin_connections_anonymized_public.csv](linkedin_connections_anonymized_public.csv)

### Interactive Dashboard

View on Tableau Public:  
🔗 [LinkedIn Network Dashboard](https://public.tableau.com/views/LinkedInNetworkGrowth/Dashboard2?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

📊 Dashboard Preview
<img width="3198" height="1798" alt="Dashboard 2-2" src="https://github.com/user-attachments/assets/20767981-3c66-4921-a47d-822140b30390" />


- Switch views between **2024** and **All Time**
- Filter by **Focus Industry**
- Visualize growth trends, account depth, company size, and geography
- Evaluate function mix and industry penetration

---

## Strategic Recommendations

This project enabled data-informed decisions for:

- Continuing growth in **Focus Industry 2** (with deeper account penetration)
- Launching a targeted campaign for **Focus Industry 3**
- Refining function targeting and geographic segmentation
- Enhancing content marketing strategy with audience data


