# Shopify-Data-PowerBI
Table of Contents for Repository Artifacts

File Number	Title	Description
1	README.md	This current page with all relevant information about the project, just past the Table of contents.
2	Requirements.txt	A simple .txt file with the provided project requirements 


Table of Contents for README

Section Title	Description
DATA	Describes the source of data, included files, tables, and fields.
Description	Describes the final product's purpose, software, format, and included visuals.
Process	A general outline of how this project formed from start to finish.
Findings	Insights learned from the data analysis.
Data

The Excel file provided by TripleTenwas was public data scraped from the Shopify App Store.

'shopify.xlsx': Excel Workbook containing 4 sheets:
'apps': Details of the apps on the Shopify apps marketplace
'apps_categories': Join tables to connect apps with categories
'categories': Categories of the apps. Each app has multiple categories
'reviews': Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.
Description:

3 page Power BI Dashboard
Includes data analysis, KPI cards and Charts
Assumptions:

The scraped data from Shopify websites is accurate and representative of the actual app landscape.
The data in the shopify.xlsx file is complete and consistent, with minimal missing values or inconsistencies.
The provided column names and data types in the tables accurately reflect their content.
Process:

I first assessed the app store landscape using KPI cards and charts. Then I cataloged review data with cards and charts. Lastly, I analyzed app developers across review types.

Findings:

New Apps are more likely to be rated early in their deployment.
Most apps are rated favorably.
Reviews are higher for an app if a developer answers the review.
Reviews that have been voted as helpful have a weighted average of 5.48.
The app developer "Elfsight" has the highest combined ratings at 135.10 stars.
The app developer "Pictorem" has the highest average helpful reviews at 50.
The app developer "FireaApps" has responded to the highest amount of reviews at 6,008 responses.
