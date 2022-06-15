**Title of the proposal**

# An open image atlas for the journal "Archeologia e Calcolatori"

**Name of the selected panel**

Electronic Publishing and Open Science in Archaeology

**Authors**

- **Nicolò Paraciani**
  - ISPC, CNR, Rome, Italy
  - [nicolo.paraciani@cnr.it](mailto:nicolo.paraciani@cnr.it)
- **Irene Rossi**
  - ISPC, CNR, Rome, Italy
  - [irene.rossi@cnr.it](mailto:irene.rossi@cnr.it)

**Proposal text**

Open Science best practices and policies have been increasingly promoted and adopted in Europe and worldwide to extend public availability of research data and publications, according to FAIR principles. In this context, the so-called ‘Diamond Open Access’ model is particularly relevant since it entails provision of scientific content entirely free of charge, both for authors and readers. The journal Archeologia e Calcolatori adopted this model at a very early stage, when - in 2005 - it started publishing online full-text PDFs and metadata of its articles according to recognised standards, as an Open Archives Initiative data provider.

Very recently, the online version of the journal was enriched with the presentation of visual media related to publications, more specifically figures and 3D models. These were also annotated with standard metadata and treated as individual resources, both on the [journal's website](http://www.archcalc.cnr.it) and in its OAI-PMH repository. The 3D models were presented online by embedding the [ATON framework](https://github.com/phoenixbf/aton) as an interactive web viewer. This work, which will be illustrated in the first part of the paper, has been applied to publications from 2021 onward.

Moreover, to valorise the extensive amount of visual media produced by the journal in its previous, thirty-year long history, the Editorial Board has decided to create a dedicated web application to present this content in a structured and visually appealing manner, which will work as an atlas of images. With the collaboration of the journal's Publisher, image files related to article figures were gathered and their metadata were imported in the journal's relational database, so that they could be manipulated programmatically. To this end, the existing framework that manages Archeologia e Calcolatori's website and repository - built in PHP - was extended to provide a server API that retrieves data from the database and serves them in a structured JSON format. This data is then consumable by a dedicated front-end - the atlas - presenting the images in galleries, browsable by volume and by article. The API can also serve as an independent REST endpoint to be queried by external services.

The perspectives that this work on the visual contents of the journal opens up, in terms of metadata enrichment, new search functionalities and data reuse, will also be discussed.
