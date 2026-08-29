# People Analytics Executive Dashboard

## Portfolio positioning
**Project title:** People Analytics Executive Dashboard | Power BI Portfolio Project

**Scenario:** Northstar Digital Services is a fictional Canadian digital-services organization. The dataset is synthetic and contains no real employee information.

## Business problem
Leadership needs a single executive view of workforce growth, turnover, engagement, absence, talent movement and workforce composition.

## Questions to answer
1. How has headcount changed over time?
2. Which departments are driving growth or contraction?
3. Where are total and voluntary turnover highest?
4. Which workforce segments show lower engagement or higher absence?
5. How are hires, exits and promotions changing over time?
6. What is the current workforce mix by department, location, level, gender, age band and work mode?
7. Which departments should management investigate first?

## Recommended Power BI pages
### Page 1 — Executive Overview
- Current Headcount
- FTE
- Headcount Growth
- Hires
- Exits
- Turnover Rate
- Average Engagement
- Headcount Trend
- Hires vs Exits
- Headcount by Department
- Workforce Risk Matrix

### Page 2 — Turnover & Movement
- Total Turnover
- Voluntary Turnover
- Exit Reasons
- Turnover by Department
- Turnover by Job Level
- Promotion Rate
- Hires vs Exits trend

### Page 3 — Workforce Profile
- Department
- Location
- Job Level
- Work Mode
- Employment Type
- Gender
- Age Band
- Average Tenure
- Engagement
- Absence Days per FTE

## Data model
Load:
- `employee_master.csv`
- `monthly_snapshot.csv`

Create a Calendar table in Power BI covering 2024-01-01 through 2026-07-31.

Use `SnapshotMonth` for monthly trend analysis. Use inactive date relationships (or USERELATIONSHIP measures) for `HireDate` and `TerminationDate`.

## Final portfolio deliverables
1. Power BI `.pbix`
2. Three dashboard screenshots
3. One-page case study
4. GitHub README
5. KPI dictionary
6. Synthetic source data

## Resume rule
Describe this explicitly as a **portfolio project using synthetic data**. Do not present Northstar Digital Services as a real employer or client.
