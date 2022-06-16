# An open source and collaborative framework for sharing structured archaeological 3D data

**Panel 5**. Electronic Publishing and Open Science in Archaeology

- **Francesca Buscemi**
  - Institute of Sciences of Cultural Heritage, National Research Council
  - via Biblioteca 4, 95124 Catania, Italy
  - [francesca.buscemi@cnr.it](mailto:francesca.buscemi@cnr.it)
 - **Marianna Figuera**
   - Department of Humanities, University of Catania
   - via Biblioteca 4, 95124 Catania, Italy
   - [marianna.figuera@unict.it](mailto:marianna.figuera@unict.it)
- **Giovanni Gallo**
  - Department of Mathematics and Computer Science, University of Catania
  - viale A. Doria 6, 95125 Catania, Italy
  - [giovanni.gallo@unict.it](mailto:giovanni.gallo@unict.it)
- **Angelica Lo Duca**
  - Institute of Informatics and Telematics, National Research Council
  - via G. Moruzzi 1, 56124 Pisa, Italy
  - [angelica.loduca@iit.cnr.it](mailto:angelica.loduca@iit.cnr.it)
 - **Andrea Marchetti**
   - Institute of Informatics and Telematics, National Research Council
   - via G. Moruzzi 1, 56124 Pisa, Italy
   - [andrea.marchetti@iit.cnr.it](mailto:andrea.marchetti@iit.cnr.it)

![An open source and collaborative framework for sharing structured archaeological 3D data](buscemi-figuera-gallo-lo duca-marchetti.jpg)


The CNR-ISPC project W.A.L.(L) "Wall-facing Automatic images identification Laboratory. A quantitative analysis method for the study of ancient architecture" aims to apply quantitative analysis methods and machine learning to the study of ancient architecture.
A purposely conceived data base obtained from 3D photogrammetric models allows to query the architectures and to extract significant features for the archaeologists, in order to analyse aspects such as building techniques and materials, constructive behaviours, social groups engaged in the construction, and chronology.
As International Archaeological Joint Laboratory, the Project encourages partnerships whose members strongly cooperate in sharing architectural data from different archaeological sites and contribute in a collaborative way to the population of the data base through the use of an open source framework.
A multidisciplinary research group composed of archaeologists, mathematicians and computer scientists from Italy, Belgium and France has developed a workflow to fit the goals of the Project.
It focuses on archaeological materials not yet considered in such a study: Prehistoric and Protohistoric architectures from Crete (Phaistos, Ayia Triada, Anavlochos, Sissi). Insofar a Data Set of about 2.000 virtual 3D models of wall stones has been created and shared on a dedicated server.
In the perspective of the open data, the Project foresees a usable web interface to access the data base, with diversified login credentials for different level of users; this also in order to improve the applications of virtual machine processes to the study of archaeological heritage.
The information for the data base was acquired on field at high resolution with standard photogrammetric procedures. The obtained 3D models have been cleaned and decimated to allow an efficient computation. Then they were manually segmented and classified by the archaeologists to obtain a collection of 3D models of the wall face stones.
Geometric analysis is hence performed on each digitized stone to extract a plethora of quantitative data (number of vertexes and triangles of the digital models, surface extension, volume of the convex hull, dimensions of the oriented bounding box, statistics on the normals over the surface, shape index like elongation, flankiness and sphericity). Information about the proximity among stones was also obtained. All these data are useful to build machine learning models that can assist the expert in classification and interpretation of the wall structures.
Images of the wall units in false colour were also produced and have been proved as useful in communication among the experts as well as to the general public.
The Logical Model of a relational data base has been signed to manage and query the virtual 3D models. Fulcrum of the model are the wall face stones and the masonries. Two main aspects were stressed: 1) A correct conceptualization and semantic classification. In fact, because of the lack of data bases specifically addressed to ancient architectural data, the CIDOC-CRM and its extension CRMba devoted to archaeological monuments, were the main reference points. The Art and Architecture Thesaurus of the Getty Institute was the reference vocabulary used to normalise the terminology. 2) The accessibility, according to the FAIR principles, guaranteed by well-defined protocols.
In order to facilitate the insertion of new data into the defined knowledge base by various collaborators, a web application was implemented, based on Django, an open-source framework. At the moment the web application reads the defined data base schema and allows different users to add new entities. In addition, the application manages the automatic import into the data base of already available data, according to the defined format.


**License**
Text and image are relesed under CC BY-ND 4.0 License. Copyright Buscemi, Marianna Figuera, Giovanni Gallo, Angelica Lo Duca, Andrea Marchetti 2022