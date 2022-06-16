**Title of the proposal**

# The new Harris Matrix workflow from pyArchInit to Extended Matrix


**Archaeological stratigraphy data**


**Authors**

- **Enzo Cocca**
  - CNR -ISPC , sede di Napoli
  - [enzo.cocca@cnr.ispc.it](mailto:enzo.cocca@cnr.ispc.it)
  - [@Giano5](https://t.me/Giano5)
  - GitHub: [enzococca](https://github.com/enzococca/)
  - GitHub: [pyarchinit](https://github.com/pyarchinit/)

**Proposal text**

The work proposed here is intended to show the new workflow in pyArchInit4 for generating an Harris Matrix comaptible with Extended Matrix.
The generated matrix will not only include the classical stratigraphic relationship, but also the virtual stratigraphic relationship used into EM.
The tools used for this workflow include:
•	the plug-in for QGIS (version >=3.22) pyarchinit4;
•	the graphviz software;
•	an xml parser written ad hoc to convert a file dot to graphml for yed;
•	the yed  software.
The workflow steps involve recording the relationship information in pyArchInit4, which will be processed by graphviz to generate a 'dot' file and cleaned of redundancies with a tred function. Via an xml parser, the dot file will be converted into a graphml for yed. Finally, with yed, you will open the graphml file to expand it with the swimeline function and save it as a jpg or svg file. Saving it in svg format allows you to make the matrix interactive because it keeps all information (such as attachments) in hypertext. 

![output of an Harris Matrix made by pyarchint4](./cocca.jpg)


**License**

This text is released with CC BY 4.0 license. Copyright Enzo Cocca 2022

