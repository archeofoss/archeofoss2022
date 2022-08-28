# Harris Matrix Data Package: version 2022 of the hmdp tool with new features for the creation of stratigraphy data packages


**Panel 7**. Archaeological stratigraphy data

- **Stefano Costa**
  - Soprintendenza Archeologia Belle Arti e Paesaggio per le province di Imperia e Savona, Ministero della Cultura, Genoa, Italy
  - [Personal website](https://steko.iosa.it/)
  - Email: [stefano.costa@cultura.gov.it](mailto:stefano.costa@cultura.gov.it)
  - ORCID: [0000-0003-1124-3174](https://orcid.org/0000-0003-1124-3174)
  - GitHub: [steko](https://github.com/steko/)
  - Codeberg: [steko](https://codeberg.org/steko/)

The Harris Matrix Data Package is a proposed standard for
archaeological stratigraphy data, based on the well known Data Package
specification and the formalization developed by T. S. Dye together
with the `hm` Lisp package. The `hmdp` tool was first presented at the
ArcheoFOSS 2019 conference and has since been maintained. With version
2022, the `hmdp` tool is getting new features, notably a new `init`
command, with the aim of easier onboarding at the different levels of
detail that the standard allows.

The Harris Matrix Data Package is fully compatible with the `hm` data
format and therefore it allows rich metadata without hindering
interoperability. The metadata descriptor is a JSON file that follows
the Frictionless Data specification.

Since creating datapackage.json manually is error-prone and time
consuming, the new init command can be either run in the directory
containing the already existing CSV files (e.g. contexts.csv and
observations.csv), or it can also be used to create a data package
from scratch, with both the data descriptor and the resource files.

Future research would need to focus on importing data from other
widely used formats.

**License**

[CC BY 4.0 International](https://creativecommons.org/licenses/by/4.0/).
