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

### Analyzing Data
Before sharing any data with a team, you first have to carry out your own, personal data analysis using Power BI Desktop. You can conduct several forms of analysis. At the most basic level, when the data enters the system, you have to review it to make sure it looks right and appears as it should. If it doesn’t, you manipulate the data by cleansing it, a task often carried out by an analyst or
engineer.  

Once the data source has been cleaned up and you’ve mapped the data into refined datasets, it’s time to create the necessary visualizations, pictures that can serve as examples of your data sources — charts, maps, indicators, and gauges. You’ll find these visuals in deliverables such as reports and dashboards. Even the Q&A feature in Power BI produces visuals after you ask focused questions.  

You eventually want to get to a point in your use of Power BI where you can rapidly generate reports and access data using dashboards. A Power BI designer builds out dashboard visualizations, referred to as tiles, using data in reports and datasets. A user can build their own dashboards for personal use or share the dashboard with others. (Note: If you share dashboards, security credentials are tied to each
visual.)  

### Creating and publishing items
If you want to post that data project on the web in a read-only format to a limited audience. And you certainly can for free. Suppose, however, that you want others to edit and collaborate with you beyond read-only support. In that case, you must pay for such features.  

When you publish items from Power BI Desktop to Power BI Services, the files are workspace bound. Similarly, if you’ve produced any reports, they appear in Report view. Datasets migrate from the desktop with the same name, as do any reports to the workspace. The relationship is often a one-to-one relationship, with rare exceptions.  

In Power BI Desktop, you can publish your files by choosing Publish ➪ Publish to Power BI from the main menu or selecting Publish on the Ribbon.  

When you publish an item from the Power BI Desktop to Services, you’re performing the same action as using the Get Data feature. That means connecting to a data source, uploading a file from Power BI Desktop, and sending it to Services.  

Saving in Power BI Services doesn’t make changes to the original Power BI Desktop file. Therefore, don’t expect any updates when you or your colleagues add, delete, or change any dataset, visualization, or report.

## Power BI Services
Services aren’t intended for a single user, whereas Desktop supports individual usage exclusively. The purpose of Services is to allow the individual user to publish data from the desktop and then share it with user groups.  

The Desktop user can continually update their data product, whether it is a dataset, data model, or report, after they publish it online using Power BI Services. However, Power BI Services doesn’t refresh the data at the desktop level. Therefore, it’s up to you to keep data in sync.  

Services offers four significant product features beyond Desktop for multiuser access that Desktop doesn’t support: the ability to view and edit reports, access to dashboards based on credentials, collaboration among users, and data refresh options depending on product type purchased.

### Viewing and editing reports
The report lifecycle generally begins when a user sets up a dataset and builds a functional data model in Power BI Desktop. The user also crafts one or more reports. Once a report is developed, you can then publish it to Power BI Services. The workflow is typical, as refinement with complex data makes it easier to build a report deliverable offline. You can assume that you don’t need an Internet connection to access the dataset.  

Sometimes you might require online services access because you have large datasets from third-party applications. Everyday use cases include when you have a subscription to CRM or ERP solutions requiring data connections. Assuming that you are part of an organization and have access to a service (SaaS) app, you’ll find someone in your organization whose job it is to publish apps. That person generally
distributes the app, granting you access to specific features and data. With Power BI Services, you connect to these apps to generate reports specific to your business need.  

Though you can directly connect to data sources such as databases, files, and folders in Power BI Desktop, applications are different. You need Power BI Services to access app data.

### Sharing your results
Once you create reports or dashboards, you can share them with users who are given Power BI Services accounts. The type of license in force dictates how the user can interact with the data. Some users may be able to view only the reports and dashboards, and others may be able to collaborate fully. For you and your colleagues to manage a report or dashboard, a workspace may be established. You bundle and distribute
the deliverable as an app. Once you share the dataset, it becomes the basis for a new set of dashboards or reports.  

A Power BI report, by default, supplies a holistic view of a dataset. It has visuals representing findings from one or more datasets. Reports may hold a single visualization or many.  

### Why reports are valuable
The basis of a report is a single dataset, whereas a dashboard collects many reports. With reports, you get a laser-focused view of a topic. Moreover, data is static in a non-data-model-based application; such is not the case in a tool such as Power BI. The visuals are dynamic because, as the underlying data updates, so do the reports in real time. In addition, a user is free to interact with the visuals as little or as much as they want in a report. They can also use reports to filter and query in a variety of different ways within Power BI. Reports are highly interactive and even customizable based on your organizational role and responsibility.

### Accessing reports from many directions
You should consider two basic scenarios when it comes to report access: Either you created the report yourself and imported it from Power BI Desktop or someone has shared a report with you. Any report that you imported is on your My Workspace.  

Within the framework of these two scenarios, access might come about as  
- Reports shared directly, for example, by email
- Reports shared as part of an app
- Reports accessible from the dashboard.
- Recent or favorite reports, dashboards, apps, and workspaces accessible from the Services Navigation pane.

Among these options, the three most common ways users view and edit reports when collaborating are:
a. Sharing directly.  
b. Sharing as part of an app.  
c. Accessing the dashboard.  

To open a report that is shared with you, follow these steps:
1. Open Power BI Services, located at https://app.powerbi.com.
2. Select Home in the Navigation pane. (The Home canvas appears)
3. Click the Shared with Me icon.
4. Then, select a report found on the Shared with Me page.

The second choice is receiving an app from someone directly or accessing the app using Microsoft’s AppSource. You access these apps either from the Power BI home screen or from the Apps and Shared with Me items found on the Navigation pane.  

Someone who wants to open an app must first either acquire a Power BI Pro license or have an app workspace stored in a Power BI Premium capacity.  

To access reports from an app, you need to navigate to the app source. Here’s one example of how you’d do it:  
1. Point your browser to the app source’s location, such as https://appsource.microsoft.com.
2. Select the Power Platform check box.
3. Using the Search box at the top of the screen, search for Microsoft sample Sales and Marketing.
4. Click the Get it Now button.
5. On the new page that appears, choose Continue ➪ Install to install the app in the Apps canvas.
6. Open the app in the Apps canvas or Home canvas.

You can also open reports from a dashboard. Most times, a tile is a snapshot of a pinned report. When you double-click the tile, a report will open. To open a report from a dashboard, follow these steps:  
1. From the dashboard, select any tile.
2. Drill down into a more granular view of the report data by clicking on data points within a report.

### Working with dashboards
A dashboard lets you tell a story from a series of visualizations. A dashboard must be well designed, because it contains the critical highlights so that a reader can drill down into related reports and view
details later.  

Dashboards are available only with Power BI Services. You can create dashboards with a Power BI Free license, but this feature isn’t integrated into Power BI Desktop. Therefore, once you build your reports in Power BI Desktop, you need to publish outputs to Power BI Services. Keep in mind as well that, although dashboards can be created only on a desktop-based computer, you can view and share dashboards on all device form-factors, including Power BI Mobile. When you want to create a dashboard, you need to have at least one or more reports pinned to a blank canvas. Each tile represents a single report based on a single dataset.

## Collaboration with Power BI Services
The transition from Power BI Desktop to Power BI Services is partially due to collaboration as you’re unable to collaborate with others using Power BI Desktop. You may want to share with a small subset of users, or perhaps the group of users you’re looking to share information with is distributed.  
Depending on the Power BI Services option you’re working with, you have these options:  
- **Using workspace:** The most common way to share reports and dashboards is by using the workspace. Suppose that another user is given access to a report or dashboard. In that case, the user either views or edits the workspace area in Power BI Services.  
- **Using Microsoft Teams:** Using the Chat feature in Teams allows for collaborating on reports and dashboards with Power BI.
- **Distributing your reports and dashboards via an app:** If your results are focused, the user can build a single app and create a working executable for sharing among other users.
- **Embedding reports and dashboards on websites:** Sometimes, the reports and dashboards you create might be helpful for targeted public consumption on an external or internal facing website. You can create an iteration of a Power BI report or dashboard that’s viewable. Any user who visits that website may view the data if they’re assigned permission to do so.
- **Printing reports:** When in doubt, you can always print your reports and distribute paper copies. Of course, each time the data is refreshed, you need to print a new copy of the report. For dashboards, each output is printed separately.
- **Creating a template app:** If your deliverables are repetitious, distribute them so that Power BI users can access them using the Microsoft AppSource. One must assume that these items are publicly consumable for other businesses to use.

## Refreshing data
Every time you access a report or a dashboard on Power BI Services, you must query the data source. If there are new data points, the results are updated in the dataset as part of the visualization. Depending on the refresh requirements, one or more processes might be needed. The refresh process consists of several phases, depending on the storage operation required for the dataset. You have two concepts to consider: storage mode as well as data refresh type.  

### Storage modes and dataset types
Power BI offers several modes for allowing access to data in a dataset:  
- **Import mode:** Datasets are imported from the original data source into the dataset. Power BI can query the reports and dashboards submitted to the dataset and return results from the imported tables and columns. You may find this to be a snapshot copy — a dataset representing a moment in time. Each time Power BI copies the data, you can query the data to fetch the changes.
- **DirectQuery/LiveConnect:** Two connection types that don’t rely on importing data directly are DirectQuery and LiveConnect. Data results come in from the data source whenever the report or dashboard queries the dataset. Power BI will then transform the raw data into usable datasets. Only DirectQuery mode, though, requires that Power BI not use queries using the Power Query Editor Extract Transform Load (ETL) engine. The reason for this is that the queries are processed directly using Analysis Services, without having to consume resources. Data refreshes aren’t required because no imports occur in the Power BI Desktop environment. Features that are still updated include tiles and reports, whereby the data updates about every hour. The schedule can be changed to accommodate business needs.
- **Push mode:** In Push mode, there’s no formal definition for a data source, so there’s no requirement for a data refresh. Instead, you push the data into the dataset through an external service, which is quite common for real-time analytics processes in Power BI.

### Data refresh types
For a Power BI user, data refreshes are defined as importing data from the original data sources into one or more datasets. The refresh is based on a schedule or can be in real time. Depending on the procured Power BI license, the refresh rate varies from 8 updates to as many as 48 per day. You’re limited to 8 daily dataset refreshes for shared capacity, which are executed by the schedule using a plan. The updates reset daily at 12:01 AM.  

A Power BI refresh operation can have multiple refresh types, including a standard data refresh, OneDrive refresh, query cache refresh, tile refresh, dashboard refresh, and course visualization refresh. Power BI decides the individual refresh steps with each of these examples. A precedence must be applied based on operational complexity.  

Regardless of the refresh approach, you must ensure that reports and dashboards use current data for a business to be successful. If, for some reason, you find that your data is stale, address the problem with the data owner or the gateway administrator.  
When refreshing data, keep the following points in mind:
- For optimal performance, schedule refresh cycles for off-peak business hours, especially if you use Power BI Premium.
- Consider the number of refreshes your organization is allowed with your license and the volatility of your data. Refresh only when you know it makes sense.
- Make sure the dataset refresh doesn’t exceed the refresh duration, or else the data won’t refresh properly, causing business issues with your options.
- Optimize your data by including only the data needed to operate in the environment necessary for your reports and dashboards. Any extra overhead
can be costly, especially when it comes to memory and processing overhead consumption.
- Apply the appropriate security settings for both Power BI Desktop and Power BI Services. The settings don’t carry over from one environment to another.
- Be mindful of the visuals used as more outputs result in performance degradation and potential data refresh issues down the line.
- Use only reliable data gateways to connect data sources, whether on-premise or cloud-based. If data refresh failures happen, you may need to deploy additional infrastructure to handle needed capacity.
- If data refresh failures happen, put a notification method in place so that you can quickly deal with any technical concerns.
