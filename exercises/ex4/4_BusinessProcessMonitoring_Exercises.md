# Business Process Monitoring Exercises

Disclaimer: These tasks contain the relevant steps - the relevant solutions are embedded.

## 4.1 Create your Custom KPI (Guided Exercise)

- Open 'Configuration' section, navigate to 'KPI Management', and Click on 'Configure KPI' button
![BPMon KPI Management](images/BPMon_CustomKPINav.png)

- Click on the 'Create Custom KPI' button placed on the toolbar of the KPIs table
![BPMon Add Custom KPI](images/BPMon_AddCustomKPI.png)

- Configure your Custom KPI. Fill all Mandatory fields
![BPMon Configure Custom KPI](images/BPMon_ConfigureCustomKPI.png)

- Refer to the section below to configure the KPI. **Please follow the naming convention as suggested** \
**Replace XX with your Participant Number**  
    - Name: **XX** - Open Travel Bookings
    - Description: Travel Bookings with Status Open - Participant **XX**
    - KPI ID: ZKPITBP0**XX**
    - Category: Backlog
    - Service Type: SAP BTP, Cloud Foundry environment 
    - Data Collection Frequency: 15 minutes \
    - **Fill out the Characteristics section as shown below
    ![BPMon KPI Settings](images/BPMon_KPI_Settings.png)

- Close the Custom KPI
![BPMon Close Custom KPI](images/BPMon_KPI_Close.png)

- Check the KPI listed in the KPIs table
![BPMon KPI Listed](images/BPMon_KPIListed.png)


## 4.2 Check Data Collection (Guided Exercise)
- Contact instructors to trigger Data Collection.
- Open 'Configuration' section, navigate to 'KPI Management'. Check the Collection Status of the KPI
![BPMon Custom KPI Data Collection](images/BPMon_DataCollectionStatus.png)

** Show Data Collection being switched on in KPI Management > KPI Management > Click on KPI > Data Collection Tab (check if the data collection is switched on, if not switch the data collection on for you KPI)

** Inform the instructor so that the data collection run is triggered

## 4.3 Create an Event to be alerted (Guided Exercise)
In order to get alerted based on certain conditions, an Event needs to be configured

- Navigate to the KPI created in the previous section
![BPMon Edit Custom KPI](images/BPMon_EditKPI.png)

- Click on the KPI Name to configure the KPI
![BPMon Custom KPI](images/BPMon_CustomKPI.png)

- Navigate to the 'Events' section and click on the 'Add' button
![BPMon Add Event](images/BPMon_AddEvent.png)

- Fill the mandatory fields. \
Choose threshold values for Warning and Critical alert \
In the 'Event Actions'section, Switch On 'Create Alert' \
Save the event
![BPMon KPI Event](images/BPMon_KPIEvent.png)

** lower thresholds  1, 2 **

## 4.4 [Optional] Add an Event with a filter (Guided Exercise)
- Navigate to the KPI created in the previous section
![BPMon Edit Custom KPI](images/BPMon_EditKPI.png)

- Click on the KPI Name to configure the KPI
![BPMon Custom KPI](images/BPMon_CustomKPILink.png)

- Navigate to 'the Events' section and click on the 'Add' button
![BPMon Add Event](images/BPMon_AddEvent.png)

- Fill the mandatory fields. \
Choose threshold values for the Warning and Critical alerts 

- Click on 'Add' in the filters section \
Select 'Destination City' is 'Hamburg'
![BPMon Event Filter](images/BPMon_KPIEventFilter.png)

- **Hint** Use Value Help to search for filter values 
![BPMon Event Value Help](images/BPMOn_EventValueHelp.png)


## 4.5 Adjust Graph and work with Views (Guided Exercise)

...

## 4.6 Explore Guided Tours (Guided Exercise)


**Additional Links**\
[Business process Monitoring Overview](/exercises/ex4/4_BusinessProcessMonitoring_Base.md)\
[Return to Session Overview](/README.md#overview)

**** link to Thank you page & feedback?


