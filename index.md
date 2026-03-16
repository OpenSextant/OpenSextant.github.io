---
layout: default
---

# Info Extraction & Geo-inferencing Projects

**keywords:** geoparsing, geocoding, entity extraction, NER, REGEX 

**[Xponents](https://opensextant.github.io/Xponents)** - Geotagging APIs to work with gazetteers and multilingual extraction of geography, date/time, patterns. 
A pre-built Docker microservice is available with a complete operational gazetteer and geotagger that accepts text.  Example applications demonstrate the use of Tika for 
rendering inputs and GISCore for output formats to demonstrate end-to-end solutions.  The geotagger features the Solr TextTagger.  

Xponents is primarily a Java-based library and web service, with various Python client entry points.   5,000+ downloads on Docker Hub, so far!.

_Last updated 2026-March._


## Inactive Modules

This list of projects and experiments is no longer active, but worth listing here as part of the OpenSextant family.

* **HOWLER**: Ontology translation work.
  * **[HOWLER](https://opensextant.github.io/OpenSextant-HOWLER/)** - Translate between simple English text and OWL ontologies
  * **[HOWLER Kanban](https://github.com/OpenSextant/HOWLER-Kanban)** - HOWLER combined with Kanban (based on [Wekan](https://github.com/wekan/wekan) )

* **GISCore**: GIS support
  * **[giscore](https://github.com/OpenSextant/giscore)** - GIS file data format streaming input and output library
  * **[geodesy](https://github.com/OpenSextant/geodesy)** - Geodetic primitive library
  * The critical elements of GISCore/geodesy have been rolled into Xponents directly.

* **[SolrTextTagger](https://github.com/OpenSextant/SolrTextTagger)** - (Retired) A text tagger based on Lucene/Solr. 
  NOTE: As of Solr 7.4 this tagger plugin was migrated to Apache Solr as a formal request handler.  Xponents SDK uses the Solr TextTagger still. 

* **OpenSextant v1**:
  * **[OpenSextantToolbox](https://github.com/OpenSextant/OpenSextantToolbox)** - (Retired) A geotagger and entity extractor employing GATE. 
  Last updated in 2017.
  * **[opensextant](https://github.com/OpenSextant/opensextant)** - (Retired) The original OpenSextant project.  
  NOTE: Xponents is the currently maintained geotagger solution that took over the main functionality.
  * **[Gazetteer](http://opensextant.github.io/Gazetteer/)** - (Retired) Pipeline project to render world-wide "geo names" data into gazetteers used by these projects. 
  NOTE: This Gazetteer required Pentaho 6 or earlier and was stuck to Oracle JDK 8.  
  Xponents internal gazetteer is current and yields a flexible SQLite intermediate and complete worldwide gazetteer

