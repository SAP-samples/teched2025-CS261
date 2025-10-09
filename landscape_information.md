# Landscape Details

During this Hands-On session, a landscape is used that consists of the following services:

- SAP BTP Account covering authentication-relevant aspects
- Subaccount with CAP SFLIGHT App (Java instrumentation)
- SAP Build Workzone Launchpad with the app embedded
- SAP Cloud Logging
- SAP Cloud ALM Tenant

The following picture shows the architecture from a high-level perspective as well as the interplay of the services: 

![High-Level Landscape Architecture](/exercises/overall_content/landscape_architecture.png)

For this session, we have already prepared the custom SAP BTP application for monitoring. All related steps are in the following [additional chapter](/exercises/overall_content/Additional_Information_Instrumentation.md) for your reference. These details are not relevant to participating in the session and following the exercises.

## Custom SAP BTP Application

We are using the SFlight CAP application in the Java-based version. You can download the application from the following GitHub repository:

[SFlight GitHub Repository](https://github.com/SAP-samples/cap-sflight)

## Logon Details 

For login to the applications, you can use the user ID and password that is provided by the instructors.

![Logon Details](/exercises/overall_content/Logon_Details.png)

If asked for a sign-in, select "tdct3ched1.accounts.ondemand.com" during the authentication process.

![Sign In](/exercises/overall_content/Sign_In.png)

### SFlight Application

Via the following SAP Build Workzone Launchpad URL, you can access the SFlight application:

https://cs261-n5i2x9xc.launchpad.cfapps.eu10.hana.ondemand.com/site?siteId=7f5e32cf-5ca9-491b-946f-1ea71063afea#Shell-home 

### SAP Cloud ALM

Via the following URL, you can access the SAP Cloud ALM tenant:

https://cs261-n5i2x9xc.eu10-004.alm.cloud.sap/launchpad#Shell-home 

### SAP Cloud Logging

Via the following URL, you can access the SAP Cloud Logging tenant:

https://dashboards-sf-0a39e8fe-4651-4d15-bcfc-ebdbd0634b4e.cls-13.cloud.logs.services.eu10.hana.ondemand.com 

Remark: During the exercises, you will be guided to the SAP Cloud Logging instance using context-sensitive links.

