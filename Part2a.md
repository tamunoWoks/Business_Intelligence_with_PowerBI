## Preparing Data Sources
The modern organization has a lot of data. Enterprise software vendors such as Microsoft have built data source connectors to help organizations import data into applications such as Power BI. Connecting to data sources isn’t necessarily the tricky part, it’s often the data transformation that takes a bit of time.

### Getting Data from the Data Source
Without a data source, it’s hard to use Microsoft Power BI. You can connect to your own data source or use one of the many connectors Microsoft makes available to users as part of Power BI Desktop or Services. Before you begin loading data, you must first grasp what the business requirements are for your data source. For example, is the data source local to your desktop with occasional updates? Is your data perhaps coming from a third-party data source that supplies real-time feeds? The requirements for both scenarios are vastly different.  

Microsoft continually adds data connectors to its Desktop and Services platform. As a result, Power BI offers well
over 100 data connectors. The most popular options include files, databases, and web services.  
You can find a list of all available data sources at `https://docs.microsoft.com/en-us/power-bi/connect-data/powerbi-
data-sources`.  

To correctly map your data in Power BI, you must determine the exact nature of the data. For example, would you use the Excel Connector if the document type were meant for an Azure SQL database?  

**To connect to a file using the Excel Connector with Power BI Desktop, follow these steps:**
- On the Excel Home tab, click either the Excel button or the Get Data button, and then choose Excel from the drop-down menu that appears.
- In the Open window, navigate to the particular file, click to select it, and then click Open.
- With the file open, head to the Navigator and select all check boxes on the left.
- Click the Transform Data button.  
After you click Transform Data, a new interface appears called the **Power Query Editor**. It’s what loads the data from the two Excel spreadsheet tabs you just clicked on from the previous Power BI screens. But If you’d gone with Load, you’d have to make modifications to your dataset manually.  

When you load data into Power BI Desktop, the data is stored as a snapshot in time. To ensure that you view the latest data, you click the Refresh Preview button on the home screen every so often.  

Loading folders with data inside them can present a few unique challenges. Though you can point to a folder and ingest just about any type of file, it’s another matter to replicate a folder structure using the Power Query Editor. When you load data in Power BI stored inside a folder, you should ensure that the same file type and structure exist. An example is a series of Microsoft Excel or Google Sheet files that would be complimentary.  

The difference between the Combine and Transform Data option and the Transform Data option comes down to the file type and structure. Assuming that each file is similar and can create consistent columns, you can likely use the Combine and Transform Data option to bring everything into a single file. Otherwise, you’re better served using the Transform Data option, since there is usually a single file structure.  

Most users, if they can point to the file path or if they know the database connection and security credentials or if they know the URL and associated parameters, can configure their data sources in no time. Power BI’s Power Query feature automatically detects the nuances in the connection and applies the proper transformations.  

### Managing Data Source Settings
Commonly, your dataset requirements change over time. That means if the data source changes, so will some of the settings that were initially loaded when you configured Power BI. Suppose you move a folder containing files from `C:\Desktop` to `C:\Documents`. Such a change in folder location would require you to modify the data source settings.
