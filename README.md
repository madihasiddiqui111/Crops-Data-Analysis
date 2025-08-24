# Agricultural Insights
This project focuses on analyzing agricultural datasets (temperature, rainfall, humidity, and yield) to uncover seasonal and crop-based patterns.
The pipeline involves data storage in AWS S3, processing in Snowflake, and visual analytics in Power BI.

## Report Link:
https://app.powerbi.com/links/yML_GUDXuC?ctid=5bcca112-41e4-4d5e-a805-c5ba21ed65b6&pbi_source=linkShare&bookmarkGuid=d8993238-6a0f-4697-bbb6-7d8fcbe3df42

## Data Pipeline Workflow

**- AWS S3**

-  Created an S3 bucket to store raw CSV data (data_season.csv).

-  Uploaded dataset for centralized cloud storage.

**- Snowflake Integration**

-  Created role, integration object, and trust policy for secure connection.

-  Loaded data into Snowflake tables.

-  Applied data profiling & transformation using Snowflake SQL (cleaning, handling nulls, grouping rainfall levels).

**- Power BI**

-  Connected Snowflake as a data source.

-  Created interactive dashboards with slicers, bookmarks, and conditional formatting.

-  Published report to Power BI Service for sharing.

## Dashboard Pages & Visuals

**1) Temperature Analysis**

- Avg Temperature by Crop

- Avg Temperature by Year

- Avg Temperature by Location

- Avg Temperature by Season
<img width="1153" height="652" alt="Image" src="https://github.com/user-attachments/assets/15b331b2-949a-443f-af57-8d7a4d71ce5a" />
**2) Rainfall Analysis**

- Avg Rainfall by Crop

- Avg Rainfall by Year

- Avg Rainfall by Location

- Avg Rainfall by Season

**3) Humidity Analysis**

- Avg Humidity by Crop

- Avg Humidity by Year

- Avg Humidity by Location

- Avg Humidity by Season

**4) Yield Analysis**

- Avg Yield by Crop

- Avg Yield by Year

- Avg Yield by Location

- Avg Yield by Season

 ## Insights

**Rainfall vs Yield:** Strong correlation between high rainfall seasons and increased yield in specific crops.

**Temperature Variation:** Certain crops (e.g., rice, wheat) are highly sensitive to seasonal temperature differences.

**Humidity Trends:** Humidity plays a crucial role in crop productivity across regions.

**Location-wise Analysis:** Geographical variation highlights specific regions with consistent crop performance.

