# Solution Architecture Document
This document provides a comprehensive architectural overview of the Farmacy Family, using a number of different architectural Views to depict different relevant aspects of the system. It is intended to capture and convey the significant architectural decisions which have been made on the system:

- [01. Context View](01ContextView.md)
describes where is the Farmacy Family fitting in the Client’s landscape, highlighting the Actors that interact with the Solution and the integrations. It’s a high-level view.
- [02. Logical View](02LogicalView.md)
describes the logical components of the Farmcy Family (i.e. the architecturally relevant parts, the layers, the high-level modules)
- [03. Design View](03DesignView.md)
 describes architecturally relevant data models used by the Faramcy Family; these data models could be persisted, exposed via API, exposed via UI interfaces.
- [04. Process View](04ProcessView.md)
describes architecturally relevant processes executed by the Farmacy Family which can be represented as sequence diagrams or flow diagrams. 
- [05. Integration View](05IntegrationView.md)
describes each integration endpoint consumed / exposed by the Farmacy Family, with relevant details (protocol, format, samples)
- [06. Deployment View](06DeploymentView.md)
describes the deployment architecture, for each environment that is architecturally relevant.
- [08. Quality View](07QualityView.md)
describes the mechanisms through which the Farmacy Family is reaching its non-functional requirements.
- [09. ADRs](08ADRs.md)
describes the main technical decisions that were made, with the reasons and the decision makers.
