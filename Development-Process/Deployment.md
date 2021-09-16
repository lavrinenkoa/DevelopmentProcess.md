[Up](Implementation.md) | [Home](Overview.md) | [Next step](Testing.md)

---
# Continuous Deployment
---
Roles:
* [Technical Coordinator(TC)](Roles.md#technical-coordinator-tc) - Receiving Building, UT, installation reports and monitoring iessue statisstic;
* [Software Engineer (SE)](Roles.md#software-engineer-se) - Receiving Building, UT, installation reports;
* [DevOps](Roles.md#devops-engineer-devops) - Automating Continuous Deployment procedure. Resolving Deployment procedure issues.

Input objects:
* Develop environment specification (OS, library, lang, IDE);
* Deploy environment specification (OS, Lib);
* Detailed Design Document (DDD), UI Design, DB Design;
* Code repository;
* Build Server VM;
* Deploy VMs.

Tasks:
* Automaticaly code building;
* Automaticaly UT passing;
* Product deploy on test environment.

Output objects:
* Deploy VM with current product version ([DevOps](Roles.md#devops-engineer-devops));
* Building, UT, installation reports (Automaticaly).

Check points:
* Check code and product version.

---
[Up](Implementation.md) | [Home](Overview.md) | [Next step](Testing.md)