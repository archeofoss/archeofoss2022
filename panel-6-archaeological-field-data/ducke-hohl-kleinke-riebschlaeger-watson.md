**Title of the proposal**

# iDAI.field: Developing software for the documentation of archaeological fieldwork


**Panel 6**

Practice and Paradigms of Open Source Technologies for Archaeological Field Data


**Authors**

- **Benjamin Ducke**
  - Deutsches Archäologisches Institut, Berlin, Germany
  - [benjamin.ducke@dains.de](mailto:benjamin.ducke@dains.de)
- **Simon Hohl**
  - Deutsches Archäologisches Institut, Berlin, Germany
  - [simon.hohl@dains.de](mailto:simon.hohl@dains.de)
- **Thomas Kleinke**
  - Deutsches Archäologisches Institut, Berlin, Germany
  - [thomas.kleinke@dains.de](mailto:thomas.kleinke@dains.de)
- **Fabian Riebschläger**
  - Deutsches Archäologisches Institut, Berlin, Germany
  - [fabian.riebschlaeger@dains.de](mailto:fabian.riebschlaeger@dains.de)
  - [@friebsch](https://twitter.com/friebsch)
- **Juliane Watson**
  - Deutsches Archäologisches Institut, Berlin, Germany
  - [juliane.watson@dains.de](mailto:fabian.riebschlaeger@dains.de)


**Proposal text**

The German Archaeological Institute (Deutsches Archäologisches Institut, DAI) conducts a variety of field research types, each with its own unique documentation requirements: Excavations, surveys and building recordings. The resulting differences are reflected in the workflows, the recording methods applied and the documentation produced. In addition, the DAI's international work has to comply with the guidelines of the respective heritage agencies in the host countries.

This results in a whole range of requirements that software for field data recording must fulfil:
-	It must provide a sufficiently flexible, adaptable data model.
-	At the same time, a standardized core data schema should allow for data comparison across geographical, temporal and thematic boundaries.
-	Multilingual data entry must be possible.
-	It must work both offline and online and allow robust methods of (delayed) data synchronisation.

It should also be possible to publish primary research data, together with the research results (narrative), with minimal additional effort, and in accordance with the requirements of the international research community and the funding providers.

An initial version of a unified field recording system for the DAI ([iDAI.field](https://github.com/dainst/idai-field)) was based on the proprietary software Filemaker. This was used and modified by numerous projects at the DAI. However, systematic evaluation revealed severe problems in guaranteeing data quality and comparability as well as integration into existing workflows. Furthermore, the use of proprietary software, and its closed data formats, caused expensive problems with upgrades that broke backward compatibility.

For these reasons, the decision was made to design the new iDAI.field from scratch, relying exclusively on open source software and current Web technologies. The focus of the redesign was on enabling complete documentation of archaeological fieldwork, mapping existing workflows to the new software, and improving them through the use of customised digital technologies. This distinguishes iDAI.field from generic platforms, such as GIS or CAD.

The individual roles of the software were split into separate components: a desktop application for on-site data entry, a server component for synchronisation via the Internet (or a local network) and a dynamic HTML report generator for publishing the primary data.

So far, the focus has been mainly on transferring already known, analogue documentation workflows into the digital application. In the future, it should also be evaluated whether and how the possibilities of using these digital technologies can improve those workflows in order to open up new knowledge discovery processes.


**Illustrative image**

![Archaeological documentation with iDAI.field. Progetto Prile, Vetulonia by Camilla Colombi, CC BY 4.0](idaifield-progetto_prile_colombi.jpg)

Archaeological documentation with iDAI.field. Progetto Prile, Vetulonia by Camilla Colombi, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)


**License**

Text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
Image: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), Camilla Colombi
