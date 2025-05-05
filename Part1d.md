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

You don’t always have to store the data directly in Power BI Desktop. You can always use Desktop to query and load data from external sources. If you prefer to extend your data model with calculated measures or a specific relationship, consider importing the Power BI Desktop file into a Power BI Online site for easier manipulation.  

Databases are a bit different from files because you connect to a live data source — sources requiring an Internet connection which are made available to either a small subset of users or to many users for consumption. This is especially true when the database is available “as a service,” such as Azure SQL Database, Azure Cosmos DB, Azure Synapse Analytics, or Azure HDInsight. Because the data is live, all that a data professional must do is appropriately model the data first. Once satisfied with the intended model, the user can explore the data, manipulate the data, and create data visualizations.  

If you want to explore a plethora of data sources beyond those offered by Microsoft, including open source and third-party options, you need to utilize Power BI Desktop. Online Services offers a narrow range of options, whereas Desktop offers over 100 options for you to choose from.  

When it comes to data ingestion, “dataset” and “data source” are treated the same, even though they’re actually just distant relatives that support the same mission. You create a dataset in Power BI whenever you use the Get Data feature. It’s what allows you to connect and import data, including from live data sources.  

A dataset stores all the details about the data source and its security credentials. A data source is where all the data stored in the dataset is derived, which can be a proprietary application data source, a relational database, or a stand-alone file storage alternative such as a hard drive or file share.

## Building Data Models  
Power BI is a data-model-based reporting tool. A data model is a reusable asset that, when tweaked a little depending on the business need, can dramatically reduce development efforts and cut costs.  

Sometimes, you get lucky and can build new assets on top of the existing solution. At other times, recycling the asset with a few enhancements can score you the desired results. These are the key characteristics of data models:  
- Tables hold meaningful data.
- Relationships exist between the loaded tables with data.
- Formulas, also known as measures, apply business rules to the raw data to extract, transform, and load data to create meaningful business insights.

With BI solutions such as Power BI, users are able to streamline business issues with a data model. To summarize, models are useful for these reasons:  
- **Reusability:** Users can solve a reporting requirement or business challenge
using a formulaic approach without having to reinvent queries or
rebuild datasets.
- **Management:** Business users are in a position to manage the data on their own after models are built. Seldom is a database expert or technical professional needed to handle infrastructure requirements.
- **Adaptive models:** You can build a logical model with minimum code. Changes are commodative to technical and business requirements, including the use of measures (formulas) and rule sets.

## Analyzing Data
Before sharing any data with a team, you first have to carry out your own, personal data analysis using Power BI Desktop. You can conduct several forms of analysis. At the most basic level, when the data enters the system, you have to review it to make sure it looks right and appears as it should. If it doesn’t, you manipulate the data by cleansing it, a task often carried out by an analyst or
engineer.
