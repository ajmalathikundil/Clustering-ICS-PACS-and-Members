# Clustering-ICS-PACS-and-Members

This project applies K-Means clustering to analyze geographical data from organic grower groups, Primary Agricultural Credit Societies (PACS), and NCOL members. The goal is to identify areas with high concentrations of these entities to optimize operations, onboard new PACS, and assign existing PACS to manage organic grower groups. These PACS act as procurement hubs, making clustering insights crucial for effective decision-making.

Features
1. Extract pin codes from addresses using Python’s re library.
2. Match addresses with latitude and longitude for geospatial analysis.
3. Perform K-Means clustering to identify group concentrations.
4. Refine clusters where distances exceed a defined threshold for better precision.
5. Provide actionable insights for onboarding and field management
