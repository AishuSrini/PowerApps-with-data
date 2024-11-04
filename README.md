# **🚀 Lab: Develop**
# **📝 Lab- Tasks**

In this lab, you will go though the following tasks:

+ Creating A Canvas App With Data From An Excel-File
+ Creating A Canvas App With Power Apps Copilot
+ Creating A Solution
+ Add The Resources Created By Power Apps Copilot To A Solution
  
# **☑️ Task 1: Create A Canvas App With Data From An Excel-File**
In this task, you will:

+ Create a Canvas App using Excel to App
+ Customize galleries by using Power Apps Ideas to generate Power Fx formulas
  
**Introduction To Excel To App**

With Excel to App, you can choose an Excel file, generate an app from it, and then run the app you've created. Each generated app comes with screens for browsing records, viewing record details, and creating or updating records. This allows you to quickly build a functional app using your Excel data, which you can then customize to better align with your specific needs.

When you upload an Excel file, a Dataverse table is automatically created. Dataverse provides both standard and custom tables for securely storing your data in the cloud. These tables allow you to structure your organization’s data in a way that fits your business requirements, making it easier to integrate and use within your apps.

If your environment is based in the US region and AI features are enabled within your organization, the AI Copilot can assist in setting up your table. This feature can suggest table names, descriptions, data types for columns, and headers, even if some details are missing from the uploaded file. When AI Copilot is used to generate a table, a Copilot card will appear, indicating that the table was created using AI.

In this exercise, you will create an application using data from an Excel table.

> **Note:** Power Apps requires either a Microsoft 365 license or a free trial. Learn more about your licensing options. [Microsoft products include Microsoft Power Apps and Power Automate.](https://learn.microsoft.com/en-us/power-platform/admin/pricing-billing-skus)

**Explore The Excel To Power App Functionality**

1.Go to [make.powerapps.com](https://make.powerapps.com/) and Sign In with your Power Apps credentials.

2.From the Power Apps home screen, select Start with data.
![start with data](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/start-with-data.png)

3.Select create new tables from other ways to get started
![create from table](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/other-ways-to-start.png)

4.Select Import an excel file from choose an option to create a tables
![choose an option](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/choose-option.png)

5.Click Select from device and navigate to the location where the Employee_Directory_file.xlsx Excel file is saved and upload it. The maximum file size limit is 5 GB.
![upload file](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/import-excel.png)

6. Table which is based on the data from the Employee_Directory_file.xlsx Excel file will be generated. Click the 3 dots in employee record and choose properties to change display name.
![edit](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/edit-table-name.png)

7.On the Edit Table pop up, enter  Employee Record as the Display name, Employee Records as the Plural Name, and make sure that Address is selected as the Primary column. Select Save
![properties](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/properties.png)

8.Select the save and open app button on the top right-hand corner of the screen.
![Save and run app](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/save-and-open-app.png)

9.When the app first loads, a dialog may appear saying: Welcome to Power Apps Studio. If so, select the Skip button.

10.You should now be viewing the app that has been generated for you in Edit mode.
![employee app](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/employee-app.png)

11.To the left of the screen, select the Data icon from the navigation bar. Notice that a Dataverse table, based on the Employee_Directory_file.xlsx Excel file, has been created.
![data](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/data.png)

12.Select the Tree view icon to return to the Tree view.
![tree](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/tree.png)

13.On the app main screen, click on the gallery displaying the Employee Records and then click on RecordsGallery1 in the Tree view to expand it.
![gallery](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/gallery.png)

14.Select the ellipsis (…) next to the NextArrow and delete it.

![delete](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/next%20arrow%20delete.png)

15.Select the RecordsGallery1 and then select the edit button to put the gallery in edit mode.
![edit](https://github.com/AishuSrini/PowerApps-with-data/blob/main/images/edit.png)
