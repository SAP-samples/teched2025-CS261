# Exercises: Integration and Exception Monitoring 

# 2.1 Adjust Time Window and explore exceptions raised for other traces (Guided Excercise)

-  Click on Exception Message (link: “Invalid travel Status (must be ‘Open’)”)
![IEM Cloud Logging Navigation](images/IEM_NavToCloudLogging.png)

- Add filter "com.sap.cap.sflight.processor.AcceptRejectHandler" by hovering and clicking on "+"
![Cloud Logging - Add Filter](images/CloudLogging_AddFilter.png)

- Disable "traceid" from filter. Click on "traceid" and select "Temporarily disable"
![Cloud Logging - Disable Filter](images/CloudLogging_Disable.png)

- **Result**
![Cloud Logging - All Occurences](images/CloudLogging_AllOccurences.png)

**Next Step**\
[Continue to Real User Monitoring Overview](/exercises/ex3/3_RealUserMonitoring_Base.md)

**Additional Links**\
[Integration and Exception Monitoring Overview](/exercises/ex2/2_ExceptionMonitoring_Base.md)\
[Session Overview](/README.md#overview)