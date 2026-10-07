## History

* 2013 ~ OpenSextant 1.0 released here on GitHub, courtesy of US Govt agencies sponsoring R&D and prototyping in 
  this field of geospatial awareness tools.  The primary project was a GATE pipeline in Java and other languages.
* 2014 - Xponents collection of libraries partitioned off as lower-level functional libraries
* 2026 - Dave Lutz published HOWLER, an app to work on ontology translation ideas
* 2017 - Consumer projects like Diffeo and VoyagerGIS were spotted citing use of this work
* 2017 - Dave Smiley migrates the SolrTextTagger module formally as the Apache 7.x Solr TextTagger module that lives on
* 2018 - As Pentaho/Kettle pipeline for Gazetteer curation aged, Xponents ported all Gazetteer curation to pure Python, 
  and added additional gazetteer sources
* 2019 - An initial Xponents Docker REST server is built out; Python client illustrates how that works
* 2020 - First cut of Xponents postal/address geotagger and gazetteer released.
* 2023-present - Xponents 3.x series refines support for European, Asian and Middle Eastern languages and scripts

## Inactive Modules

This list of projects and experiments is no longer active, but worth listing here as part of the OpenSextant family.  Last update is noted in each heading.

* **HOWLER**: Ontology translation work. Last update 2016.
  * **[HOWLER](https://opensextant.github.io/OpenSextant-HOWLER/)** - Translate between simple English text and OWL ontologies
  * **[HOWLER Kanban](https://github.com/OpenSextant/HOWLER-Kanban)** - HOWLER combined with Kanban (based on [Wekan](https://github.com/wekan/wekan) )

* **GISCore**: GIS support. Last update 2019.
  * **[giscore](https://github.com/OpenSextant/giscore)** - GIS file data format streaming input and output library
  * **[geodesy](https://github.com/OpenSextant/geodesy)** - Geodetic primitive library
  * The critical elements of GISCore/geodesy have been rolled into Xponents directly.

* **[SolrTextTagger](https://github.com/OpenSextant/SolrTextTagger)** - (Retired) A text tagger based on Lucene/Solr.  Lat updated 2023.
  NOTE: As of Solr 7.4 this tagger plugin was migrated to Apache Solr as a formal request handler.  Xponents SDK uses the Solr TextTagger still. 

* **OpenSextant v1**: Original Gangstah. Last updated 2017.
  * **[OpenSextantToolbox](https://github.com/OpenSextant/OpenSextantToolbox)** - (Retired) A geotagger and entity extractor employing GATE. 
  * **[opensextant](https://github.com/OpenSextant/opensextant)** - (Retired) The original OpenSextant project.  
  NOTE: Xponents is the currently maintained geotagger solution that took over the main functionality.
  * **[Gazetteer](http://opensextant.github.io/Gazetteer/)** - (Retired) Pipeline project to render world-wide "geo names" data into gazetteers used by these projects. 
  NOTE: This Gazetteer required Pentaho 6 or earlier and was stuck to Oracle JDK 8.  
  Xponents internal gazetteer is current and yields a flexible SQLite intermediate and complete worldwide gazetteer

