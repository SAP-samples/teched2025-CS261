# CS261 - Monitoring Custom SAP BTP Application with SAP Cloud ALM for Operations

## Description

This repository contains the material for the SAP TechEd 2025 session called CS261 - Monitoring a custom SAP BTP application with SAP Cloud ALM for operations.  

## Overview

This session introduces attendees to monitoring a custom SAP BTP application. This is done based on a prepared landscape consisting of the instrumented application, a SAP Build Workzone Launchpad service, SAP Cloud Logging, and the active data collection in SAP Cloud ALM. Attendees will monitor their clicks in SAP Cloud ALM and SAP Cloud Logging and explore our latest features. 

![CS261](/exercises/overall_content/CS261_visual.png)

## Requirements

We already prepared the landscape for the session. You can find further details on the required components, settings, and credentials in the [chapter](/landscape_information.md) and embedded links. 

## Exercises

- [Getting Started](landscape_information.md)

- [Health Monitoring](exercises/ex1/)
    - [Familiarize yourself with Health Monitoring](exercises/ex1/1_HealthMonitoring_Base.md)
    - [Exercise 1 - Using Health Monitoring](exercises/ex1/1_HealthMonitoring_Exercises.md#health-monitoring-excercises)
        - [1.1 Adjust Time Frame](exercises/ex1/1_HealthMonitoring_Exercises.md#11-adjust-time-frame)
        - [1.2 Adjust Resolution](exercises/ex1/1_HealthMonitoring_Exercises.md#12-adjust-resolution)
        - [1.3 Which library version is used by the custom app](exercises/ex1/1_HealthMonitoring_Exercises.md#13-which-library-version-is-used-by-the-custom-app)
        - [1.4 Check which Events and Alerts are configured](exercises/ex1/1_HealthMonitoring_Exercises.md#14-check-which-events-and-alerts-are-configured)
        - [1.5 Add Service to Favorites](exercises/ex1/1_HealthMonitoring_Exercises.md#15-add-service-to-favorites)
        - [1.6 Explore What’s New](exercises/ex1/1_HealthMonitoring_Exercises.md#16-explore-whats-new)
        - [1.7 In App Help Use Spots](exercises/ex1/1_HealthMonitoring_Exercises.md#17-in-app-help-use-spots)
    - [Navigate to SAP Cloud Logging](exercises/ex1/1_HealthMonitoring_CloudLogging.md)
        - [1.8 Adjust Time Window and explore exceptions raised for other traces](exercises/ex1/1_HealthMonitoring_Exercises.md#18-adjust-time-window-and-explore-exceptions-raised-for-other-traces)

- [Integration and Exception Monitoring](exercises/ex2/)
    - [Familiarize yourself with Integration and Exception Monitoring](exercises/ex2/2_ExceptionMonitoring_Base.md)
    - [Exercise 2 - Using Integration and Exception Monitoring](exercises/ex2/2_ExceptionMonitoring_Exercises.md)
    - [Navigate to SAP Cloud Logging](exercises/ex2/2_ExceptionMonitoring_CloudLogging.md)

- [Real User Monitoring](exercises/ex3/)
    - [Familiarize yourself with Real User Monitoring](exercises/ex3/3_RealUserMonitoring_Base.md)
    - [Exercise 3 - Using Real User Monitoring](exercises/ex3/3_RealUserMonitoring_Exercises.md)
        - [3.1 Front End Analysis](exercises/ex3/3_RealUserMonitoring_Solutions.md#22-front-end-analysis)
        - [3.2 Check out Related Links](exercises/ex3/3_RealUserMonitoring_Solutions.md#23-check-out-related-links)
        - [3.3 Timeout Error Root Cause Analysis](exercises/ex3/3_RealUserMonitoring_Solutions.md#24-timeout-error-root-cause-analysis)
    - [Navigate to SAP Cloud Logging](exercises/ex3/3_RealUserMonitoring_CloudLogging.md)

- [Business Process Monitoring](exercises/ex4/)
    - [Familiarize yourself with Business Process Monitoring](exercises/ex4/4_BusinessProcessMonitoring_Base.md)
    - [Exercise 4 - Using Business Process Monitoring](exercises/ex4/4_BusinessProcessMonitoring_Exercises.md)
        - [4.1 Create your Custom KPI (Guided Exercise)](
        - [4.2 Check Data Collection (Guided Exercise)](
        - [4.3 Create an Event to be alerted (Guided Exercise)](
        - [4.4 Add an Event with a filter (Guided Exercise)](
        - [4.5 Adjust Graph and work with Views (Guided Exercise)](
        - [4.5 Explore Guided Tours (Guided Exercise)](

**IMPORTANT**

Your repo must contain the .reuse and LICENSES folder and the License section below. DO NOT REMOVE the section or folders/files. Also, remove all unused template assets(images, folders, etc) from the exercises folder. 

## Contributing
Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct
Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License
Copyright (c) 2024 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
