# Real User Monitoring Exercises

**Info:** There are two types of exercises: "Use what you learnt", where you can apply what you previously learnt, and guided exercises. 
The solution for the "Use what you learnt" exercise is linked at the end of the page. 

## 3.1 Front End Analysis
Figure out which Front Ends are used most often. Have a look on Operations Systems and Web Browser

## 3.2 Check out Related Links
Explore the Related Links area and check out the links provided

## 3.3 Timeout Error Root Cause Analysis
Analyze the time out issue being shown by the instructor and figure out the root cause

- Home
![RUM Home](images/RUM_Home_CustomeTime.png)

- Navigate to Requests (New)
![RUM Requests(New)](<images/RUM Requests(New).png>)

- Adjust dimensions
![RUM Requests Dimension](<images/RUM Requests Dimension.png>)

- Select “Request Name”, “Request Type”, and “Action”
![Dimesion Selection](<images/RUM Dimension Selection.png>)

- Close. The table should be updated according to the selected "Dimensions"
![Updated Request Dimensions](<images/RUM_Dimension_Updated.png>)

- Select Request with Action “Go button”
![RUM Request Go Button](<images/RUM Go Button.png>) 

- Execution List
![RUM Request Executions](images/RUM_Request_Executions.png)

- Select the relevant execution to navigate to the details
![Execution Details](images/RUM_Execution_Graph.png)

- Open Navigation Options and “Show detailed trace in Cloud Logging”
![RUM Navigation Links](images/RUMLinks.png)

- Trace details in SAP Cloud Logging
![Cloud Logging](images/RUM_CloudLogging_Result.png)

- Explore spans to learn more about the request content
![Cloud Logging Span](images/RUM_CL_Span.png)

## 3.4 Creating a Custom Page (Guided Excercise)
- Open the side navigation menu
- Click on the "Add Custom Page" button at the bottom of Page List 
![RUM Add Custom Page](images/RUM_AddCustomPage.png)

- Select Views and Drag it to the Page
![RUM Custom Views](images/RUM_Select_Views.png)

- Provide and Name and an Icon for the Page in the "Page Management" panel
![RUM Name and Icon for the Custom Page](images/Custom_Page_NameIcon.png)

- Save the Page
![RUM Save Custom Page](images/CustomPage_Save.png)

- **Result**\
You can see that the newly added Page appears on the Page List and will be available on subsequent revisits
![RUM Custom Page](images/RUM_Custom_Page.png)

- **Note**\
As an **Admin** - **which you are not** - you can also share custom pages with other users
![RUM Share Custom Page](images/RUM_ShareCustomPage.png)


**Next Step**\
[Refer to the Solutions](/exercises/ex3/3_RealUserMonitoring_Solutions.md)\
[Continue to Business Process Monitoring Overview](/exercises/ex4/4_BusinessProcessMonitoring_Base.md)

**Additional Links**\
[Real User Monitoring Overview](/exercises/ex3/3_RealUserMonitoring_Base.md)\
[Session Overview](/README.md#overview)
