# Integration and Exception Monitoring

Integration and Exception Monitoring provide transparency for data exchange processes. The application
supports monitoring for peer-to-peer interfaces and interfaces using orchestration platforms and provides a
unified user experience for all interface types using a common look-and-feel and handling pattern.

![CALM Home IEM](images/CALM_Home_IEM.png)


## Scope Selection and Home

- Open the Scope Selector
![Scope Selector Opened](images/IEM_Scope_Selector.png)

- Change the Filter for Managed Components, select “Service” and press “Go”
![IEM Scope Services](images/IEM_Scope_Services.png)
***** Select all Service Status ****** TCS

- Select “SAPTechEd-HandsOn-CF”, Service Type “SAP BTP, Cloud Foundry environment”
![IEM Scope Selector Results](images/IEM_Scope_Result.png)

- Apply your selection
![IEM Scope Selected](images/IEM_Scope_Selected.png)

- **Result**: You will see services a card for services of the type “SAP BTP, Cloud Foundry environment” in the
Overview area, based on your selection.
![IEM Home](images/IEM_Home.png)


## Explore Exceptions
- Navigate to the Home of Integration and Exception Monitoring
![IEM Home](images/IEM_Home-1.png)

- Navigate to "Exceptions" by clicking on "Exceptions" link on BTP Subaccount Service Card
![IEM Home Exceptions](images/IEM_Home_Exceptions_Link.png)

- **Result**: Exception Overview 
![IEM Exception Overview](images/IEM_Exceptions.png)

- Click on individual Exceptions to explore details
![IEM Exception](images/IEM_Status_Open.png)

- Collection Context
![IEM Exception Details](images/IEM_Exception_CollectionContext.png)

-  Navigate through the details of the exception via “Association Context” and “Call Stack”

## Time Frame
- Navigate to the Home of Integration and Exception Monitoring
![IEM Home](images/IEM_Home.png)

- Click on Time Frame, Select “Last 7 days”
![IEM Custom Time Frame](images/IEM_TimeFrame.png)

- **Result**: Collected data is shown based on the selection Time Frame
![Custom Time Frame Result](images/IEM_TimeFrame_Result.png)

## Search in Exceptions
- Navigate to the Home in Integration and Exception Monitoring
![Custom Time Frame Result](images/IEM_TimeFrame_Result.png)

- Navigate to Tracking Page in Integration and Exception Monitoring
- Enter details for search. E.g. “Invalid”
![IEM Tracking](images/IEM_Tracking.png)

- Navigate to “Exceptions”
  **Info**: The search is for both Integration as well as Exceptions
![IEM Tracking Exception](images/IEM_Tracking_SearchException.png)

- Click on Result (Exception)
![Exception Details](images/IEM_ExceptionDetails.png)


- Navigate to Page Exceptions
![IEM Exceptions](images/IEM_Exception_Page.png)

- **Additional Information**: You can find further details in Card Information
![IEM Card Information](images/IEM_CardDetails.png)


## Alerting
Alerts and the Alert Inbox page are available in all SAP Cloud ALM for operations areas. As part of this Hands-
In the session, we looked at them in the context of Exception Monitoring. The alert details are specific to the
respective area you are using. In Health Monitoring, the details are based on metrics, and below, you will be
guided through an exception-based context.
**Please do not confirm Alert(s) so that all participants can explore those.**

- Page: Exceptions
![IEM Exceptions](images/IEM_Exception_Page.png)

- Navigate to Open Alerts
![IEM Alerting](images/IEM_Alerting.png)

-  Navigate to “**Erroneous Java Application**” with Object Details “Invalid Status. (must be ‘Open’)”
![IEM Java Alert](images/IEM_JavaAlert.png)

- Navigate to Errors
![IEM Alert Details](images/IEM_JavaAlert_Details.png)

- By clicking on a certain message, details are shown.
![IEM Error Details](images/IEM_ErrorDetails.png)

- **Hint**: You can also use the “Full Screen” option
![IEM Alerting Full Screen](images/IEM_Alerting_FullScreen.png)

## Raise an exception in the custom application

- Open the Launchpad 
[Travel Agency](https://cs261-n5i2x9xc.launchpad.cfapps.eu10.hana.ondemand.com/site?siteId=7f5e32cf-5ca9-491b-946f-1ea71063afea#Shell-home)
![Custom Apps Home](images/Custom_Apps_Home.png)

- Navigate to "Process Travels"
![Process Travel App](images/App_Process_travels.png)

- Select Travel with Travel Status "Accepted" and try to "Reject Travel".
  (not allowed as per application logic)
![Travel Selected](images/Travel_Selected.png)

- **Result**
![Error](images/Action_Error.png)


**Next Step**\
[Proceed to Cloud Logging](/exercises/ex2/2_ExceptionMonitoring_CloudLogging.md)

**Additional Links**\
[Session Overview](/README.md#overview)
