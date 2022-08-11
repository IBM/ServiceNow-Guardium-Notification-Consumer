# ServiceNow-Guardium-Notification-Consumer
Consume Guardium alerts and other notifications to allow further processing before creating Incidents, Problems, Change Request, and other Tasks.

## Contents
<details open="open">
  <summary><b>Table of contents</b></summary>

  - [Overview](#overview)
  - [Notes](#notes)
  - [Technical Documentation](#technical-documentation)
  - [Design Diagram](#design)
  - [User Roles](#user-roles)
  - [Licensing](#licensing)
  - [Contributing](CONTRIBUTING.md)
  - [Contact us](issues)

</details>

<hr/>

## Overview

This repository holds the **IBM Guardium Notification Consumer** code that serves as a target for IBM Guardium Data Protection notifications from **Alert Builder**, **Risk Spotter**, and **Thread Analytics**.  

**Vulnerability Assessment** results can be integrated far better with the [**IBM Guardium Vulnerability Assessment**](https://github.com/IBM/ServiceNow-Guardium-Vulnerability-Assessment/) plug-in available on the ServiceNow Store.  This plug-in allows the ServiceNow IT admin to integrate vulnerability results into the ServiceNow Vulnerability Response and Configuration Complicance modules providing centralized management of vulnerability data in ServiceNow.

## Notes

- Update Set
	- A ServiceNow administrator can install an Update Set in your ServiceNow instance
	- Follow instructions in the <a href="INSTALLATION.md">Installation document</a>
- Processor Scripts
  - Once this framework is installed, a user with role `x_ibmrt_gdpcon.scripter` or `x_ibmrt_gdpcon.admin` can write scripts to handle the incoming notifications from Guardium.  An example is provided.

## Technical Documentation

- <a href="INSTALLATION.md">Read-me for installation instructions</a>
- <a href="CONTRIBUTING.md">Read-me for developers who wish to contribute to this project</a>

## Design 

![](images/nc-design.png)

## User Roles:

  | Role name | Comments |
  | :---      | :--- |
  | x_ibmrt_gdpcon.producer | Able to create entries in Notifications table |
  | x_ibmrt_gdpcon.producer | Able to create and edit entries in Notifications and Processor Scripts |
  | x_ibmrt_gdpcon.admin | Able to delete entries in Notifications and Processor Scripts |

## Licensing

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
