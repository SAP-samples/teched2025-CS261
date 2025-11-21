# Familiarize yourself with Synthetic User Monitoring

[Link to SAP Cloud ALM tenant](https://cs261-n5i2x9xc.eu10-004.alm.cloud.sap/launchpad#Shell-home)

In the Synthetic User Monitoring application, you can monitor solutions to detect performance and availability issues from a client-side perspective. 

![Cloud ALM Operations Home](images/CALM_Home_SUM.png)

## Scope Selection and Home

- Open the Scope Selector
![Synthetic User Monitoring Scope Selector](../ex5/images/SUM_Scope_Selector.png)

- Select the scenarios Analyze Bookings and Analyze Accepted Bookings. Then Apply your selection.
![Synthetic User Monitoring Scope Selected](../ex5/images/SUM_Scope_Selected.png)

Result: You will see a card for each Scenario deployed on a Runner 
You see the current Availability and Performance status.
You also have an overview of the executions that happened during the last hour (the currently select Time Frame). 
![Synthetic User Monitoring Overview](../ex5/images/SUM_Overview.png)

### Availability

The availability metrics can have 4 statuses:
-	Success (green): when the scenario sequence can be executed as designed.
-	Failure (red): when the scenario execution fails because the sequence cannot be executed as designed.
-	Not Rated (blue): when the execution cannot be carried out due to a problem in the Synthetic User Monitoring infrastructure. E.g. runner not reachable.
-	Unknown (grey): when the last execution is outdated. An execution is valid until the next execution planned time. 

### Performance

The performance can have 5 statuses:
-	Good (green): when the execution duration is “normal” compared to the expectation.
-	Poor (yellow): when the execution duration is slightly abnormal – takes a little more time than expected.
-	Critical (red): when the execution duration is clearly abnormal – takes more time than expected.
-	Not Rated (blue): when the performance cannot be evaluated. E.g. when the availability is not success.
-	Unknown (grey): when the last execution is outdated.

## Explore the executions

- Home
![Synthetic User Monitoring Overview](../ex5/images/SUM_Overview.png)

- Click the header of any Analyze Bookings card
![Synthetic User Monitoring Analyze Bookings Card](../ex5/images/SUM_AnalyzeBookings_Card.png)

Result: You jump to the Exections page. 

- The page is prefiltered on the Analyze Booking scenario.
![Synthetic User Monitoring Analyze Bookings Szenario](../ex5/images/SUM_AnalyzeBookings_Scenario.png)

On the top half of the page, you can see for all the runners:
-	when the executions happen,
-	 what was their:
    - status,
    - duration, 
    - validity, …
    ![Synthetic User Monitoring Execution Explanation](../ex5/images/SUM_Executions_Explanation.png)

On the bottom half of the page, you can see:
-	The availability distribution in percentages per status
-	The Response Time chart.

- Change the Time Frame to the last 24 hours
![Synthetic User Monitoring Time Frame](../ex5/images/SUM_TimeFrame.png)

Result: The page displays the executions for the last 4 hours and you can navigate back and forth by 4 hours increments
![Synthetic User Monitoring Executions](../ex5/images/SUM_Executions.png)

- Click on a Runner row
![Synthetic User Monitoring Runner Row](../ex5/images/SUM_RunnerRow.png)

Result: the bottom half of the page focusses on the results for the selected runner
The Response Time chart is toggled to the Performance: showing the performance status of each execution.
![Synthetic User Monitoring Selected Runner Results](../ex5/images/SUM_Runner_SelectionResults.png)

- Expand the Performance chart
![Synthetic User Monitoring Expand Performance Chart](../ex5/images/SUM_PerformanceChart.png)

- Check the Full Period checkbox
![Synthetic User Monitoring Performance Chart Full Period Selection](../ex5/images/SUM_PerformanceChart_FullPeriod.png)

Result: the chart displays the full last 24 hours Time Frame (the full Time Frame chose in the Time Frame selector)
![Synthetic User Monitoring Performance Chart Full Period Result](../ex5/images/SUM_PerformanceChart_FullPeriod_Result.png)

- Toggle to the Response Time Chart
![Synthetic User Monitoring Show Response Time Chart Toggle](../ex5/images/SUM_ResponseTimeChart_Toggle.png)

Result: the chart displays the response time along with the thresholds used to determine the performance.
![Synthetic User Monitoring Show Response Time Chart](../ex5/images/SUM_ResponseTimeChart.png)

These are Dynamic Thresholds: they are automatically computed from past executions. For that, Synthetic User Monitoring uses machine learning algorithms to predict, from historical executions, what would be a "normal" execution duration for future dates and times.

![Synthetic User Monitoring - Dynamic Thresholds Explanation](../ex5/images/SUM_DynamicThresholds_Explanation.png)

- Collapse the Response time chart
![Synthetic User Monitoring - Collapse Response Time Chart](../ex5/images/SUM_ResponseTimeChart_Collapse.png)

- Open the context menu on an execution
![Synthetic User Monitoring - Execution Context Menu](../ex5/images/SUM_Execution_ContextMenu.png)

Result: a popup displays additonal information about the execution
![Synthetic User Monitoring - Execution Context Menu Details](../ex5/images/SUM_Execution_ContextMenu_Details.png)

- Close the popup

## Drill to execution details

- Click an execution
![Synthetic User Monitoring - Click an Execution](../ex5/images/SUM_Execution_Click.png)

Result: You see the execution details.
In the Steps section, you see the individual results of all the functional steps composing the scenario.

![Synthetic User Monitoring - Execution Details](../ex5/images/SUM_Execution_Details.png)

Synthetic User Monitoring scenarios are based on Script that user can load as a Resource.
The Scripts describes the exact sequence of actions to be performed during an execution.
The one who designs it can:
-	Split it in functional steps to get a finer grain monitoring: Synthetic User Monitoring evaluates the availability and performance of each step. The scenario status is the aggregation of each step sub-status.
-	Define variables: to change some input characteristics. E.g. URL, username/password, …
-	…
It is possible to create several sceanrios out of a same script. E.g. to use diferent set of variables.

- Click the Screenshots tab.
![Synthetic User Monitoring - Execution Details Screenshots](../ex5/images/SUM_Executions_Details_Screenshots.png)

Result: It displays the screenshots captured during the execution of the scenario.
![Synthetic User Monitoring - Execution Details Screenshots](../ex5/images/SUM_Executions_Details_Screenshots_Result.png)

Depending on the scenario technology, Synthetic User Monitoring can (optionally) be configured to take screenshots during the execution of the scenario.

- Click a screenshot tile to see enlarge it.
![Synthetic User Monitoring - Execution Details Screenshots Enlarged](../ex5/images/SUM_Execution_Details_Screenshot_Enlarged.png)

- Click the Metrics Report tab.
![Synthetic User Monitoring - Execution Details Metrics Navigation](../ex5/images/SUM_Execution_Details_Metrics_Navigation.png)

Result: Here, you see what are the exact actions composing the underlying script.
![Synthetic User Monitoring - Execution Details Metrics](../ex5/images/SUM_Execution_Details_Metrics.png)

- Navigate back and forth on the Previous/Next executions
![Synthetic User Monitoring - Execution Details Navigation](../ex5/images/SUM_Execution_Details_Navigation.png)

- If you are on an execution that detected an availability issue, you can see details on the encountered problem.
![Synthetic User Monitoring - Execution Details Error](../ex5/images/SUM_Execution_Details_Error.png)

## Show some statistics

- Use the breadcrumb to go back to the Analyse Bookings executions
![Synthetic User Monitoring - Execution Breadcrumb](../ex5/images/SUM_Execution_Breadcump.png)

- Click the “...” icon and choose Show Statistics > Performance > Last 30 days
![Synthetic User Monitoring - Context Statistics Last 30 Days](../ex5/images/SUM_Statistics_Last30Days.png)

Result: a statistic popup show the evolution of the Performance status statistics for the last 30 days (depending on the Housekeeping settings, you may get less days)
![Synthetic User Monitoring - Context Statistics Last 30 Days Result Chart](../ex5/images/SUM_Statistics_Last30Days_Chart.png)

## Have a glimps on the configuration

Depending on your role, you may not have access to the details of the Synthetic User Monitoring configuration.
However, every user with access to Synthetic User Monitoring can have on overview of the configuration (in read-only).

- Click the Configuration icon
![Synthetic User Monitoring - Configuration Navigation](../ex5/images/SUM_Configuration_Navigation.png)

Result: This opens the configuration tray (a.k.a. Level 1)
It shows, in read-only, the entities configured in Synthetic User Monitoring.
![Synthetic User Monitoring - Configuration Panel](../ex5/images/SUM_Configuration_Panel.png)

The managed components are:
- Runners: The infrastructure where the Sceanrios are executed. This is what represents the location of the synthetic users.
- Resources: The container imported in Synthetic User Monitoring that contains the scripts (sequence of actions to execute)
- Sceanrios: The executed entities. The sceanrio describes which script to execute on which runner, at which interval and with which variable values.
Note: A scenario can be associated to a runner, but not active. I.e. not scheduled for executions (stopped).
- Business Services: The Business Service represents the business monitored by the Scenarios.A Scenario must be associated to, at least, one Business Service. A Business Service is also associated to the Systems and Services providing the monitored business. In Synthetic User Monitoring, the monitoring events (Alert configuration, Notifications, …) are defined on the Business Services. They apply to all the associated scenarios.

The Application Settings show the memory space consumed by Synthetic User Monitoring, along with its Housekeeping settings.

- Expand the Scenarios section
![Synthetic User Monitoring - Configuration Panel Scenarios](../ex5/images/SUM_Configuration_Scenarios_Expand.png)

Result: it shows the configured scenarios.
By default, only the scenarios in the scope are shown. But you can toggle to All scenarios.
![Synthetic User Monitoring - Configuration Panel Scenario List](../ex5/images/SUM_Configuration_Scenario_List.png)

For each scenario, it indicates:
- The technology (here, only Selenium IDE scenario are configured)
- The number of runners where it is “active” among the number of runners its associated to.

- Click a Runner counter.
![Synthetic User Monitoring - Configuration Panel Scenario Runners](../ex5/images/SUM_Configuration_Scenario_Runners.png)

Result: a pop-up shows the list of associated runners and if the scenario is active on them.
![Synthetic User Monitoring - Configuration Panel Scenario Runner Status](../ex5/images/SUM_Configuration_Scenario_Active_Runners.png)

**Next Step**\
[Continue to Exercises](/exercises/ex5/5_SyntheticUserMonitoring_Exercises.md)

**Additional Links**\
[Session Overview](/README.md#overview)


