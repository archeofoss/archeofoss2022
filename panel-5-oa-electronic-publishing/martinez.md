# Pyarchinit potential and limits in university and research context: San Sisto case study and the Laboratory of Medieval Archaeology of the University of Pisa

**Panel 5**. GIS open source solution for archaeological context in between Universities, Public Administration, societies, research center: pyArchInit case

-  Gianluca Martinez
    - Dipartimento di Civiltà e forme del sapere. Università di Pisa, Pisa, Italy
    - [g.martinez3@unipi.it](mailto:g.martinez3@unipi.it)

The adoption of Pyarchinit by the laboratory took place in the spring of
2021 and immediately found the positive opinion of all the members of
the same, who finally had an innovative data management tool, which
would allow the migration of databases from the old commercial platforms
to the world of open source, more akin to the orientation of
international research and the open data movement. Research has been the
ultimate goal, as well as the guiding tool, of the entire workflow that
from the excavation and data collection has passed through the
processing and refinement of the same in a GIS environment and finally
to the management and storage on an online database. The use of
Pyarchinit took place in this second moment, where we could experience
the potential and limitations of this plug-in, listed below briefly.

During the excavation:

> Ortophoto: produced in photogrammetry with the use of the Metashape
> software, starting from shooting with drone or from the ground with
> SLR and georeferenced through markers materialized on the ground and
> georeferenced with total station.
>
> Vector drawing of the stratigraphic units: the drawing was carried out
> through the use of the Metashape software, with georeferenced
> orthophotos and tracing the layer limits for each US in order to
> create a polygonal shape. This shape is eventually exported as a shp
> file and imported into qgis, where it is inserted into a special
> Postgres database, through the Pyarchinit interface. The
> pyunitàstratigrafiche table allows to computerize the us through a
> series of fields that define their characterization.
>
> At the same time, students are also working on the process of
> computerizing the US cards through the pyarchinit interface, which
> turns out to be a very versatile tool also in the field. The
> customizable thesaurus for compiling the cards was much appreciated at
> this stage, especially for its application in university excavations,
> where we are dealing with different archaeological contexts and for
> which a fixed thesaurus would certainly have been not exhaustive. The
> strength of the entire system, however, is represented by the
> query-view, which allows to call up in the map, through a simple query
> of the database, a specific us or a group of us and visualize the
> drawing. This feature was tested in the site of San Sisto, where
> through specific queries it was possible to highlight spatial
> relationships between different burials, which was the starting point
> for some degree theses still in progress.
>
> During editing:
>
> A first obstacle, however, arose during the elaboration of the
> excavation plants, especially it was difficult to represent with the
> graphic norms of the archaeological design normally used by us, the
> points where the US are cut (or with the hatch to indicate the point
> of removal), especially during the edition of the phase plants. The
> solution adopted in this case was to use a linear layer represented by
> a white dotted line, traced above the cut section of the US

Material inventory:

The pyarchinit database contains several tables dedicated to the
recording of information from excavation finds. We tested the level of
detail of the material inventory table***.*** A fundamental premise to
do is that regarding the excavation of San Sisto, we found such several
finds and such a variety of classes that allowed us to deepen the
analysis and classification of the finds, and it was also possible to
seriously test the level of detail offered by the card. As in the usual
classification, like subdivision into type, material class, shape etc ..
the material table allows you to manage the recording of the data in an
optimal way and without loss of information. In addition, the open
thesaurus allows you to file almost any type of find, as happened in our
excavation where we have a range of ceramic classes ranging from VIII
b.c. about until the twentieth century. A first problem, however, had
arisen with the inventory number, whose field was not structured with
self-increasing value, and which therefore made it difficult for several
subjects to file at the same time. Problem that however was soon solved
with the modification of the field and the use of the autoincremental
value, for which we thank the availability of the developers. Returning
to the level of detail of the card, we realized that the composition of
the fields and the generality with which the production data is treated
were unsatisfactory for our work. For the purpose of an accurate
recording of the characteristics of the finds, especially the ceramic
ones, intended for a more specific analysis of the production
characteristics, it was also necessary to record a whole series of
features that required a different structuring of the table, more
focused in the registration of both the production markers and in the
decoration and coating techniques

Documentation review and data management:

As previously mentioned, the entire system relies on a postgres
database, to which you always connect through the pyarchinit interface.
The possibility of connecting several users simultaneously to the same
database has allowed all the members of the laboratory, each with its
own specialization, to work together to record, catalog and refine the
data and archaeological documentation, from the tables to the materials
and topographic surveys. After having built a solid base of
documentation in the past campaigns, we are now using the plug-in in the
excavation, still in progress, as a support for the interpretation of
the excavation context, the planning of future interventions and finally
also as a support tool for the teaching carried out on site with regard
to the excavation methodology and the use of information technologies in
archeology.

License

The text is release under CC BY 4.0 International license, copyright by
Gianluca Martinez

