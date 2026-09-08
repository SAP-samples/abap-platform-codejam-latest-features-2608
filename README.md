# SAP CodeJam: ABAP Cloud & ABAP RESTful Application Programming Model (RAP) - SPECIAL EDITION

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/abap-platform-codejam-latest-features-2608)](https://api.reuse.software/info/github.com/SAP-samples/abap-platform-codejam-latest-features-2608)   

Welcome to a hands-on workshop that deepens your practical skills of ABAP Cloud and the ABAP RESTful Application Programming Model (RAP). 
In this special edition you'll get exclusive, applied exposure to features delivered in cloud releases 2602–2608 through short demos, guided feature implementation, and expert support. You can also try out relevant features from older releases.

## What's in It for You?
- Refresh your knowledge about core RAP concepts and building blocks: CDS data modeling, behavior definitions, projections, and UI service exposure
- Be guided through the implementation of the latest RAP features:
    - [RAP BOs based on CDS Table Entities](/../../wiki/1-RAP-BOs-based-on-CDS-Table-Entities) (2605) - Get to know CDS Table Entities and the option to generate table entity based RAP BOs with the OData Generator from Scratch   
    - [Implementing Authorizations](/../../wiki/2-Implementing-Authorizations) (2608) — a complete end-to-end authorization setup following RAP best practices
    - [ADT in VS Code with the ADT MCP Server](/../../wiki/3-VS-Code---ADT-Basics-—-Creating,-Activating,-and-Running-ABAP-Objects) (2605) — working with ABAP development tools in Visual Studio Code and leveraging the ADT MCP server
    - [Configure a Custom Copilot Agent](/../../wiki/4-Configure-a-Custom-Copilot-Agent) (2608) — first steps towards developing agentic workflows that support RAP development
- Selected topics from CodeJam 2602 are also available:
    - [Draft Scope](/../../wiki/5-Collaborative-Draft) (2508)
    - [Cross-BO with Draft Scope](/../../wiki/6-Draft-Scope) (2508)
    - [Analytical Table (Read-Only)](/../../wiki/7-Analytical-Table) (2511)
    - [Recommendations](/../../wiki/8-Recommendationss) (2602)
    
    
- Make use of various feedback options
  
## Agenda and Format
- 10:00 : Introduction and feature presentations
- 11:00 : Feature implementation I
- 13:00 : Lunch (Cantine)
- 14:00 : Feature implementation II
- 15:30 : Closing

Work on any presented feature, combine features across your RAP business objects, and experiment freely. Feature experts will be available throughout for questions and feedback.

## Prerequisites
- **Eclipse ADT (latest)** installed — [Installation Tutorial](https://developers.sap.com/tutorials/abap-install-adt.html)
- **VS Code ADT (latest)** installed — [ABAP Development Tools for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=SAPSE.adt-vscode)
- **GitHub Copilot license** — a coding agent extension for VS Code that supports VS Code's virtual workspace filesystem is required to call MCP tools and read/edit ABAP files. GitHub Copilot is the only agent currently supported for this task. See the [event announcement](https://community.sap.com/t5/sap-codejam/sap-codejam-abap-cloud-amp-abap-restful-application-programming-model/ec-p/14460756) for details.
- **GitHub account** — to submit feedback and issues via this repository
- Solid knowledge of ABAP Cloud and RAP development — this event is **not** suited for absolute beginners

## Technical Setup
- A dedicated ABAP System in an SAP BTP ABAP environment (2608) is prepared for this event. Access the Fiori Launchpad here: [Fiori Launchpad Link](https://b8443c56-ceb0-4a12-8f4b-d0a004bb2f72.abap.eu10.hana.ondemand.com/ui#Shell-home). Follow [this link](https://adt.only.sap/bridge.html#adt://AI3?sap-adt-project-type=abap-http&sap-adt-project-instance-url=https://b8443c56-ceb0-4a12-8f4b-d0a004bb2f72.abap.eu10.hana.ondemand.com/&sap-adt-project-system-id=AI3) to create your ABAP Cloud Project in ADT.
- To log on to the service instance, use your assigned username and password.
- You have been assigned a participant number (for example ###=042) and corresponding development packages ZDEVELOPER_### are already available in the system.
- Please work inside your assigned packages. There is one subpackage for every feature available.

## Resources
- This [CodeJam repository](./../../), especially the feature guides in the [Wiki](/../../wiki/)
- ABAP Flight Reference Scenario
    - [Flight Reference Scenario on GitHub](https://github.com/SAP-samples/abap-platform-refscen-flight/tree/ABAP-platform-cloud)
    - [Flight Reference Scenario in the System](#TBD-system-flight-package-link) in the package `/DMO/FLIGHT`
- [RAP Documentation](https://help.sap.com/docs/abap-cloud/abap-rap/abap-restful-application-programming-model?ai=true&locale=en-US&version=LATEST) on the SAP Help Portal
- [RAP on SAP Community](https://pages.community.sap.com/topics/abap/rap)
- [ABAP Cheat Sheets](https://github.com/SAP-samples/abap-cheat-sheets)
- The RAP Experts present at the event - get in touch!

### RAP Outlook
[ABAP Platform - Roadmap Information](https://help.sap.com/docs/abap-cross-product/roadmap-info/abap-platform-roadmap-information?locale=en-US)

## Tell us what you think
We appreciate your feedback. Use any of the options below:
- Provide feedback or report a problem for a feature. Whether you want to rate a feature or report a bug, documentation issue, enhancement idea, or question — use the single combined form:
      Go to Issues in this repository.
      Choose New Issue-->Feature Feedback & Issue Report.
      Select 💬 Feature Feedback or 🔴 Issue Report at the top of the form, fill in the relevant section, and submit.
- Provide event feedback.
  You will be asked to participate in a small survey when the event is concluded to give feedback regarding the CodeJam itself
- Talk to the experts.

## License
Copyright (c) 2026 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.
