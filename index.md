---
layout: default
---

## Info Extraction Projects

**[Xponents](https://opensextant.github.io/Xponents)** - Geotagging APIs to work with gazetteers and multilingual extraction of geography, date/time, patterns. A pre-built Docker microservice is available with a complete operational gazetteer and geotagger.  Example applications demonstrate the use of Tika for rendering inputs and GISCore (below) for output formats to demonstrate end-to-end solutions.  The geotagger features the Solr TextTagger.  Last updated 2022-June.

**[OpenSextantToolbox](https://github.com/OpenSextant/OpenSextantToolbox)** - A geotagger and entity extractor employing GATE. Last updated in 2017.


## Semantic Technologies

**[HOWLER](https://opensextant.github.io/OpenSextant-HOWLER/)** - Translate between simple English text and OWL ontologies

**[HOWLER Kanban](https://github.com/OpenSextant/HOWLER-Kanban)** - HOWLER combined with Kanban (based on [Wekan](https://github.com/wekan/wekan) )

## GIS Libraries

**[giscore](https://github.com/OpenSextant/giscore)** - GIS file data format streaming input and output library

**[geodesy](https://github.com/OpenSextant/geodesy)** - Geodetic primitive library

## Retired Modules

* **[opensextant](https://github.com/OpenSextant/opensextant)** - (Retired) The original OpenSextant project. 
 - NOTE: Xponents is the currently maintained geotagger solution.
**[Gazetteer](http://opensextant.github.io/Gazetteer/)** - (Retired) Pipeline project to render world-wide "geo names" data into gazetteers used by these projects
 - NOTE: This Gazetteer required Pentaho 6 or earlier and was stuck to Oracle JDK 8.   Xponents internal gazetteer is current and yields a flexible SQLite intermediate and complete worldwide gazetteer
**[SolrTextTagger](https://github.com/OpenSextant/SolrTextTagger)** - (Retired) A text tagger based on Lucene/Solr. 
 - NOTE: As of Solr 7.4 this tagger plugin was migrated to Apache Solr as a formal request handler
