## Tableau Interview Questions and Answers

### What is Tableau?
- Tableau is a powerful data visualization tool used in the business intelligence industry.
- It simplifies the raw data into a very easily understandable format.
- It visualizes and creates interactive, sharable dashboards.
- Tableau is not required any technical or programming skills.

### Explain the features of Tableau?
- **Data Blending**: Data blending is an essential feature in Tableau. It is used when we combine related data from multiple data sources, which you want to analyze together in a single view, and represent in the form of a graph.
- **Real-time Analysis**: Real-Time Analysis makes users able to quickly understand and analyze dynamic data when the Velocity is high, and real-time analysis of data is complicated. Tableau can help extract valuable information from fast-moving data with interactive analytics.
- **The Collaboration of Data**: Data analysis is not isolating task. That's why Tableau is built for collaboration. Team members can share data, make follow up queries, and forward easy-to-digest visualizations to others who could gain value from the data. Making sure everyone understands the data and can make informed decisions is critical to success.

### Explain all data terminologies in Tableau?
There are several types of data terminologies in Tableau, such as:
**Bookmark**: A .tbm document in the bookmarks folder in the Tableau repository that contains a single worksheet. It helps in improving data analysis. Unlike, web browser bookmarks, .tbm files are a compatible way to display various studies quickly.
**Workbook**: A workbook is a file with .twb extension that holds one or more worksheets as well as dashboards and stories.
**Dashboard**: The dashboard is a combination of several views that are arranged on a single page. In Tableau, dashboards are used to observe and compare a variety of data together, and also it allows interacting with other worksheets.
**Data Source Page**: Data Source is a page where you can set up your data source. Does this data source page generally consist of four main areas? Join area, left pane, a preview area, and metadata area.
**Worksheet**: The worksheet is a collection of sheets. It's a place where you build views of your data by dragging various fields onto the shelves.
**Dimensions**: Dimension is commonly known as a field of categorical data. Dimensions hold discrete data such as members and hierarchies that cannot be aggregated. It also contains characteristic values such as dates, names, and geographical data. The dimensions used to reveal details of your information.
**Measures**: measures are the measurable quantities of the data, which can be analyzed by a dimension table. Measures are stored in a table which contains foreign keys referring uniquely to the associated dimension tables. The table supports data storage at the atomic level and thus, allows the number of records to be inserted at one time.
For example, a Sales table can have a product key, customer key, promotion key, items sold, referring to a specific event.
**Filters shelf**: Filter shelf is located on the left side of the workbook. Filters shelf is used to exclude the data from a view by filtering it using both dimensions and measures.
**Pages shelf**: Page shelf is on the left side of the view. With the help of the page shelf, you can split a view into a sequence of pages based on the values and members in a continuous or discrete field. Adding a field with the pages shelf is similar to adding a field in rows shelf. For each new row, a new page is created.
**Marks card**: Marks card is on the left side of the worksheet. The user can drag fields to the control mark properties such as color, type, shape, size, label, detail, and tooltip.

### What is the difference between .twb and .twbx extension?
**.twb**
- A .twb is an xml document that contains the information about your dashboards, sheets, and stories.
- A .twbx is a package of files "compressed" together.
**.twbx**
- It doesn't contain any data so to share your workbook, and you have send both workbook file and the data source file of Tableau.
- It includes data source file and any other file used to produce the workbook, including images.

### What are the different data types in Tableau?
Tableau expresses fields and assigns data types automatically. If the data source appoints the data type, Tableau will use that data type. If the data source doesn't individually assign a data type, Tableau will assign one. Tableau consist of the following data types:
- Date values
- Text values
- Numerical values
- Date and time values
- Boolean values (True or False conditions)
- Geographic values (longitude and latitude used for maps)

### Explain the different connections you can make with your datasets?
We can connect the datasets in two ways, such as:
- **Live**: Live connection sends queries to your database and retrieves data. These queries will return whatever data is currently in the database.
- **Extract**: Extracts connection saved subsets of data that use to improve performance or to take the advantages of Tableau functionality which are not supported or available in your original data.

### What are the Sets?
Sets are used to create subsets of data based on the specific condition defined by the user. Sets are only created based on the dimension field.

There are two types of sets in Tableau, such as:
- **Dynamic Sets**: The values or members in the dynamic sets get change when the underlying data changes.
- **Fixed Sets**: The values or members in the fixed sets does not change when the underlying data changes.

### What are Groups?
A group is a combination of the members of the dimension which make higher-level categories.

### What is the Hierarchical Field?
In Tableau a hierarchical field is used for drilling down data. It means viewing your data at a more granular level.

### What is a Tableau Data Server?
Tableau server acts as a middle man between the data and Tableau uses. Tableau Data Server allows you to share and upload data extracts, preserve database connections, as well as reuse calculations and field metadata.

### How to create a Calculated Field in Tableau?
1. Click on the drop-down option to the right of dimension on the data pane and go to the create options and select the calculated field to open the calculation editor.
2. Name the calculated field and create a formula.

### What is the difference between Data Joining and Data blending?
Data joining: Data joining is used when you are combing the data from the same source.	
Data blending: Data blending is required two completely defined data sources in a report.

### What is the difference between discrete and continuous data in Tableau?

| Discrete                                                             | Continuous                                                  |
| -------------------------------------------------------------------- | ----------------------------------------------------------- |
| Discrete data is the value that is counted as distinct or separate.  | Continuous data is used to measure continuous data.         |
| Only It can take individual values within a range.                   | It can take any values within a finite and infinite range.  |

