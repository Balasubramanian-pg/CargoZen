## Project: Operational P\&L Lakehouse

### Overview

This project establishes a month-wise ingestion pipeline from JSON sources into a lakehouse architecture to compute business-critical KPIs and build an operational P\&L dashboard.

### Pipeline Architecture

1. **Raw Data Ingestion**

   * 12 JSON files (1 per month)
   * Ingested using dynamic metadata

2. **Lakehouse Construction**

   * **Bronze Layer**: Raw + cleaned data
   * **Gold Layer**: Curated, structured data

3. **Data Processing**

   * Standardization
   * Layered transformation
   * Null/duplication handling

4. **Semantic Model Foundation**

   * Business KPIs derived from gold layer
   * Clean joins, hierarchies, and relationships

5. **Operational P\&L Visualization**

   * Dynamic dashboard generation
   * Drilldowns across months, categories

6. **Forecasting**

   * Predictive analytics on fuel and variable costs
