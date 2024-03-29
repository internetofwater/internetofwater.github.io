
This is the GitHub page for the [Internet of Water](https://internetofwater.org) project at the Nicholas Institute for Environmental Policy Solutions at [Duke University](https://www.duke.edu). We make a variety of tools to facilitate the opening of water data in United States to lower data-related barriers to sound water policy-making. Tools we are developing on GitHub include:

1. [Glossary](#Glossary): An ontology of water science, data, and policy-related concepts.
2. [Water Budget Framework](#Water-Budget-Framework): An ontology of water budgeting components, estimation methods and models, model parameters, and data sources required to build water budgets.
3. [Data Inventories](#Data-Inventory): We conduct data inventories of the Federal and State governments, systematically identifying which government departments and agencies collect water data, and the discoverability, accessibility, and interoperability of the data they publish.
4. [Real time data reporting](#Reporting). Online/Offline Mobile Data Collection Integrated with Sensor Observation Service

## Glossary

The glossary is managed with [vocbench3](https://purl.org/iow/vocbench3) in an ontology that assigns URIs to unique concepts corresponding to unique definitions. So, terms with conflicting definitions by different organizations are encoded as unique concepts that have a semantic relationship to the same term, which is a unique concept on its own.

The current glossary can be browsed at <https://purl.org/iow/Glossary> (currently for demo purposes only)

The glossary GitHub repository is <https://github.com/internetofwater/glossary>

The underlying ontology is stored in the graph database <https://purl.org/iow/vocbench3/graphdb>


## Water Budget Framework

The water budget framework is an ontology of 5 major concepts:

1. Water Budgeting Framework Developer: Entities that have developed and published frameworks to estimate water budgets. So far, included developers include the [USGS](www.usgs.gov), [California Department of Water Resources](https://water.ca.gov/), and [Utah Department of Water Resources](https://water.utah.gov/).

2. Water Budget Compenent: The distinct flows of water into, out of, and within a given water budgeting zone.

3. Estimation Methods: The methods documented to be in use in estimating water budget components

4. Parameters: The inputs to estimation methods, generally represented by single variables in an estimating model.

5. Data Resources: Sources of raw or modeled data that have been documented to serve as parameters

## Data Inventories

See at <https://internetofwater.org/resources/inventory/>
Code to conduct data inventories is at <https://github.com/internetofwater/DataInventory>


## Reporting

This is a template package of open-source software components that allows for 

1. The offline or online recording of data from water data monitoring sites
2. Registering these sites as "sensors"
3. Publishing the data from these sites over the OGC Sensor Observation Services web service specification
4. Visualizing this data in an attractive user interface

Project is at <https://github.com/internetofwater/DataReportingTemplate>

