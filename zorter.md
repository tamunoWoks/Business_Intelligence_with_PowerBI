### Comparing Data Connectivity Modes
|   | Import | DirectQuery | Live Connection |  
|:---|:--------|:-------------|:-----------------|
| Maximum size | Based on how you’re licensed | Limited by your infrastructure. | Services have dataset size limits like Import Data. Otherwise, infrastructure limits your size. |
| Number of sources | Unlimited | Unlimited | One |
| Security | Row level based on user login | Row level security. Security is defined as the data source for some sources. However, row level security can still be used in Power BI Desktop. | Can use data source security based on current user login |
| Refresh cycle | Based on license: Pro — eight refreshes per day; Premium — unlimited refreshes per day | Shows latest data available in the source. | Shows latest data available in the source |
