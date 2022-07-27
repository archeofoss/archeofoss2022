# Revising the Gazetteer model - Places Of The Past

**Panel 1**. Maps to the past. Open digital approaches to the investigation of historical maps

- **Marco Montanari**
  - Open History Map, Bologna, Italy
  - [marco.montanari@openhistorymap.org](mailto:marco.montanari@openhistorymap.org)
  - [@ingmmo](https://twitter.com/ingmmo)
  - ORCID: [0000-0001-5026-6083](https://orcid.org/0000-0001-5026-6083)


Textual sources and maps help us understand and contextualize the past. These elements are transformed into Gazetteers for us to use and work on. The maps, in addition, can be georeferenced and warped to get a glimpse of how the world was perceived in the past, what was considered relevant and what not and how the views of the world changed. For this reason we are here proposing a new methodology to merge the two operations and to make it easy for citizen scientists to work on the two parts, giving us the best of both worlds. 

The OHM Places platform we are presenting unifies the approach to the attestation and positioning of the named locations from the maps by exposing a simplified API to validate names and merges the information by inferencing the additional information about the context. The match is created by name and considering the other points added as context. 

The OHM Places platform transforms each document (map or text file) into a DOI via Zenodo. From this moment on each transformation is documented and tracked into a dataset stored beside the image. 

When warping the map, obviously, it will be difficult to get a perfect topologic match, so a general "sensible" approach is considered and the deformation is  very outlying points are ignored and flagged to be verified. In case the points are right and their location was correctly pointed out, the gazetteer will have information about the variant in a strange location.

All data, cleaned up, will finally be transformed into a set of files to be used by other parties: 
- Geographic Control Points are stored in Zenodo and Github
- The gazetteer data is stored as CSV file and uploaded to World Historical Gazetteer
- Every step of the process is documented via DOIs and their interconnections.

The paper presents the tool and covers the process of gazetteer creation from a methodological point of view.

**License**

Texts and images are released under [CC BY 4.0 International](https://creativecommons.org/licenses/by/4.0/) license.
