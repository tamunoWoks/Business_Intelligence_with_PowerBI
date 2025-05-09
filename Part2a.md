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
1. On the Excel Home tab, click either the Excel button or the Get Data button, and then choose Excel from the drop-down menu that appears.
2. In the Open window, navigate to the particular file, click to select it, and then click Open.
3. With the file open, head to the Navigator and select all check boxes on the left.
4. Click the Transform Data button:  
*After you click Transform Data, a new interface appears called the **Power Query Editor**. It’s what loads the data from the two Excel spreadsheet tabs you just clicked on from the previous Power BI screens. But If you’d gone with Load, you’d have to make modifications to your dataset manually*.  

When you load data into Power BI Desktop, the data is stored as a snapshot in time. To ensure that you view the latest data, you click the Refresh Preview button on the home screen every so often.  

Loading folders with data inside them can present a few unique challenges. Though you can point to a folder and ingest just about any type of file, it’s another matter to replicate a folder structure using the Power Query Editor. When you load data in Power BI stored inside a folder, you should ensure that the same file type and structure exist. An example is a series of Microsoft Excel or Google Sheet files that would be complimentary.  

**To make sure that happens, be sure to follow these steps:**
1. Go to the Home tab on the Ribbon and click the Get Data button.
2. Choose All ➪ Folder from the menu that appears:  
*Want to try another way? Go to the Home tab on the Ribbon, click New Source, choose More from the menu that appears, and then choose Folder.*
3. Whichever way you select Folder, your next step is to click the Connect button:  
*Pressing the Connect button enables access to a single data source.*
4. Locate the folder path specific to where you’ve stored files on your desktop, then browse to the location where you’ve placed the file similar, eg. `C:\DummiesFiles\TrainingNAICS`:  
*The files from the folder you just selected load into a new screen.*
5. Select one or more tables that have loaded.
6. Once the tables have been selected, click the Combine and Transform Data button:  
*The datasets from the TrainingNAICS.xlsx are now loaded into Power Query Editor.*

The difference between the Combine and Transform Data option and the Transform Data option comes down to the file type and structure. Assuming that each file is similar and can create consistent columns, you can likely use the Combine and Transform Data option to bring everything into a single file. Otherwise, you’re better served using the Transform Data option, since there is usually a single file structure.  

Most users, if they can point to the file path or if they know the database connection and security credentials or if they know the URL and associated parameters, can configure their data sources in no time. Power BI’s Power Query feature automatically detects the nuances in the connection and applies the proper transformations.  

### Managing Data Source Settings
Commonly, your dataset requirements change over time. That means if the data source changes, so will some of the settings that were initially loaded when you configured Power BI. Suppose you move a folder containing files from `C:\Desktop` to `C:\Documents`. Such a change in folder location would require you to modify the data source settings.  

**You can go about making these changes in one of two ways:**
1. Select each query under Queries on the left.
2. Locate Query Settings on the right side of the interface.
3. Under Applied Steps, click Source:  
*Doing so brings up a window pointing to the file path and file source.*
4. Make the updates necessary to match the new requirements:  
*Change the file type or path of the original file for each query with this option.*

Though the steps outlined here may seem easy, they might become laborious because you need to make a change to each file listed for each query. That process can be pretty time-consuming, and, if you have a lot of queries, you’re bound to make errors. That’s why you
want to consider an alternative option where you can change the source location all at once rather than tackle each query independently.  

**Follow these steps for the other method:**
1. On the Power Query Editor’s Home tab, click the Data Source Settings button:  
*A new window opens to make the source location change.*
2. Select all files requiring a change in location by choosing Change Source.
3. Make the changes you want to the source location.
4. (Optional) Change and clear associated security credentials by selecting Edit Permissions or Clear Permissions in this interface.

### Working with Shared versus Local Datasets  
After a dataset is published and shared with others by way of either your own workspace or a shared one, the dataset is referred to as a **shared dataset**.  
Unlike with Power BI Desktop, where you have to continually update the dataset on the local hard drive, a shared dataset is stored on the cloud, which means that, whether it’s stored in your workspace or with others, updates can be more consistent.  

You can find many other benefits to using a shared dataset over a local dataset, including:
- Consistency across reports and dashboards
- Reduction in dataset copying due to centralization of a data source
- The ability to create new data sources from existing sources with little effort.

Though you may have your own needs with a dataset, after a dataset is shared with a team, the desired outputs might be different. In that case, you may want to create a single dataset and allow the other users to develop reports and dashboards from the single dataset.  

Connecting to a published dataset in Power BI Services requires a user to have Build permission. You can also be a contributing member of a shared workspace where a dataset exists. Make sure the owner of the dataset provisions your access according to your business need.  

**You can connect to a shared dataset using either Power BI Desktop or Power BI Services. To accomplish this action, follow these steps:**
1. Using Power BI Desktop, either click the Power BI Datasets button on the Home Tab or click the tab’s Get Data button and then choose Power BI Datasets from the menu that appears:  
*The data is transferred from Power BI Desktop to Power BI Services for you to
consume.*
2. With Power BI Services, you would first go to the workspace you’ve published your data to and then choose New ➪ Report.

Whether you’re using Power BI Desktop or Power BI Services, your ability to connect to a dataset without having to worry about data refresh issues or version control becomes a bit easier. You also have the choice to select Save a Copy in the
Power BI Service next to any report in My Workspace or a shared workspace without having to re-create a dataset. This action is similar to connecting to a dataset using Power BI Desktop, because you create a report without the base data model.  

**NOTE:**  
If you are using a shared dataset and then some buttons become inactive in Power BI Desktop, it is because you’re no longer able to make changes using Power Query Editor. As a result, the data view is also no longer visible.  
However, you can tell whether your dataset is shared or local by looking in the lower right corner of the Power BI Desktop interface, where you can find the name of the dataset and the user accessing the data.  

**If you ever need to change from a shared dataset to a local dataset, follow these steps:**
1. Click the Transform Data label.
2. Select the Data Source Settings option.
3. Modify the data source settings to the dataset you want to connect to instead of the shared dataset.
4. Click the Change button once complete.  

### Storage Modes
You can consume data in many ways using Power BI Desktop and Power BI Services. The most common method is to import data into a data model. By importing the data in Power BI, you’re copying the dataset locally until you commit to a data refresh. Though data files and folders can only be imported into Power BI, databases allow you to use a connection that
supports more flexibility.  

Two alternatives exist with database connectivity:  
- **Import the data locally:** This supports data model caching as well as the ability to reduce number of connections and lookups. By ingesting the model, a user can use all Desktop features offered with Power BI.  
- **Create a connection to the data source with DirectQuery:** With this feature, the data isn’t cached. Instead, the data source must be queried each time a data call is required. Most, but not all, data sources support DirectQuery.

You can also use one of two other methods:  
1. **Live Connection:** Here the goal is to use the analysis services integrated with Power BI Desktop or Power BI Services. Live Connection also supports calculation-based activities that occur within a data model.
2. **Composite models:** Suppose that a user must combine both importing data and DirectQuery, or there is a requirement to connect to multiple DirectQuery connections. In that case, you apply a composite model.
You face some risks, though, when dealing with model security. Suppose, for example, you open a Power Bi Desktop file that is sent from an untrusted source. If the file contains a composite model, the information that someone retrieves from a single source using credentials from a user opening the file can be sent to another data source as part of the newly formed query. Therefore, it’s vital to ensure that your data sources are correctly assigned to only those who need access to the sources.  

#### Dual Mode
The four storage modes — local storage, DirectQuery, Live Connection, and composite models — have data housed in a single location. It’s either local to the user or bound to some server on a network in a data center or the cloud.  

Looking back at the composite model, the storage mode property prescribes where tables are stored in the data model. To view the properties of a table, you can hover over a table. In Power BI, you can do this in either the Fields pane of a report or by accessing the Data view. You can also change the Model view in the Properties pane by finding the Advanced section.
