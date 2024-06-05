[![ENERSHARE](./wp-content/uploads/logo_Enershare_White.png)]([http://enershare.eu/](https://enershare.eu/wp-content/uploads/logo_Enershare_White.png))
# Enershare MVP2.0
## TSG connector
###  Description and purpose
One example of an IDSA Connector is the TNO Security Gateway (TSG) Core Container. The TSG container operates as a base for data space components and can be easily integrated with data apps. These data apps can perform the business logic for both data consumers and providers, in the same way that is desired in ENERSHARE. 
####  Description and purpose
The TSG Connector performs seamless collaboration and data sharing, supporting the ENERSHARE participants to leverage the maximum potential of their data components and assets and evolve their practices. Additionally, based on the TSG concept simultaneously with the IDSA architecture, the TSG connector ensures the establishment of very specific rules and principles customized and aligned according to the ENERSHARE objectives. TSG Connector is an IDSA-based HTTP Multipart communication, performing message flows and being easily deployable.
Development progress and goals
The TSG Connector is developed in Kotlin and built within Docker images. Its default deployment phase is based on Helm.Kubernetes and Kubernetes. More detailed technical and structural details about the TSG Connector can be found in  https://tno-tsg.gitlab.io/ , https://gitlab.com/tno-tsg/core-container and https://gitlab.com/tno-tsg/helm-charts/connector . A set of 15 connectors have been deployed within Enershare data space and can be found in https://daps.enershare.dataspac.es/#connectors . Regarding ENERSHARE, the MVP version 1 deployed TSG and its related components. Regarding future development work, an  updated version of TSG connector will be developed in Q2.

Tools and sub-components
The usage control functionality that is provided by TSG Connector and the individual components that perform it are presented in section 5.2.2 in ENERSHARE deliverable D4.2. These sub-components and entities are nominally, the Policy Enforcement Point, the Policy Decision Point, the Policy Administration Point and the Policy Information Point.
The technical description of the communication and data exchange between a data provider’s TSG connector and a data consumer’s TSG connector is presented in detail in section 5.3.4 in the ENERSHARE deliverable D4.2. The involved sub-components and the steps that are performed in order to communicate two TSG connectors are presented in a sequence diagram in the aforementioned section.


# Deployment view
