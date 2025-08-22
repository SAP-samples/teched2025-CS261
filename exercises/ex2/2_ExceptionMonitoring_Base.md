# Integration and Exception Monitoring

Integration and Exception Monitoring provide transparency for data exchange processes. The application
supports monitoring for peer-to-peer interfaces and interfaces using orchestration platforms and provides a
unified user experience for all interface types using a common look-and-feel and handling pattern.

> Insert screenshot: CALM Home -> Tile Highlighted


## Scope Selection and Home

- Open the Scope Selector
> Insert screenshot: Scope Selector Opened

- Change the Filter for Managed Components, select “Service” and press “Go”
> Insert screenshot: Scope Selector Filter selection

- Select “BTP_Subaccount_HandsOn”, Service Type “SAP BTP, Cloud Foundry environment”
> Insert screenshot: Scope Selector Value selection

- Apply your selection
>Insert screenshot: Scope Selector - Highlighting the Apply button

- **Result**: You will see services a card for services of the type “SAP BTP, Cloud Foundry environment” in the
Overview area, based on your selection.
>Insert screenshot: Home - Integration and Exception Monitoring


## Explore Exceptions
- Navigate to the Home of Integration and Exception Monitoring
> Insert screenshot: Home - Integration and Exception Monitoring

- Navigate to "Exceptions" by clicking on "Exceptions" link on BTP Subaccount Service Card
> Insert screenshot: Home - Card with Exceptions in focus

- **Result**: Exception Overview 
> Insert screenshot: Exceptions page

- Click on individual Exceptions to explore details
> Insert screenshot: Exceptions Page with highlighted exception

- Collection Context
> Insert screenshot: Exception details

-  Navigate through the details of the exception via “Association Context”, “Call Stack”, and “Process Arguments”

## Time Frame
- Navigate to the Home of Integration and Exception Monitoring
> Insert screenshot: Home - Integration and Exception Monitoring

- Click on Time Frame, Select “Last 7 days”
> Insert screenshot: Time Frame Selector

- **Result**: Collected data is shown based on the selection Time Frame
> Insert screenshot: Home - Integration and Exception Monitoring

## Search in Exceptions
- Navigate to the Home in Integration and Exception Monitoring
> Insert screenshot: Home - Integration and Exception Monitoring

- Navigate to Tracking Page in Integration and Exception Monitoring
> Insert screenshot: Tracking - Integration and Exception Monitoring

- Enter details for search. E.g. “Invalid”
> Insert screenshot: Tracking 

- Navigate to “Exceptions”
  **Info**: The search is search for both Integration as well as Exceptions
> Insert screenshot: Tracking 

- Click on Result (Exception)
> Insert screenshot: Tracking

-  Check Log Message **Check if this button exists**
> Insert screenshot: Log

- Navigate to Page Exception
> Insert screenshot: Exception

- **Additional Information**: You can find further details in Card Information
> Insert screenshot: Card Information button clicked


## Alerting
Alerts and the Alert Inbox page are available in all SAP Cloud ALM for operations areas. As part of this Hands-
On session, we looked at them in the context of Exception Monitoring. The alert details are specific to the
respective area you are using. In Health Monitoring, the details are based on metrics, and below, you will be
guided through an exception-based context.
**Please do not confirm Alert(s) so that all participants can explore those.**

- Page: Exceptions
> Insert screenshot: Exceptions page

- Navigate to Open Alerts
> Insert screenshot: Alerting 

-  Navigate to “**Erroneous Java Application**” with Object Details “Invalid Status. (must be ‘Open’)”

- Navigate to Errors
> Insert screenshot: Alert Details page with Errors tab selected

- By clicking on a certain message, details are shown.
> Insert screenshot: Specific message selected in Alerting

- **Hint**: You can also use the “Full Screen” option
> Insert screenshot: Maximise button

## Raise an exception in the custom application

- Open the Launchpad
> Screenshot: Launchpad showing custom apps

- Navigate to "Process Travels"
> Screenshot: Process Travels app

- Select Travel with Travel Status "Accepted" and try to "Reject Travel".
  (not allowed as per application logic)
> Screenshot: Travel with Status 'Accepted' selected and "reject travel" button focused

- **Result**
> Error popup showing Invalid travel status


**Next Step**
[Proceed to Cloud Logging](/exercises/ex2/2_ExceptionMonitoring_CloudLogging.md)

**Additional Links**
[Session Overview](/README.md#overview)
