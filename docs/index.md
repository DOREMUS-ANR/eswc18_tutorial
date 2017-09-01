---
mainTitle: DOing REusable MUSical data
title: DOREMUS Tutorial at K-CAP 2017
layout: default
---

# Abstract
Music metadata can be very complex. Describing a classical masterpiece in all its form (the composition, the score, the various publications, a performance, a recording, the derivative works, etc.) is a complex activity. An even more challenging tasks consist in describing jazz and ethnic music for which the performance plays a central role, the music is generally not written and the authorship is not well defined.

DOREMUS is a research project that aims to develop tools and methods to describe, publish, interconnect and contextualize music catalogues on the web using semantic web technologies. Its primary objective is to provide common knowledge models and shared multilingual controlled vocabularies as well as to publish and provide access to large volume of linked data generated from music archives.

Since its beginning in late 2014, the main contributions of the project includes the definition of the DOREMUS ontology a musical extension of the FRBRoo model for the description of cultural objects. In addition to the ontology, a set of music specific controlled vocabularies has been published. The data coming from the rich musical archives of three leading cultural institutions in France — the Bibliothèque Nationale de France (BnF), the Philharmonie de Paris (PP) and Radio France (RF) — are being progressively harmonised and published in the Web of Data. For this reason, a series of tools for data conversion, visualisation and recommendation have been developed.

The aim of this tutorial is first to provide in-depth explanations of the DOREMUS model (and its underlying foundations, CIDOC-CRM and FRBRoo) as well as the necessary controlled vocabularies. We will demonstrate how real data coming from musical libraries can be converted to this model and be transformed to be compliant to Schema.org for various consumption scenarios. The entire DOREMUS tools chain will be presented (e.g. tools for reconciling large multilingual knowledge graphs). We will illustrate how the DOREMUS data can be consumed through various applications including an exploratory search engine and music recommender systems. Finally, we will propose several hands-on for the audience to play with the DOREMUS data.

This tutorial is the direct continuation of the ones given at ESWC 2016 and IAML 2016: beyond the modelling challenges, we will focus on data quality and consumption, and knowledge-graph empowered applications including recommender systems.

# Intended Audience
We expect participants from various areas of research that are represented in the Knowledge Engineering community such as: information extraction, knowledge modeling, multimedia processing, data mining, data science, human-computer interaction, humanities, and web information systems. We assume that most participants will be familiar with the basic principles of the semantic web. This tutorial proposal is for a half-day and intends to attract around 25-35 participants.

# Tutorial Structure

The tutorial will be decomposed into three parts, consisting each of slides and hands-on exercises:

The first part will present the DOREMUS model. Starting from describing real problems of modeling classical and traditional music, several examples and best practice will be shown for representing the works, their interpretations (e.g. concerts), publications (e.g. scores) and manifestations (e.g. musical albums). Cases and problems specific to the music knowledge representation will be detailed. We will argue for the choice of using CIDOC-CRM and FRBRoo as foundations and we will illustrate how the resulting complex model can also be converted into a simpler Schema.org one. Finally, we will present the numerous controlled vocabularies that are being developed by the community such as musical genres, musical instruments, etc.
The second part deals with the problems of converting, interconnecting and publishing data following those models. We will present the marc2rdf tool for converting data from the librarian MARC standard in RDF following the models described previously, with particular attention to some critical issues in the librarian files. We will highlight what are the key ontology matching problems for interlinking those datasets. Finally the audience will learn how to access to DOREMUS data and how they can answer interesting complex questions, that fulfill some real needs of musical institution like the writing of a concert program or collecting information for a musicologist study.

The third part of this tutorial will present [Overture](http://overture.doremus.org), a modern web application that provides an exploratory search engine on top of this data. The audience will be encouraged to play with the application in order to discover its advanced search and the recommendation section. We will also present methods and datasets for training recommendation engines based on web radio programs and Spotify playlists. The tutorial will conclude with a deeper look about the recommendation of music using knowledge graphs and neural networks.

# Tutors

### Pasquale Lisena, EURECOM, Sophia Antipolis, France
[pasquale.lisena@eurecom.fr](mailto:pasquale.lisena@eurecom.fr) - [http://pasqlisena.github.io/](http://pasqlisena.github.io/)

Pasquale Lisena is currently a PhD candidate in the Data Science department at EURECOM, working on music representation and recommendation under the supervision of Raphaël Troncy. He got his Master in Media Engineering at Politecnico di Torino, and he has a previous work experience in the field of Web Interaction. Since 2016, he is part of the DOREMUS project, being in charge of the knowledge base population and recommendation tasks, contributing papers to conferences in the field like ISWC and EKAW.

### Raphaël Troncy, EURECOM, Sophia Antipolis, France
[raphael.troncy@eurecom.fr](mailto:raphael.troncy@eurecom.fr) - [http://www.eurecom.fr/~troncy/](http://www.eurecom.fr/~troncy/)

Raphaël Troncy is an associate professor in the Data Science department at EURECOM whose research mainly concerns the use of semantic web technologies in multimedia systems, knowledge modeling for information systems, data integration, knowledge extraction and web science in general. He is the primary investigator of a number of national (e.g. ACAV, Datalift, DOREMUS, ASRAEL, NexGen-TV) and EU projects (e.g. Apps4Europe, LinkedTV, MediaMixer, 3cixty, PasTime) in the area of this tutorial proposal. He was a co-organiser of numerous workshops (DeRiVE 2011, 2012, 2013, 2015), SemStats (2013, 2014, 2015, 2016, 2017), LiME (2014, 2015, 2016) at ESWC, ISWC or WWW. He also gave numerous tutorials at WWW (2014, 2008), ESWC (2016) and ISWC (2008, 2009).
