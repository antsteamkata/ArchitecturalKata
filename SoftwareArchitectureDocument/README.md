# Solution Architecture Document
This document provides a comprehensive architectural overview of the Farmacy Family, using a number of different architectural Views to depict different relevant aspects of the system. It is intended to capture and convey the significant architectural decisions which have been made on the system:

- [01. Context View](ContextView/01ContextView.md)
describes where is the Farmacy Family fitting in the Client’s landscape, highlighting the Actors that interact with the Solution and the integrations. It’s a high-level view.
- [02. Logical View](SoftwareArchitectureDocument/02LogicalView.md)
describes the logical components of the Farmcy Family (i.e. the architecturally relevant parts, the layers, the high-level modules)
- [03. Design View](SoftwareArchitectureDocument/03DesignView.md)
 describes architecturally relevant data models used by the Faramcy Family; these data models could be persisted, exposed via API, exposed via UI interfaces.
- [04. Process View](SoftwareArchitectureDocument/04ProcessView.md)
describes architecturally relevant processes executed by the Farmacy Family which can be represented as sequence diagrams or flow diagrams. 
- [05. Integration View](SoftwareArchitectureDocument/05IntegrationView.md)
describes each integration endpoint consumed / exposed by the Farmacy Family, with relevant details (protocol, format, samples)
- [06. Deployment View](SoftwareArchitectureDocument/06DeploymentView.md)
describes the deployment architecture, for each environment that is architecturally relevant.
- [07. Security View](SoftwareArchitectureDocument/07SecurityView.md)
describes the security best practices employed in building the Farmacy Family 
- [08. Implementation View](SoftwareArchitectureDocument/08ImplementationView.md])
 describes development best practices used in building the Farmacy Family on topics like logging, exception handling, layer isolation.
- [09. Quality View](SoftwareArchitectureDocument/09QualityView.md)
describes the mechanisms through which the Farmacy Family is reaching its non-functional requirements.
- [10. Configuration View](SoftwareArchitectureDocument/10.ConfigurationView.md)
this is the configuration manual of the Farmacy Family.
- [11. ADRs](SoftwareArchitectureDocument/11ADRs.md)
describes the main technical decisions that were made, with the reasons and the decision makers.
