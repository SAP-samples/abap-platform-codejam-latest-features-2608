# SAP CodeJam: ABAP Cloud & ABAP RESTful Application Programming Model (RAP) - SPECIAL EDITION

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/abap-platform-codejam-latest-features-2608)](https://api.reuse.software/info/github.com/SAP-samples/abap-platform-codejam-latest-features-2608)   

Welcome to a hands-on workshop that deepens your practical skills of ABAP Cloud and the ABAP RESTful Application Programming Model (RAP). 
In this special edition you'll get exclusive, applied exposure to features delivered in cloud releases 2602–2608 through short demos, guided feature implementation, and expert support. You can also try out relevant features from older releases.

## What's in It for You?
- Refresh your knowledge about core RAP concepts and building blocks: CDS data modeling, behavior definitions, projections, and UI service exposure
- Get to know CDS Table Entities and the option to generate table entity based RAP BOs with the OData Generator from Scratch
- Be guided through the implementation of the latest RAP features:
    - [Best Practice Authorization Scenario](/../../wiki/Best-Practice-Authorization-Scenario) (2608) — a complete end-to-end authorization setup following RAP best practices
    - [ADT in VS Code with MCP Server](/../../wiki/ADT-VS-Code-MCP-Server) (2605) — working with ABAP development tools in Visual Studio Code and leveraging the ADT MCP server
    - [RAP Coding Agents](/../../wiki/RAP-Codeing-Agents) (2608) — first steps towards developing agentic workflows that support RAP development
- Selected topics from CodeJam 2602 are also available:
    - [Draft Scope](/../../wiki/Draft-Scope) (2508)
    - [Recommendations](/../../wiki/Recommendations) (2602)
    - [Analytical Table (Read-Only)](/../../wiki/Analytical-Table) (2511)
    - [Cross-BO with Draft Scope](/../../wiki/Cross-BO-Draft-Scope) (2508)
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
- **VS Code ADT (latest)** installed — [ABAP Development Tools for Visual Studio Code](https://developers.sap.com/group.abap-tools-for-vs-code.html)
- **GitHub Copilot license** — a coding agent extension for VS Code that supports VS Code's virtual workspace filesystem is required to call MCP tools and read/edit ABAP files. GitHub Copilot is the only agent currently supported for this task. See the [event announcement](https://community.sap.com/t5/sap-codejam/sap-codejam-abap-cloud-amp-abap-restful-application-programming-model/ec-p/14460756) for details.
- **GitHub account** — to submit feedback and issues via this repository
- Solid knowledge of ABAP Cloud and RAP development — this event is **not** suited for absolute beginners

## Technical Setup
- A dedicated ABAP System in an SAP BTP ABAP environment (2608) is prepared for this event. Access the Fiori Launchpad here: [TBD - Fiori Launchpad Link]. Follow [this link](#TBD-ADT-bridge-link) to create your ABAP Cloud Project in ADT.
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

# Tell us what you think
We appreciate your feedback. Use any of the options below:
- Provide general feedback for a feature  
Let us know what you think about a feature you implemented:
    - Go to [Issues](/../../issues) in this repository. Choose **New Issue**-->**Feature Feedback**.
    - Select the feature label, complete the form with ratings and comments, and submit.
- Report a problem (bug, documentation issue, enhancement idea, question)  
Help us improve the feature by reporting problems you experience during development: 
    - Go to [Issues](/../../issues) in this repository. Choose **New Issue**-->**Feature Problem Report**.
    - Select the feature label and an additional problem category ( `bug`, `documentation` `enhancement idea`, `question` )
    - Describe your findings and submit.
- Provide event feedback  
You will be asked to participate in a small survey when the event is concluded to give feedback regarding the CodeJam itself
- Talk to the experts. 


## License
Copyright (c) 2026 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.
