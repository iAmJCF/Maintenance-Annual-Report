# Fleet Maintenance Power BI Report (2024 Simulation)

This project is a simulated Power BI dashboard for our trucking company's **maintenance department**. It was developed to represent a full annual report for a **25-truck fleet**, including key metrics on repair costs, driver behavior, parts usage, and vendor repairs.

---

## Project Objective

The maintenance team needed a single source of truth to track:
- Labor and parts costs
- Repairs by vehicle and reason
- Preventative maintenance (monthly oil and filter changes)
- Driver misuse/abuse (e.g. tire curb damage)
- Towing fees for breakdowns
- Outside vendor repair costs

This dashboard was built to reflect those requirements using simulated but realistic data.

---

## Dashboard Pages

### Page 1: Annual Maintenance Summary
- Total cost breakdown (parts + labor)
- Most expensive vehicles
- Monthly trends
- Tire misuse costs

### Page 2: Driver Impact Dashboard
- Misuse incidents per driver
- Total tire-related costs
- Towing costs by month
- Driver comparison

### Page 3: Parts & Vendor Analysis
- Most frequently purchased parts
- Monthly parts spending
- Part usage by truck

---

## Tools Used

- **Power BI Desktop**
- **DAX** for KPI measures
- **Power Query** for calculated columns and data prep
- **Excel** and **Python** to simulate raw datasets

---

## Notes & Limitations

- This dataset is **entirely synthetic** and not from a production system.
- Purchase Orders and Work Orders currently track parts separately and are not directly linked by `PartID` or `WorkOrderID`. This is flagged for future data model enhancement.
- This report was developed to simulate reporting output similar to what might come from tools like **Fleetio**, **Samsara**, or **AssetWorks**, using internal Power BI infrastructure instead.

---

## Usage

1. Download the `.pbix` file.
2. Load the CSV files from the `Data/` folder when prompted.
3. Refresh the data in Power BI to populate visuals.

