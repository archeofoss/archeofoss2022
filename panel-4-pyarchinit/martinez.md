# Pyarchinit potential and limits in university and research context: San Sisto case study

Panel 4: GIS open source solution for archaeological context in between Universities, Public Administration, societies, research center: pyArchInit case

- **Gianluca Martinez**
  - Dipartimento di Civiltà e forme del sapere
  - G.martinez3\@unipi.it

The adoption of Pyarchinit by the laboratory immediately found the
positive opinion of all the members, who finally had an innovative data
management tool for archaeology. the entire workflow that from the
excavation and data collecton ended in GIS, is here briefly explained.

During the excavation:

Ortophotos are produced in photogrammetry with the use of Metashape and
georeferenced through markers on the ground with total station. Then
they are used to vectorial drawing of the stratigraphic units, carried
out still in Metashape tracing limits for each SU to create a polygonal
shape. This shape is exported as a shp file and imported into qgis,
where it is inserted into a Postgres database through the Pyarchinit
interface. The pyunitàstratigrafiche table allows to computerize the us
through a series of fields that define their characterization. At the
same time, students are also working on computerizing the SU table
through the pyarchinit interface. The customizable thesaurus for
compiling the tables was much appreciated at this stage, especially for
its application in university excavations, where we are dealing with
different archaeological contexts and for which a fixed thesaurus would
certainly have been not exhaustive. The strength of the entire system,
however, is represented by the query-view, which allows to call up in
the map, through a simple query of the database, a specific us or a
group of us and visualize the drawing. This feature was tested in the
site of San Sisto, where through specific queries it was possible to
highlight spatial relationships between different burials, which was the
starting point for some degree theses still in progress.

During editing:

A first obstacle, however, arose during the elaboration of the excavation plants, especially it was difficult to represent with the graphic norms of the archaeological design the points where the SU are cut (a hatch to indicate the point of removal), especially during the edition of the phase plants. The solution adopted in this case was to use a linear layer represented by a white dotted line, traced above the cut section of the US

Material inventory:

The material inventory table allows to manage the recording of the data
without loss of information; the open thesaurus allows to file almost
any type of find. Some problems, however, had arisen with the inventory
number, whose field was not structured with self-increasing value, and
which therefore made it difficult for several subjects to file at the
same time. Problem that however was soon solved with the modification of
the field and the use of the autoincremental value, for which we thank
the availability of the developers. For an accurate recording of the
characteristics of the finds, especially the ceramic ones, intended for
a more specific analysis of the production characteristics, it was also
necessary to record a whole series of features that required a different
structuring of the table, more focused in the registration of both the
production markers and in the decoration and coating techniques

Documentation review and data management:

The possibility of connecting several users simultaneously to the same
database has allowed all the members of the laboratory to work together
to record, catalog and refine the data and archaeological documentation.
After having built a solid base of documentation in the past campaigns,
we are now using the plug-in on field, as a support for the
interpretation of the excavation context, the planning of future
interventions and finally also as a support tool for the teaching
carried out on site regarding the excavation methodology and the use of
information technologies in archeology.

**License**

The text is release under CC BY 4.0 International license, copyright by
Gianluca Martinez

