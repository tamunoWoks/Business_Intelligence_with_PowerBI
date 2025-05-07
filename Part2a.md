## Preparing Data Sources
The modern organization has a lot of data. Enterprise software vendors such as Microsoft have built data source connectors to help organizations import data into applications such as Power BI. Connecting to data sources isn’t necessarily the tricky part, it’s often the data transformation that takes a bit of time.

### Getting Data from the Data Source
Without a data source, it’s hard to use Microsoft Power BI. You can connect to your own data source or use one of the many connectors Microsoft makes available to users as part of Power BI Desktop or Services. Before you begin loading data, you must first grasp what the business requirements are for your data source. For example, is the data source local to your desktop with occasional updates? Is your data perhaps coming from a third-party data source that supplies real-time feeds? The requirements for both scenarios are vastly different.  

Microsoft continually adds data connectors to its Desktop and Services platform. As a result, Power BI offers well
over 100 data connectors. The most popular options include files, databases, and web services.  
You can find a list of all available data sources at `https://docs.microsoft.com/en-us/power-bi/connect-data/powerbi-
data-sources`.  

To correctly map your data in Power BI, you must determine the exact nature of the data. For example, would you use the Excel Connector if the document type were meant for an Azure SQL database?  

When you load data into Power BI Desktop, the data is stored as a snapshot in time. To ensure that you view the latest data, you click the Refresh Preview button on the home screen every so often.
