# SemMorphDBase

These are the source code ontologies for two modules of semantic Morph·D·Base. SCMDB-Basic contains specifications of general features and processes of semantic Morph·D·Base. SCMDB-MD contains specifications for the module for morphological descriptions and SCMDB-S specifications for the specimen module. These source code ontologies as based on Semantic Programming and use terms from the Semantic Programming Ontology (SPrO; https://github.com/SemanticProgramming/SPrO). 
SPrO can be used like a programming language with which one can control a data-centric Semantic Web application by describing it within a corresponding source code ontology. SPrO consists of ontology classes, individuals and properties that the accompanying Java-based middleware (see https://github.com/SemanticProgramming/Interpreter) interprets as commands and variables. The commands are defined as annotation properties. Specific values and variable-carrying resources are defined as ontology individuals. Additional object properties are used to specify relations between resources, and data properties are used for specifying numerical values or literals for resources that describe the Semantic Web application. SPrO can be used to describe the graphical user interface (GUI), data representations, user interactions, and all workflow processes of a Semantic Web application. The descriptions are written in a corresponding source code ontology. The Java-based middleware functions as an interpreter that dynamically interprets and executes the descriptions in this source code ontology by interpreting them as declarative specifications. 

The following data schemes, database processes, and entry form and graphical user interface (GUI) specifications have been developed for semantic Morph·D·Base and fully described in the three source code ontologies as well as documented through vue files:
* data schemes 
  * general data architecture of named graphs and directories and their relations for morphological description and for specimen documents;
  * model for metadata associated with morphological descriptions and with specimen-related data;
  * detailed data model for morphological descriptions;
  * data model for free-text descriptions and their semantic annotations as well as for image annotations with specifications of regions of interest and their semantic annotation, all following the W3C Web Annotation Data Model;
* database processes
  * workflow actions for adding parts to the partonomy of a given morphological description document.
* entry form and GUI specifications:
  * our case-study for proof of concept: specimen document (specification of functionality only for the first panel and not for internal linking of entries, but the concept for the whole specimen document is completed, including the possibility of tracking history of a specimen and its relation to other specimens, like for instance if a DNA sample has been taken from an existing specimen);
  * morphological description document (with specification of functionality of the main document page and the entry forms for the different categories of parts);








Further information on the project is available at http://escience.biowikifarm.net - feel free to contact us at 
dev@morphdbase.de

This repository contains the SCMDB-Basic source code ontology for general features and processes of semantic Morph·D·Base, the SCMDB-MD source code ontology for the description module, and the SCMDB-S source code ontology for the specimen module of semantic Morph·D·Base.
In order to set up a running application, you additionally need the Semantic Programming Ontology (SPrO; https://github.com/SemanticProgramming/SPrO) and the SOCCOMAS source code ontology that provides further required process and feature specifications (SC-Basic; https://github.com/SemanticProgramming/SOCCOMAS). In order to execute these source code ontologies you also need the Java Interpreter (https://github.com/SemanticProgramming/Interpreter) and the Interface (https://github.com/SemanticProgramming/Interface). 

**Please be aware that this project is ongoing research! This code is for demonstration purposes only. Do not use
 in production environment!**
