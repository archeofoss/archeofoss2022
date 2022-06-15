# Stratigraphic data in R

**Panel 7**: Archaeological stratigraphy data


- **Joe Roe**
  - Institute of Archaeological Sciences, University of Bern
  - [joe@joeroe.io](mailto:joe@joeroe.io)
  - [joeroe.io](https://joeroe.io)


Handling stratigraphic data in R is, in a word, easy.
Plain text data can be readily imported using its base library, and it is relatively straightforward to extend these tools to parse more complex formats such as the LST files used by BASP Harris, ArchEd and Stratify.
Archaeological stratigraphies are perhaps best seen as a special class of directed graph ([Dye & Buck 2015](https://doi.org/10.1016/j.jas.2015.08.008)) and R also offers a rich set of add-on packages for network analysis. 
The core package [igraph](https://igraph.org/r/) implements a comprehensive collection of algorithms for constructing, analysing, and visualising networks, and is itself a wrapper for the igraph C library, providing interoperability with C++, Python, and Mathematica through parallel APIs.
With igraph and its extensions it is, for example, trivial to reproduce the classic 'Harris matrix' visualisation of stratigraphic graphs, or to assess the stratigraphic validity of the network by checking for cycles.
Functions for performing these procedures with archaeological stratigraphic data are implemented in the R package [stratigraphr](https://stratigraphr.joeroe.io).

A slightly more difficult problem is exposing stratigraphic networks to other types of analysis.
igraph provides an excellent domain-specific language for network analysis, but extracting the underlying graph data for other purposes typically involves a painful amount of 'data munging'.
This problem is especially relevant for stratigraphic data, which is rarely used as the sole unit of analysis in itself, but more often as a covariate or prior alongside other types of data, as for example in Bayesian radiocarbon modelling.
Achieving this is made easier with [tidygraph](https://tidygraph.data-imaginist.com/) and [ggraph](https://ggraph.data-imaginist.com/), which provide grammars for manipulating and visualising graph data within the widely-used 'tidy data analysis' paradigm.
Extending this philosophy, recent development of stratigraphr has focused on integrating with [c14](https://c14.joeroe.io/) to provide a consistent and 'tidy' interface for working with stratigraphic and radiocarbon data together.
For example, we can combine these tools to describe Bayesian stratigraphic models in R using stratigraphr's implementation of the Chronological Query Language (CQL, [Bronk Ramsey 2016](https://doi.org/10.1017/S0033822200018348)), and export them to [OxCal](https://c14.arch.ox.ac.uk/oxcal.html) for fitting using [oxcAAR](https://github.com/ISAAKiel/oxcAAR).
Apart from OxCal, all the software mentioned here is free and open source; a useful future extension to these packages would therefore be to eliminate this dependency and implement direct Bayesian inference from the stratigraphic graph, as suggested by Dye and Buck.

**License**

This text is released with [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Copyright Joe Roe 2022.
