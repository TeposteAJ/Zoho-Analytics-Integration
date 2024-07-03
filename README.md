# Zoho-Analytics-Integration
This repository contains the code necessary to integrate Zoho Analytics with your Odoo system. The integration facilitates seamless data synchronization between Odoo and Zoho Analytics, enabling advanced data analysis and reporting capabilities directly within Zoho's robust analytics platform.

As per the instructions provided by Zoho Analytics, we have implemented the following steps to ensure seamless data synchronization and reporting:

1. **Authentication**: Users need to authenticate with their Odoo account to fetch data into Zoho Analytics.
2. **Data Synchronization**: The integration ensures that data from Odoo is regularly synced with Zoho Analytics, providing up-to-date information for analysis.
3. **Handling Deleted Records**: To maintain accurate records, we have added a new table, `zadeleted_records`, to track IDs of records deleted in the last 30 days. This table is dynamically updated during the synchronization process.

The provided zip file contains the necessary code to set up this integration. Users should extract the contents and place them in the `/usr/lib/python3/dist-packages/odoo/addons` directory of their Odoo instance. This setup will ensure that deleted records are properly tracked and reported in Zoho Analytics.

This integration will significantly enhance our ability to analyze business data, identify trends, and make data-driven decisions.

