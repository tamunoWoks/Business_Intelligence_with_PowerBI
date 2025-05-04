## Power BI Highlights
The data sources power BI users can connect to aren’t limited to local repositories. Users can aggregate sources locally with third-party data that is structured or unstructured to create data models. The data model lets the user build a visual representation of the stored datasets. When you have many visuals, the user can derive reports or dashboards for analysis.  
A typical usage of Power BI Desktop is:  
- Ingest data across one or more data sources.
- Model data to create reports and dashboards.
- Refine, cleanse, and visualize the data by way of analysis.
- Create reports for individual consumption.

Though you can complete these activities online, the Desktop platform is purpose-built for individual user consumption or development work. It isn’t intended for groups and not until the user is ready to share the products created using Desktop do you need to expose anything to Power BI Services.  
The end user gains access to three distinct views in Power BI Desktop: Report, Data and Model. Each Power BI Desktop view carries out specific tasks:  
- **Report:**
You can create reports and visualizations after you’ve ingested and modeled the data. Users spend most of their time here post-data ingestion, transformation, and modeling.
- **Data:**
You can find all data ingested, or migrated, from tables, measures, and data sources associated with reports and visualizations created here. Sources can be local to the desktop or from a third-party data source accessible over the web.
- **Model:**
Like creating a relational data model in Microsoft SQL Server, Azure SQL Server, or even Microsoft Access, you can fully manage the relationships among the structured tables you’ve created after you’ve ingested the necessary data using Power BI.  

### Ingesting Data  
Each dataset comes from a particular data source, either found on your local desktop or acquired from other online data sources. These sources may be Microsoft-based applications, a third-party database, or even other application data feeds.  

In Power BI Desktop, you either use the Power BI Ribbon or click the Power BI Data Navigation icon, to access a data source.  

### Files or Databases?  
In Power BI, you can create or import content yourself. When it comes to the type of content users can create or import, it boils down to either files or data stored in a database. Files can be a bit more complicated than databases.  

You need to get the data, transform the data, and then import the data into a readable form. Suppose that you want to import an Excel or .csv file that includes many data types. First, you load the data into Power BI. Then you format the data into a Power BI-ready format in conjunction with dataflows, which transforms the data to support a data model. Finally, you query the data using the Get and Transform feature in Power Query.

### NOTE:  
If the data you’re trying to import isn’t structured or perhaps you don’t want it housed in Power BI Desktop? Your best choice is to use native Microsoft options such as OneDrive for Business.  

Where you store your data makes a difference when dealing with data refresh. Consider the frequency of data updates when selecting the data storage location. When the data is on your local desktop, you’ll generally find better performance, even with large datasets. With shared data accessible over the Internet, you are reliant on network connectivity and other users accessing the data source. Data stored on the desktop is managed by one person — you.  

