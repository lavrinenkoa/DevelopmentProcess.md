# Engenering Process Developing

Let's describe the development process using waterfall as an example, since other development processes are built from similar elements. For example, by adding additional iterative steps, returns to previous stages, a combination of phases.

**Development phases:**

**A. Requirements defenition:**
   - [Opportunity infrastructure setup](Opportunity-infrastructure.md);
   - [Requirements analysis](Requirements-analysis.md);
   - [Estimation](/Development-Process/Estimation.md);

**B. Design:**
   - [Project infrastructure setup](Project-infrastructure.md);
   - [Software design](Software-design.md);

**C. Implementation:**
   - [Development infrastructure setup](Development-infrastructure.md);
   - [Implementation](Implementation.md);
     - [Code Development](Implementation/Code-Development.md);
     - [Development infrastructure update](Development-infrastructure.md#Update);
     - [Continuous Deployment](Deployment.md);
   - [Testing](Testing.md);

**D. Delivery:**
   - [Delivery](Delivery.md);
   - [Maintenance](Maintenance.md);
   - [Support](Support.md);

**E. Person Involvement:**
   - [Person Onboarding](Onboarding.md);
   - [Person Releasing](Releasing.md);



```mermaid
graph TB
  subgraph "Engenering development phases"
  Requirements[Requirements analysis] --> Estimation[Estimation]
  Estimation --> Design[Software design]
  Design --> Implementation[Implementation]
  Implementation --> Deployment[Deployment]
  Deployment --> Testing[Testing]
  Testing --> Installation[Installation]
  Installation --> Maintenance[Maintenance]
  Maintenance --> Support[Support]

  Onboarding[Person Onboarding] --> Releasing[Person Releasing]
end
```

---

**Appendix:**
* [Roles list](Roles.md);
* [Code Style](Code-Style.md);
* [Documents Examples](Documents-Examples.md);
* [Common practic](Common-practic.md);






    
