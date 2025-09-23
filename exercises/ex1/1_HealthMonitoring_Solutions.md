## Health Monitoring Solutions

## 1.1 Adjust Time Frame
- Follow the steps until opening the History of the metric "Memory: Eden Space (Java)"

- Open Time Frame Selection
![Metric History Timeframe](images/MetricHistory_TimeFrame.png)

- Pick a date that is a few days on the past
![Metric Custom Time](images/Metric_History_Custom_Time.png)

## 1.2 Adjust Resolution
- Open Time Frame 
![Metric Resolution Popup](images/Metric_Resolution.png)

- Adjust Resolution with the slides to “15Min” and apply changes
![Metric Resolution 15 mins](images/Metric_Resolution_15mins.png)

- Result
![Metric History with Custom Resolution](images/Metric_History_with_Resolution.png)

## 1.3 Which library version is used by the custom app
- Navigate to metric “Library Version”
![Metric Library Version](images/Metric_Library_Version.png)

- The version is shown on the tile itself and in metric details.
In case there are multiple apps running in the environment, check the metric details.

## 1.4 Check which Event and Alerts are configured
- Home
![Metric Overview](images/HM_Metrics.png)

- Open Configuration Panel and click on Service “SAPTechEd-HandsOn-CF”:
![Health Monitoring Configuration](images/HM_Configuration.png)

- Configuration for Services
![Health Monitoring Configuration Dialog](images/Configuration_Dialog.png)

- Navigate to Events
![Health Monitoring Event Configuration](images/Configuration_Events.png)

- **Result** 
Alert are active for “High Disk Utilization”, and “High Java Memory Utilization”

## 1.5 Add Service to Favorites
- Navigate to the Metric Overview of the Service “SAPTechEd-HandsOn-CF”
![Metric Overview](images/HM_Metrics.png)

-  Click on “Favorite” Icon
![Mark as Favorite](images/Mark_Favorite.png)

- Navigate to Home and see the results in the favorite section
![Home with Favorite](images/Home_with_Favorite.png)

## 1.6 Explore Whats's New
-  Open the In-App Help and Navigate to the What's New area
![What's New](images/Home_WhatsNew.png)

- **Result**
![What's New Result](images/WhatsNew_Result.png)

## 1.7 In App Help Use Spots
- Open the In-App Help and click on a certain spot (example: Scope Overview)
![In App Help](images/InApp_Help_Overview.png)

## 1.8 Adjust Time Window and explore exceptions raised for others traces
- Adjust the Time Window to see all data collected for “This Week”
![Cloud Logging Timeframe Selection](images/CloudLogging_TimeFrame.png)

- **Result**
![Cloud Logging Custom Timeframe](images/CL_TimeFrame_Result.png)

- Click on the filter starting with “traceId:” so see results across the resource
![Cloud Logging TraceId](images/CL_TraceId_Filter.png)


**Next Step**\
[Integration and Exception Monitoring Overview](/exercises/ex2/2_ExceptionMonitoring_Base.md)


**Additional Links**\
[Health Monitoring Overview](/exercises/ex1/1_HealthMonitoring_Base.md)\
[Health Monitoring Exercises](/exercises/ex1/1_HealthMonitoring_Exercises.md)\
[Session Overview](/README.md#overview)
