
🕊️ Russia-Ukraine War Power BI Dashboard
This project presents an interactive Power BI dashboard that visualizes key data related to the ongoing Russia–Ukraine war, offering insights into humanitarian, military, geopolitical, and economic aspects of the conflict.

📊 Features
Casualties: Civilian and military casualty counts over time and by region.

Refugee Movements: Displacement trends, host countries, and temporal flows.

Equipment Losses: Visual breakdown of military equipment losses by type and country.

International Aid: Contributions by donor countries and aid types.

Sanctions: Issued sanctions by country, type, and timeline.

Territorial Control: Timeline and status of region control throughout the conflict.

🧩 Data Model
The data model uses a star schema design with the following:

Fact tables: Casualties, Refugees, International_Aid, Sanctions, Territorial_Control, Equipment_Losses

Lookup tables: CountryLookup, AidTypeLookup, EquipmentTypeLookup, SanctionLookup, DateTable, and disconnected slicers for filtering

⚙️ Technologies
Power BI Desktop

DAX for custom measures (e.g., TREATAS-based filtering)

Excel for initial data structuring

Visual design includes custom background and KPIs

📁 Files Included
.pbix Power BI report file

.xlsx source dataset

.png background image for dashboard pages

✅ Usage
Download the .pbix and .xlsx files.

Open in Power BI Desktop.

Refresh or replace data sources if needed.

Interact with slicers and visuals to explore trends and patterns.
