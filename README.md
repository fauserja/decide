# DECIDE Toolbox Repository

This repository provides access to the digital tools and components developed within the DECIDE project. The DECIDE Toolbox supports the analysis, development and validation of circular economy business models through a modular, multi-method modelling approach.

The repository currently provides the ADOxx-based DECIDE Modelling Tools as a release download. Additional components, such as the System Dynamics Simulation Component, the Dashboard prototype, the GraphDB-based Data Platform and further documentation, will be added or linked separately.

## Available Components

| Component | Description | Status |
|---|---|---|
| DECIDE ADOxx Modelling Tools | ADOxx-based modelling toolkit for Business Model Canvas (BMC), e3Value, BPMN and Capability Map / Digital Service Implementation Recommender modelling | Available |
| DECIDE System Dynamics Simulation Component | Vensim-based simulation component for dynamic impact analysis and scenario-based assessment of circular economy business models | To be added |
| DECIDE Dashboard Prototype | Web-based dashboard prototype for visualising KPIs and modelling results from the DECIDE Data Platform | Available separately |
| GraphDB-based Data Platform | Semantic data platform based on RDF, GraphDB and a DECIDE-specific knowledge graph structure | To be added |
| Documentation | Installation instructions, user guidance and methodological documentation | To be added |

## Download

The current release contains the ADOxx-based DECIDE Modelling Tools.

**Download DECIDE ADOxx Modelling Tools v0.1:**  
https://github.com/fauserja/decide/releases/download/v0.1/decide-modelling-tool-master.zip

All releases can be accessed here:  
https://github.com/fauserja/decide/releases

## DECIDE ADOxx Modelling Tools

The DECIDE ADOxx Modelling Tools provide a shared modelling environment for selected modelling languages used in the DECIDE Toolbox. The current modelling toolkit includes:

- Business Model Canvas (BMC)
- e3Value
- BPMN
- Capability Map / Digital Service Implementation Recommender

The tools are based on ADOxx and support the modelling of strategic, value-oriented, operational and capability-related aspects of circular economy business models.

## System Dynamics Simulation Component

The System Dynamics Simulation Component supports dynamic impact analysis and scenario-based assessment of circular economy business models.

The System Dynamics models are created and simulated using Vensim. Vensim is external software provided by Ventana Systems and is not included in this repository. Users must obtain Vensim separately from the official provider.

Official Vensim website:  
https://vensim.com/

The repository may later provide DECIDE-specific System Dynamics model files, example models, XMILE exports and documentation for using the models within the DECIDE Toolbox.

## DECIDE Dashboard Prototype

The DECIDE Dashboard prototype is maintained in a separate GitHub repository:

https://github.com/kmpc-makin/decide-dashboard

The dashboard is a web-based monitoring and visualisation prototype for the DECIDE Circular Economy Toolbox. It connects to the DECIDE Data Platform via SPARQL and visualises Key Performance Indicators and modelling results of circular economy business models.

For installation and setup instructions, please refer to the dashboard repository.

## GraphDB-based Data Platform

The GraphDB-based Data Platform is intended to store and integrate model data using RDF and a DECIDE-specific knowledge graph structure.

Model data from the ADOxx-based DECIDE Modelling Tools can be exported and transformed into RDF representations. These data structures can then be stored in GraphDB and used for downstream applications, including the DECIDE Dashboard and other data-driven services.

The setup files and documentation for the GraphDB-based Data Platform will be added separately.

## DECIDE Toolbox Overview

The DECIDE Toolbox is a methodological framework that supports both static and dynamic business modelling in the context of the circular economy. It provides a structured approach to analysing existing business models, identifying circular innovation potentials and developing and validating new circular business models through an iterative multi-method process.

The DECIDE Toolbox supports companies, circular innovators and regional catalysts in the following areas:

- Identifying value creation potentials in line with circular economy principles
- Analysing and assessing existing business models in terms of ecological, economic and social performance
- Identifying optimisation opportunities in existing business models
- Developing and validating new circular business models
- Facilitating the transfer and scaling of circular business models across regions and sectors

The toolbox follows a flexible and modular logic. Depending on the use case, data availability and maturity of the business idea, individual phases can be combined, repeated, skipped or rearranged.

## Methodological Components

The DECIDE Toolbox combines several modelling methods and tools:

- The Circular Economy Value Chain Generator and CEBM Catalogue for opportunity and potential identification
- The DECIDE ADOxx Modelling Tools for BMC, e3Value, BPMN and Capability Map modelling
- The Digital Service Implementation Recommender for mapping business and IT capabilities
- The System Dynamics Simulation Component for dynamic impact analysis and scenario-based decision support
- The DECIDE Dashboard for visualising modelling and simulation results
- The GraphDB-based Data Platform for semantic integration of model data

Together, these components support a multi-perspective analysis of circular economy business models by connecting strategic, operational, infrastructural, value-oriented and dynamic perspectives.

## Planned Repository Structure

The repository will be extended step by step. A possible structure is:

```text
decide/
├── README.md
├── docs/
│   ├── DECIDE_Toolbox_Overview.md
│   ├── Installation_Guide.md
│   └── User_Guide.md
├── modelling-tools/
│   └── README.md
├── system-dynamics/
│   └── README.md
├── dashboard/
│   └── README.md
├── data-platform/
│   └── README.md
└── releases/
