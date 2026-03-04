# Real User Monitoring

The purpose of Real User Monitoring is to provide transparency about the usage (executions) and the
performance (response times) of user interactions. It supports the monitoring request executions from
different platforms with a unified user experience using a common look-and-feel and handling pattern.

[Link to SAP Cloud ALM tenant](https://cs261-n5i2x9xc.eu10-004.alm.cloud.sap/launchpad#Shell-home)

![CALM Home - Real User Monitoring](images/CALM_Home_RUM.png)

## Scope Selection and Home
- Open the Scope Selector
![RUM Scope Selector](images/RUM_ScopeSelector.png)

- Select both Services: Service "SAPTechEd-HandsOn-WZ", "SAPTechEd-HandsOn-CF" and Apply your selection
![RUM Scope Selected](images/RUM_ScopeSelected.png)

- **Result**: Based on your selection, you will see a card for services in the Overview area
![RUM Home](images/RUM_Home.png)

- **Info**: The default Time Frame is "Last Hour" - Data is always shown in context of the selected time frame. In the chapter [Time Frame](/exercises/ex2/2_ExceptionMonitoring_Base.md#Time-Frame), you will find example steps to adjust the time frame.

- **Side menu**: Expand the side menu to see all available pages
![RUM All Pages](images/RUM_AllPages.png)

## Explore Requests 
- Home
![RUM Home](images/RUM_Home_CustomeTime.png)

- Navigate to Page "Requests"
![RUM Request Page Navigation](images/RUM_Highlight_RequestPage.png)

- Click on Dimension
![RUM Request Page](images/RUM_Request_Dimensions.png)

- Select "Request Name" and "Request Type"
![RUM Request Page](images/RUM_Request_Dimensions_Adjust.png)

- **Result**: Requests are shown with additional Details
![RUM Request Page](images/RUM_Request_Dimensions_Result.png)

- Click on "+ KPI Tag" to apply additional filters 
![RUM Request Page Filter](images/RUM_SAPUI5_Requests_FilterUI.png)

- **Result**: Only Requests for Action "KPI Tag" are shown
![RUM Request Page](images/RUM_SAPUI5_Requests_KPITag.png)

- Click on Filter to see/adjust applied filters
![RUM Request Page](images/RUM_SAPUI5_Requests_FilterDetails.png)

The next steps are to explore the details of the customer application “Travel Analytics” and the performance perceived by end users.
The page "Requests" is hereby used.

- Click on Request name "sap.fe.travel_analytics"
![RUM Request Actions](images/RUM_RequestActions.png)

- Click on "KPI Tag"
![RUM Request KPI Tag](images/RUM_Request_KPI_Tag.png)

- Navigate to a specific execution
![RUM Execution Details](images/RUM_ExecutionList.png)

- Use Zoom
![RUM Execution Details Zoomed Out](images/RUM_ExecutionDetail_Zoomed.png)

- Explore Details
![RUM Execution Details Popup](images/RUM_RequestDetailCard.png)

- Switch View and expand rows
![RUM Requests Table View](images/RUM_SwitchView.png)

- Click the rows to see details per request
![RUM Details Per Request](images/RUM_DetailPerRequest.png)

**Next Step**\
[Proceed to Cloud Logging](/exercises/ex3/3_RealUserMonitoring_CloudLogging.md)

**Additional Links**\
[Session Overview](/README.md#overview)
