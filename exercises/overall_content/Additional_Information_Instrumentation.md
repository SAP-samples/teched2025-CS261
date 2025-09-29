# Additional Information

In preparation for this session we instrumented the application and prepared the landscape follwing this flow:

![alt text](instrumentation_flow.png)

## Prerequisites

- Required Java version: Runtime needs to be Java 11, Java 17 or Java 21
- Prerequisites for custom instrumentation or SAP Java Buildpack is not being used
    - Required library versions*
        - otel-agent-ext-java: Version 1.5.30
        - calm-crun-client-api-java*: Version 1.5.32 (optional, only required for custom instrumentation)
        - fesr-to-otel-java: Version 2.0.26 (for Spring Boot 3)
    -  artifactory as repository in pom.xml
    - Update settings.xml pointing to technical user credentials for the artifactory

* Make sure to use the latest versions / keep your apps updated

![Prerequisites [SAP Cloud ALM Expert Portal - OpenTelemetry@SAP]](https://support.sap.com/en/alm/sap-cloud-alm/operations/expert-portal/data-collection-infrastructure.html?anchorId=section_415688568#section_415688568) 

## Frontend Data Collection

We embedded our application into SAP Build Workzone Launchpad and switched on the colleciton of statistical data records for the site. 

![Site settings](site_settings.png)

In case you are not using SAP Build Workzone you can instrument a front end receiver into your application. The relevant steps can be found on our Expert Portal:

![Enabling Frontend Data Collection [SAP Cloud ALM Expert Portal - OpenTelemetry@SAP]](https://support.sap.com/en/alm/sap-cloud-alm/operations/expert-portal/data-collection-infrastructure.html?anchorId=section_873338493#section_873338493)

## Enabling Backend Data Collection

- To configure the data collection instrumentation for back-end services you only need the respective auto-instrumentation:
    - ![Autoinstrumentation for Java](https://support.sap.com/en/alm/sap-cloud-alm/operations/expert-portal/data-collection-infrastructure/autoinstrumentation-for-java.html)
    - ![Autoinstrumentation for Node.js](https://support.sap.com/en/alm/sap-cloud-alm/operations/expert-portal/data-collection-infrastructure/autoinstrumentation-nodejs.html)
- SAP Java Build Pack Setup (without or with Cloud Logging)

![SAP Java Build Pack Setup](SAPJavaBuildPackSetup.png)

Further information:
![Enabling Backend Data Collection [SAP Cloud ALM Expert Portal - OpenTelemetry@SAP]](https://support.sap.com/en/alm/sap-cloud-alm/operations/expert-portal/data-collection-infrastructure.html?anchorId=section_1199289189_c)

## Authentication

- In order to export towards SAP Cloud ALM you have to setup the destination via
    - OAuth based authentication
    - Bind to Destination Service
- Add the below lines to mta.yaml

![Authentification in mta.yaml](authentication_mtayaml.png)