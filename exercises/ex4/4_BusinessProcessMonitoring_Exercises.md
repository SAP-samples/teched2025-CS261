# Business Process Monitoring Exercises

Disclaimer: These tasks contain the relevant steps - the relevant solution are embedded.

## 4.1 Create your Custom KPI (Guided Excercise)

- Open 'Configuration' section, Navigate to 'KPI Management' and Click on 'Configure KPI' button
![BPMon KPI Management](images/BPMon_CustomKPINav.png)

- Click on the 'Create Custom KPI' button placed on the toolbar of KPIs table
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


## 4.2 Check Data Collection (Guided Excercise)
- Contact instructors to trigger Data Collection.
- Open 'Configuration' section, Navigate to 'KPI Management'. Check for the Collection Status of the KPI
![BPMon Custom KPI Data Collection](images/BPMon_DataCollectionStatus.png)


## 4.3 Create an Event to be alerted (Guided Excercise)
In order to get Alerted based on certain conditions, an Event needs to be configured

- Navigate to the KPI created in the previous section
![BPMon Edit Custom KPI](images/BPMon_EditKPI.png)

- Click on the KPI Name to configure the KPI
![BPMon Custom KPI](images/BPMon_CustomKPI.png)

- Navigate to 'Events' section and Click on 'Add' button
![BPMon Add Event](images/BPMon_AddEvent.png)

- Fill the mandatory fields. \
Choose threshold values for Warning and Critical alert \
In 'Event Actions'section, Switch On 'Create Alert' \
Save the event
![BPMon KPI Event](images/BPMon_KPIEvent.png)

## 4.4 Add an Event with a filter (Guided Excercise)
- Navigate to the KPI created in the previous section
![BPMon Edit Custom KPI](images/BPMon_EditKPI.png)

- Click on the KPI Name to configure the KPI
![BPMon Custom KPI](images/BPMon_CustomKPILink.png)

- Navigate to 'Events' section and Click on 'Add' button
![BPMon Add Event](images/BPMon_AddEvent.png)

- Fill the mandatory fields. \
Choose threshold values for Warning and Critical alert 

- Click on 'Add' in the filters section \
Select 'Destination City' is 'Hamburg'
![BPMon Event Filter](images/BPMon_KPIEventFilter.png)

- **Hint** Use Value Help to search for filter values 
![BPMon Event Value Help](images/BPMOn_EventValueHelp.png)


## 4.5 Adjust Graph and work with Views (Guided Excercise)

...

## 4.5 Explore Guided Tours (Guided Excercise)


**Additional Links**\
[Business process Monitoring Overview](/exercises/ex4/4_BusinessProcessMonitoring_Base.md)\
[Return to Session Overview](/README.md#overview)

**** link to Thank you page & feedback?


