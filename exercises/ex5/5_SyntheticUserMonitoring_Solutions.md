# Synthetic User Monitoring Solutions

## 5.1 Percentage of availability problems

- Open the Scope Selector, add the Manage Travels scenario and apply.
![Synthetic User Monitoring - Exercise 5.1 Scope Selection](../ex5/images/SUM_Exercise51_Scope.png)

- Open the Time Frame selector, select Last 6 hours (you can also create a custom” Last 4 hours” time frame) and close.
![Synthetic User Monitoring - Exercise 5.1 Time Frame](../ex5/images/SUM_Exercise51_TimeFrame.png)

- Click any Manage Travels card.
![Synthetic User Monitoring - Exercise 5.1 Manage Travel Card](../ex5/images/SUM_Exercise51_ManageTravel_Card.png)

Result: The Availability Distribution pie chart indicates the availability percentages for the last 4 hours
![Synthetic User Monitoring - Exercise 5.1 Availability Distribution](../ex5/images/SUM_Exercise51_Availability_Distribution.png)

## 5.2 Error Details

- Click an execution in Availability error
![Synthetic User Monitoring - Exercise 5.2 Execution Navigation](../ex5/images/SUM_Exercise52_Execution_Details.png)

- Click the “info” icon on the failing step
![Synthetic User Monitoring - Exercise 5.2 Execution Details Error Step](../ex5/images/SUM_Exercise52_ExecutionDetails_ErrorStep.png)

Result: The Error Information popup indicates the encountered problem.
![Synthetic User Monitoring - Exercise 5.2 Execution Details Error Details](../ex5/images/SUM_Exercise52_ExecutionDetails_ErrorDetails.png)

Optionally, you can also look at the captured screenshots to see what the UI looked like at the end of the faulty step.
In this case, the UI was hanging in a “busy” state at the time of the execution.

![Synthetic User Monitoring - Exercise 5.2 Execution Details Error Details Screenshot](../ex5/images/SUM_Exercise52_ExecutionDetails_ErrorDetails_Screenshot.png)

## 5.3 Statistics

- Go back to the Overview page
![Synthetic User Monitoring - Exercise 5.3 Navigate to Home](../ex5/images/SUM_Exercise53_Start.png)

- Open the Scope Selector, add the Analyze SunsetWings Bookings scenario and apply.
![Synthetic User Monitoring - Exercise 5.3 Scope Selection](../ex5/images/SUM_Exercise53_ScopeSelection.png)

- Click an Analyze SunsetWings Bookings card
![Synthetic User Monitoring - Exercise 5.3 Navigate Analyze SunsetWings Bookings](../ex5/images/SUM_Exercise53_CardNavigation.png)

- On the Scenario name, click “. . .” > Show Statistics > Performance > Last 7 days
![Synthetic User Monitoring - Exercise 5.3 Scenario Context](../ex5/images/SUM_Exercise53_ScenarioContext.png)

Result The Statistic Chart displays the Performance Last 7 Days
![Synthetic User Monitoring - Exercise 5.3 Scenario Last 7 Days Chart](../ex5/images/SUM_Exercise53_ChartLast7Days.png)

## 5.4 Configuration of the managed objects

How many Runners are configured?

- Open the configuration panel. /
  There are 3 runners.
  ![Synthetic User Monitoring - Exercise 5.4 Configured Runners](../ex5/images/SUM_Exercise54_ConfiguredRunners.png)

How many scenarios are associated to the runner On-Premise02?

- Expand the Runners section. /
  There are 4 associated scenarios (and 3 of them are active)
  ![Synthetic User Monitoring - Exercise 5.4 Configured Runners](../ex5/images/SUM_Exercise54_RunnerScenarios.png)

Among them, which ones are active?

- Click the [3/4] button. /
  Analyze Bookings, Analyze SunsetWings Bookings and, Manage Travel are active
  ![Synthetic User Monitoring - Exercise 5.4 Active Scenarios per Runner](../ex5/images/SUM_Exercise54_ActiveRunnersScripts.png)

## Configuration of the managed objects (bonus)

- Expand the Business Services section /
  In Synthetic User Monitoring, monitoring events are defined in the Business Services.
  Here, only the business service Travel Agency has defined Events.
  ![Synthetic User Monitoring - Exercise 5.5 Business Services](../ex5/images/SUM_Exercise55_BusinessServices.png)

- Click the [1/4] event button for Travel Agency /
  Only the Availability Event (Global) monitoring event is configured.
  ![Synthetic User Monitoring - Exercise 5.5 Events](../ex5/images/SUM_Exercise55_Events.png)

For which scenarios?

- Click the [4/4] scenario button for Travel Agency /
  the configured monitored events apply to all the associated scenarios.
  ![Synthetic User Monitoring - Exercise 5.5 Scenarios](../ex5/images/SUM_Exercise55_Scenarios.png)

**Additional Links**\
[Synthetic User Monitoring Overview](/exercises/ex5/5_SyntheticUserMonitoring_Base.md)\
[Return to Session Overview](/README.md#overview)

[Further Resources and Thank You](/exercises/overall_content/ConclusionAndResources.md)