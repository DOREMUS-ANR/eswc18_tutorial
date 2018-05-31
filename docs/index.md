---
title: Abstract
layout: default

navigation_weight: 1
---

# Abstract
Music information can be very complex. Describing a classical masterpiece in all its form (the composition, the score, the various publications, a performance, a recording, the derivative works, etc.) is a complex activity. An even more challenging tasks consist in describing jazz and ethnic music for which the performance plays a central role, the music is generally not written and the authorship is not well defined.

In the context of the [DOREMUS](http://www.doremus.org) research project, we develop tools and methods to manage music catalogues on the web using semantic web technologies. So far, the main contributions of the project includes the definition of the [DOREMUS ontology](http://data.doremus.org/ontology), a musical extension of the [FRBRoo model](https://www.ifla.org/publications/node/11240) for the description of cultural objects; A set of music specific controlled vocabularies for music; Large datasets coming from the rich musical archives of three leading cultural institutions in France — the [Bibliothèque Nationale de France](http://www.bnf.fr/) (BnF), the [Philharmonie de Paris](https://philharmoniedeparis.fr) (PP) and [Radio France](http://www.radiofrance.fr/) (RF) — describing musical works, publications, performances and concerts. For this reason, a series of tools for data conversion, visualisation and recommendation have been developed.

The first goal of this tutorial is to provide in-depth explanations of the DOREMUS model (and its underlying foundations, CIDOC-CRM and FRBRoo) as well as the necessary controlled vocabularies. We will demonstrate how real data coming from musical libraries, once converter to RDF format and interlinked to the Linked Open Data (DBpedia, Geonames), became a powerful resource for answering music specific question which are of interest for musicologists, librarians, concert hall programmers, etc. In this context, we will propose several hands-on for the audience to play with the DOREMUS data.

The second goal of this tutorial is to offer a deep dive in knowledge-based recommender systems, and in particular, how knowledge graph embeddings and neural networks can be used to provide recommendations. We will show how this data richness can be used for realising a content-based recommender system and which strategies shall be followed for adapting the recommendation to different contexts and explaining the recommendation to final users.

# Previous experiences

As DOREMUS group, we had already experiences in Tutorials about music and Semantic Web, like the ones given at ESWC 2016, IAML 2016 and [K-CAP 2017](https://doremus-anr.github.io/kcap17_tutorial/): beyond the modeling challenges, we will focus on the usage of the knowledge-graph for fulfilling practical needs, in particular music recommendation.

# Intended Audience
We expect participants from various areas of research that are represented in the Semantic Web community such as: information extraction, knowledge modeling, machine learning, recommender systems and human-computer interaction. We assume that most participants will be familiar with basic semantic web technologies (RDF, SPARQL, Knowledge Graphs). This tutorial proposal is for a half-day and intends to attract around 25-35 participants.

# Tutorial Structure

The tutorial will be decomposed into two parts, consisting each of slides and hands-on exercises.

The first part will present the **DOREMUS model and knowledge graph**. Starting from describing real problems of modeling classical and traditional music, several examples and best practice will be shown for representing the works, their interpretations (e.g. concerts), publications (e.g. scores) and manifestations (e.g. musical albums). Cases and problems specific to the music knowledge representation will be detailed. As support for the model, we will present the numerous controlled vocabularies that are being developed by the community such as musical genres, musical instruments, etc. Finally we will show how the model and the vocabularies, materialised in the DOREMUS dataset, can answer interesting complex questions, that fulfill some real needs of musical institution like the writing of a concert program or collecting information for a musicologist study.

The second part of this tutorial will present methods and datasets for training **recommendation engines**. The topic that will be covered are:
- Which recommender system strategies are currently used in the music field;
- How to define the similarity between entities at different levels of music description (genres, musical keys, artists, works, concerts) through _embeddings_;
- How to _tune up_ a recommender system through machine learning technologies, trained on live performance programs and playlists.
<!-- - A reverse engineering task: _explain why_ the system produced that specific recommendation, and propose visualisation of such explanations to final users. -->
