# Blog Series

## Blog 1

## Blog 2

## Blog 3

## Blog 4 
### Installation 

Power BI Desktop is built for data analysts. So, the tool empowers others with its capacity of creating and publishing reports to Power BI. As we discussed in the previous blogs, Microsoft Power BI Desktop is a companion desktop application to Power BI. Let’s discuss the installation process of Power BI Desktop.   

First, you need to have a window installed on the personal computer. The latest version of Power BI Desktop is supported for the following operating systems. 


* Windows 10 

* Windows Server 2012 R2 

* Windows Server 2012 

* Windows 8 

* Windows 8.1 

* Windows Server 2016 

* Windows Server 2019 

* Windows 11 

 

It is available for both 32-bit(x86) and 64-bit(x64) platforms. To have smooth functionality, 2GB Ram and 1GHz CPUs are recommended.  Apart from that I would recommend you have at least 1440x900 or 1600x900 (16:9) display resolution. It would enhance your user experience. Unfortunately, the software is not compatible with the Linux operating system. 

Step 1 : Download the version of Power BI Desktop that matches with your Windows OS. 

Step 2 : Run the EXE installer and follow the setup steps. 

Also, the Power BI Desktop is available for free in Microsoft Store for you to install.  

After successfully installing the application, the startup screen would be like this.  

![alt text](https://github.com/AsiriSirithunga/Social-Impact-League-Project-/blob/main/Images/blog%204/Picture1.png)

At this point, you can simply sign in with your school or work account. Please remember that it only works with a Microsoft account. You will not be able to sign-in with your Gmail, yahoo.  

After signing into your account, you will get the screen below where you can see your recent reports. Then that is it.  

![alt text](https://github.com/AsiriSirithunga/Social-Impact-League-Project-/blob/main/Images/blog%204/Picture2.png)

The installation is done. In this window you will find a few video tutorials in order to learn the basics that are recommended by the Power BI Desktop team. Obviously, you are free to follow any of these videos according to your preference.   

### User Interface 

After closing your startup window. You will see the interface below. 

![alt text](https://github.com/AsiriSirithunga/Social-Impact-League-Project-/blob/main/Images/blog%204/Picture3.png)

Basically, this is the user interface of the Power BI Desktop. It seems more familiar to you, if you are an office package user. It consists of report view, data view and model view. Each view has unique features.  


#### Report view 

In Power BI Desktop Report view, you can build visualizations and reports. The Report view has six main areas: 

![alt text](https://github.com/AsiriSirithunga/Social-Impact-League-Project-/blob/main/Images/blog%204/Picture4.jpg)

* The pages tab area at the bottom, which lets you select or add report pages. 

* The canvas area in the middle, where you create and arrange visualizations. 

* The Filters pane, where you can filter data visualizations. 

* The Visualizations pane, where you can add, change, or customize visualizations, and apply drill through. 

* The Fields pane, which shows the available fields in your queries. You can drag these fields onto the canvas, the Filters pane, or the Visualizations pane to create or modify visualizations. 

* The ribbon at the top displays common tasks associated with reports and visualizations. 


#### Data view 

![alt text](https://github.com/AsiriSirithunga/Social-Impact-League-Project-/blob/main/Images/blog%204/Picture5.jpg)

* The table pane, where you can see your data in table format. 

* The Fields pane, which shows the available fields in your queries. 



#### Model View 

![alt text](https://github.com/AsiriSirithunga/Social-Impact-League-Project-/blob/main/Images/blog%204/Picture6.jpg)

* Model view shows all of the tables, columns, and relationships in your model. 
* The properties pane, which allows you to change the field properties accordingly. 
* The Fields pane, which shows the available fields in your queries. 

With this blog we hope you understand the big picture of the user interface of Power BI Desktop tools. By going through the whole series, you will be able to create a report which solves a given analysis problem.  


## BLOG 5 
### How Power BI Desktop works
With Power BI Desktop, we can: 

Connect to data, including multiple data sources. 

Shape the data with queries that build insightful, compelling data models. 

Use data models to create visualizations and reports. 

Share our report files for others to leverage, build upon, and share. We can share Power BI Desktop .pbix files like any other files, but the most compelling method is to upload them too the Power BI service. 

Power BI Desktop integrates proven Microsoft query engine, data modelling, and visualization technologies. Data analysts and others can create collections of queries, data connections, models, and reports, and easily share them with others. Through the combination of Power BI Desktop and the Power BI service, new insights from the world of data are easier to model, build, share, and extend. 

### Connect to data 
With Power BI Desktop installed, we're ready to connect to the ever-expanding world of data. To see the many types of data sources available, select Get Data > More in the Power BI Desktop Home tab, and in the Get Data window, scroll through the list of All data sources. 

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20Blog.png)

On the Power BI Desktop Home tab, select Get Data > Web to connect to a web data source.

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20Blog%205%202%20image.png)

In the From Web dialog box, paste the address    https://www.bankrate.com/retirement/best-and-worst-states-for-retirement/ into the URL field, and select OK.

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20Blog%205%203.png)

If prompted, on the Access Web Content screen, select Connect to use anonymous access. 
The query functionality of Power BI Desktop goes to work and contacts the web resource. The Navigator window returns what it found on the web page, in this case an HTML table called Ranking of best and worst states for retirement, and five other suggested tables. You're interested in the HTML table, select it to see a preview. 
At this point you can select Load to load the table or Transform data to make changes in the table before you load it.

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%205%204.png)

When you select Transform data, Power Query Editor launches, with a representative view of the table. The Query Settings pane is on the right, or you can always show it by selecting Query Settings on the View tab of Power Query Editor.

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20blog%205%205.png)

### Shape data 

Now that you're connected to a data source, you can adjust the data to meet your needs. To shape data, you provide Power Query Editor with step-by-step instructions for adjusting the data while loading and presenting it. Shaping doesn't affect the original data source, only this view of the data.

Shaping can mean transforming the data, such as renaming columns or tables, removing rows or columns, or changing data types. Power Query Editor captures these steps sequentially under Applied Steps in the Query Settings pane. Each time this query connects to the data source, those steps are carried out, so the data is always shaped the way you specify. This process occurs when you use the query in Power BI Desktop, or when anyone uses your shared query, such as in the Power BI service.
In the third step, changed type, Power BI recognized whole number data when importing it, and automatically changed the original web Text data type to Whole numbers.

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20blog%205%206.png)

If you need to change a data type, select the column or columns to change. Hold down the Shift key to select several adjacent columns, or Ctrl to select non-adjacent columns. Either right-click a column header, select Change Type, and choose a new data type from the menu, or drop down the list next to Data Type in the Transform group of the Home tab, and select a new data type.

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20blog%205%207.png)

You can now apply your own changes and transformations to the data and see them in Applied Steps.

### Build reports

In Power BI Desktop Report view, you can build visualizations and reports. The Report view has six main areas: 

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20blog%205%208.png)

1.The ribbon at the top, which displays common tasks associated with reports and visualizations.
2.The canvas area in the middle, where you create and arrange visualizations.
3.The pages tab area at the bottom, which lets you select or add report pages.
4.The Filters pane, where you can filter data visualizations.
5.The Visualizations pane, where you can add, change, or customize visualizations, and apply drill through.
6.The Format pane, where you design the report and visualizations.
7.The Fields pane shows the available fields in your queries. You can drag these fields onto the canvas, the Filters pane, or the Visualizations pane to create or modify visualizations.

You can expand and collapse the Filters, Visualizations, and Fields panes by selecting the arrows at the tops of the panes. Collapsing the panes provides more space on the canvas to build cool visualizations.

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20blog%205%209.png)

To create a simple visualization, just select any field in the fields list, or drag the field from the Fields list onto the canvas. 
For Example Our Group Have Made one report which is given below : 

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20blog%205%2010.png)

### Share your work
Now that you have a Power BI Desktop report, you can share it with others. There are a few ways to share your work. You can distribute the report .pbix file like any other file, you can upload the .pbix file from the Power BI service, or you can publish directly from Power BI Desktop to the Power BI service. You must have a Power BI account to be able to publish or upload reports to Power BI service.
To publish to the Power BI service from Power BI Desktop, from the Home tab of the ribbon, select Publish.

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20blog%205%2011.png)

You may be prompted to sign into Power BI, or to select a destination.
When the publishing process is complete, you see the following dialog:

![alt text](https://github.com/Social-Impact-league/Social-Impact-League-Project-/blob/main/Images/Blog%205/SIL%20blog%205%2012.png)

When you select the link to open the report in Power BI, your report opens in your Power BI site under My workspace > Reports. 

With this blog, we hope you understand the big picture of Using the Power BI Desktop and by going through the whole series, you will be able to create a report which solves a given analysis problem.
-------------------------------------------------------------------------------------------------------------------------------
