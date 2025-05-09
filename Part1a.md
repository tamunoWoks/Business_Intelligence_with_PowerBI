## INTRODUCTION
What does Business intelligence require?  
-	Querying data sources
-	Reporting & Caching data
-	Visualizing data.  

On a broader scope, business intelligence requires taking structured, unstructured and semi-structured data and make sense of it. It also entails delivering robust business analytics outputs for executive consumption and delivering complex reports, visualizations, dashboards and KPIs.  

Power BI allows users to visualize and discover what is truly essential in their vast data resources. Users can share data at scale with ease, and depending on your role you can create, view or share data using Power BI via the desktop app, the cloud-based service, or the mobile app.  

## WHAT IS DATA?
Data refers to raw facts, figures or information that can be in the form of numbers, text, images, audio, video or any other format.  

**Key characteristics of data include:**
-	It is usually raw and unprocessed
-	It can be structured (e.g., spreadsheets, databases), semi-structured or unstructured (e.g., social media posts, emails, videos).
-	It can be quantitative (e.g., temperature, sales figures) or qualitative (e.g., customer feedback, interview responses).  
Data should not be confused with information. Data is usually raw and unprocessed while information is processed, structured and meaningful data that provides contest.  

**Examples of Data:**
-	Numbers: Sales records, temperatures, stock prices.
-	Text: Social media posts, books, emails.
-	Media: Photos, videos, audio recordings.
-	Sensor Data: GPS signals, health tracker metrics. 

#### STRUCTURED DATA
Structured data conforms to a tabular format; this means each column and row maintains an interrelationship. A formal specification of tables with rows and columns is commonly referred to as **DATA SCHEMA**.  

The most accessible data sources for Power BI are structured. Platforms such as Microsoft SQL Server, Microsoft Azure SQL Server, Microsoft Access, Azure Table Storage, Oracle, IBM DB2, MySQL, PostgreSQL, Microsoft Excel, Google Sheets and several others all offer robust structured data options.  

#### UNSTRUCTURED DATA
Unstructured data is ambiguous, without any rhyme, reason, or consistency. Any video, audio, photo, or text file is considered unstructured data. 

#### SEMI-STRUCTURED DATA
Semi-structured data has some formality, but it isn’t stored in a relational system, and it has no set format. Semi-structured data contains tags that make the data easier to organize in some form of hierarchy.  

Non-relational data systems or NoSQL databases are best associated with semi-structured data.

## BIG DATA
Big data is a concept where the business and data analyst will evaluate extremely large datasets which may reveal patterns and trends relating to human behavior and interactions that are not easily identifiable without the use of specific tools.  
A typical big data collection is often expressed in millions of records.  

Power BI can evaluate many data sources and millions of records simultaneously. The sources don’t need to be structured; they can be unstructured or semi-structured.   

Across the Power BI platforms, you are certain at some point to encounter one (or more) of the following products:
**POWER QUERY**  
Power Query is a data connection tool you can use to transform, combine, and enhance data across several data sources. With Power BI’s Power Query you can extract data from numerous data sources as well as read data from relational sources.   
If you’re looking to extract data from unstructured, semi-structure, or application sources, Power Query makes that possible as well. You can also use Power Query to mine platforms such as LinkedIn, Facebook, or Twitter if you have access to API services that map to specific data fields on the platforms.  

The procedure for using Power Query is always the same: It transforms the data you specify by adding columns, rows, data types, date and time, text fields, and appropriate operators making it ready for consumption.   
The product produced by the Power Query output in the Editor can then be transferred to either a portable file such as Excel or something more robust, such as a Power Pivot model.  
Working behind the Power Query scenes is a formula language called M, but M never shows its face as part of the graphical user interface.

**POWER PIVOT**  
Power BI’s data modeling tool is called Power Pivot. With it, you can create models such as star schemas, calculated measures, and columns and build complex diagrams. Power Pivot leverages another programming language called the Data Analysis eXpression Language (DAX). It is a formula-based language used for data analysis purposes.

**POWER VIEW**  
The visualization engine of Power BI is Power View. You can use Power View to generate interactive charts, graphs, maps and visuals. The idea is to connect to data sources, fetch and transform that data for analysis, and then have Power View present the output using one of its many visualization options.  

Power View gives users the ability to filter data for individual variables or an entire report. Users can slice data at the variable level or even break out elements in Power View to focus on data that may be considered anomalous.

**POWER MAP**  
This is a visualization toll for creating 3d map renderings. Sometimes, visualizing data requires a bit more than a Bar chart or a table. If you need a map that integrates geospatial coordinates with 3D requirements or you’re looking to add dimensionality to your data with the help of heat maps, in that case, you want to consider Power BI’s Power Map feature set.  

Another feature built into Power Map is the use of geospatial capabilities using Microsoft Bing. A user can highlight data using geocoordinate latitude and longitudinal data as granular as an address or as global as a country.

**POWER Q&A**  
Power Q&A is an artificial intelligence engine that allows you to ask questions and receive responses using plain language which works in conjunction with Power View.  
It is a natural language engine that interprets text, numbers, and even speech so that users can query the data model directly.  

A classic example of a situation where Power Q&A can be enormously helpful would involve determining how many users have purchased a specific item at a given store location. If you want to drill down further, you could analyze a whole set of metrics.  
The possibilities are endless if you’ve built your data model to accommodate the questions.

**POWER BI DESKTOP**  
Power BI desktop is a free, all in one solution that brings all the apps described above together into a single graphical user interface.  Using Power BI Desktop, you can complete all your business intelligence activities under a single umbrella.   

Microsoft updates Power BI Desktop features monthly, so you can always be on the BI cutting edge.

**POWER BI SERVICES**  
This is a cloud-based user experience to collaborate and distribute products such as reports with others. It functions as the Software as a Service companion to Power BI.  

Power BI Services allows users to collaborate and share their dashboards, reports, and datasets with other users from a single location. The version of Power BI you have licensed dictates your ability to share and ingest data.

## POWER BI TERMINOLOGY
Power BI has its own glossary. These terminologies are referred to as concepts and they resonate across vendors.  

**Capacities:**  
Capacities are the sum of resources needed to complete any project you may create in Power BI. Resources include the storage, processor, and memory required to host and deliver the Power BI projects.  

There are two types of capacity:  
- **Shared:** A shared capacity allows you to share resources with other Microsoft end users.   
- **Dedicated:** A dedicated capacity fully commits resources to you alone.

**Workspaces:**  
Think of a workspace as a container that allows you to manage the entire lifecycle of dashboards, reports, workbooks, datasets, and dataflows in the Power BI Services environment.  

Workspaces are a means of collaborating and sharing content with colleagues. Whether it’s personal or intended for collaboration, any workspace you create is created on capacities.  

Features that come with collaboration include the ability to create and publish Power BI-based dashboards, reports, workbooks, datasets, and apps with a team.

**Dataflow:**  
A dataflow is a collection of tables that collects the datasets imported into Power BI. After the tables are created and managed in your workspace, you can add, edit, and delete data within a dataflow. The data refresh can occur using a predefined schedule as well.  

Power BI uses an Azure data lake, to store the extremely large volumes of data necessary for Power BI to evaluate, process, and analyze data rapidly. The Azure Data Lake also helps with cleaning and transforming data quickly when the datasets are voluminous in size.  

Unlike a dataflow (which is a collection of tables), a dataset should be treated as a single asset in your collection of data sources.  
Think of a dataset as a subset of data. When used with dataflows, the dataset is mapped to a managed Azure data lake.

**Reports:**  
Power BI Reports translates transformed data into one or more pages of visualizations (Line charts, Bar charts, donuts, treemaps, etc). You can either evaluate your data at a high level or focus on a particular data subset.  

You can tackle creating a report in a number of ways, from taking a dataset using a single source and creating an output from scratch to importing data from many sources.  

Power BI offers two Report view modes: 
- Reading view 
- Editing view.

When you open a report, it opens in Reading view. If granted Edit permissions, you can edit a report. When a report is in a workspace, any user with administrative, member, or contributor rights can edit a report.  

Administrative, member, or contributor access grants you access to exploring, designing, building, and sharing capabilities within Edit view. Users who access the reports created by these users can interact with reports in Read-Only mode. That means they can’t edit it, they can only view the output.  

Reports created by privileged users are accessible under a workspace’s Reports tab. Each report represents a single-page visualization, which means it’s based on only one dataset.

**Dashboards:**  
Power BI dashboard, also known as **Canvas**, brings your data story to life. Think of it as a blank canvas. As you build your reports, widgets, tiles, and key performance indicators (KPIs) over time, you pin the relevant ones to the dashboard to create a single visualization.  

The dashboard represents the large dataset that you feel covers your topic at a glance. As such, it can help you make decisions,
support you in monitoring data, or make it possible for you to drill down in your dataset by applying different visualization options.  

To access a particular dashboard, you must first open a workspace and then click the Dashboards tab. Keep in mind that every dashboard represents a customized view of an underlying dataset.  

If you own a dashboard, you have permission to edit it. Otherwise, you have only read-only access. You can share a dashboard with others, but they may not be able to save any changes.

**Navigation pane:**   
All the capabilities discussed to this point are labels found in the Navigation pane. You would use the Navigation pane to complete actions to locate and move between a workspace and the various Power BI capabilities you want to use (dashboards, reports, workbooks,
datasets).  

Your Navigation pane options are endless. A user can:
- Expand and collapse the Navigation pane.
- Open and manage your favorite content with the help of the Favorites option.
- View and open the most recently visited section of content.  

## Business Intelligence (BI)
Simply put, Business Intelligence commonly abbreviated as `BI` is what businesses use to analyze current as well as historical data. Throughout the process of data analysis, the hope is that an organization will be able to uncover the insights needed to make the right decisions for the business’s future. By using a combination of available tools, an organization can process large datasets across multiple data sources in order to come up with findings that can then be presented to upper management.  

Using the enterprise BI tool, interested parties can produce visualizations via reports, dashboards, and KPIs.  
Many tools allow for collaboration and sharing among groups, because data changes over time.  

Here are four actions BI tools allow to transform raw data into readily accessible data:  

**Collect and transform your data:**  
When using multiple data sources, BI tools allow you to extract, transform, and load (ETL) data from structured and unstructured sources. When that process is complete, you can then store the data in a central repository so that an application can analyze and query the data.  

**Analyze data to discover trends:**  
The term data analysis can mean many things, from data discovery to data mining. The business objective, however, is all the same: It all boils down to the size of the dataset, the automation process, and the objective for pattern analysis.  

BI often provides users with a variety of modeling and analytics tools. Some come equipped with visualization options, and others have data modeling and analytics solutions for exploratory, descriptive, predictive, statistical, and even cognitive evaluation analysis.  

**Use visualization options in order to provide data clarity:**  
You may have lots of data stored in one or more repositories. Querying the data to be understood and shared among users and groups is the actual value of business intelligence tools. Visualization options often include reporting, dashboards, charts, graphics, mapping, key performance indicators, and datasets.

**Taking action and making decisions:**  
The process culminates with all the data at your fingertips to make actionable decisions. Companies act by taking insights across a dataset. They parse through data in chunks, reviewing small subsets of data and potentially making significant decisions.  

Companies embrace business intelligence because it helps them reduce inefficiency, correct problems, and adapt the business to support market conditions.
