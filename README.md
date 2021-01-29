# Workshop Network Analysis for the Humanities
## [NYCDH Week 2021](https://nycdh.org/dhweek/) - [NYU Abu Dhabi WIDH](https://nycdh.org/dhweek/sessions-2021/widhnycdh-2021-events/)

**Instructor**: Gustavo Riva

**Date**: Tuesday, February 9, 2021

**Time**: 1000-1200 EST | 1900-2100 GST

**Website**: https://nycdh.org/dhweek/event/network-analysis-for-the-humanities/

## Introduction

The world is full of networks and different topics of study in the humanities can make up networks: people, texts, ideas, etc. This workshop will introduce the basics of network analysis for the humanist. We will learn how to design a network in order to answer research questions in the humanities, how to create and visualize networks with open software and how to interpret some of their most important features and metrics. Participants will practice the skills acquired on a corpus of networks of characters in movies and theater plays.

- Skill level: Beginner

- Prerequisites/requirements: Recommended but not compulsory: installation of Gephi or Cytoscape.

## Contents of this repository

- *shakespeare_graphml*: Character networks from Shakespeare's plays created by [Dracor](https://dracor.org/) .<sup id="a1">[1](#dracor_note)</sup> This format can be uploaded to Gephi<sup id="a2">[how?](#gephi_note)</sup> or Cytoscape<sup id="a3">[how?](#cyto_note)</sup>.

- *GraphCommons_Hamlet.csv*: Character network according to the Graph Commons format

- *GraphCommons_Hamlet.png*: Image of a possible complete network for Hamlet on Graph Commons.

## Using Software for Network Analysis

### Gephi

<b id="gephi_note">Upload:</b>  *File -> Open* (so easy!) for GraphML or *File -> Import Spreadsheet* for csv

**Style**: (Left side) Recommended Layout "Force Atlas 2" or "Fruchterman Reingold". In Appearance change nodes and edges color and size. More options are available after performing some analysis.

**Analysis**: (Right side) "Average Degree" and "Modularity". Performing the analysis stores the values for each node in the data table, so it is possible to use them for color or size of the nodes.

### Cytoscape

<b id="gephi_note">Upload:</b> *File -> Import -> Network from File* for Graphml or *File -> Import -> Table from File* for csv

**Style**: Tab "Style". For options appear as you perform analysis.

**Analysis**: Cytoscape uses a modular system in which you can install new "apps" not included with the basic software that perform specific tasks. You can install new apps using *Apps -> App Manager*. Reccommendation: 

"yFiles Layout Algorithms": Enables more layout algorithms for your network. Find them under the "layout" tab.

"clusterMaker2": Calculates clusters. Recommended: *apps -> clusterMaker -> Community cluster (GLay)*. After performing the analyisis, the result will be added to the data table. You can color the clusters going to *Style -> Fill Color"* and choosing the column *\__glayCluster*

## Notes

<b id="dracor_note">[1](#a1)</b> Fischer, Frank, et al. (2019). Programmable Corpora: Introducing DraCor, an Infrastructure for the Research on European Drama. In Proceedings of DH2019: "Complexities", Utrecht University, doi:10.5281/zenodo.4284002.

