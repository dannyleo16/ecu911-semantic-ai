# Semantic Emergency Analysis using NLP and Ontologies

This repository contains research and implementation related to the paper:

**Semantic Modeling of ECU 911 Emergencies Using NLP and Ontologies**

Published in *Revista Tecnológica ESPOL (RTE)*.

DOI: https://doi.org/10.37815/rte.v37nE1.1351

---

## Overview

Emergency call centers such as ECU 911 receive large volumes of unstructured textual data from citizens.  
This project proposes a hybrid approach that combines Natural Language Processing (NLP) and semantic technologies to transform raw emergency reports into structured knowledge.

The system integrates:

- Named Entity Recognition (NER)
- Semantic classification of emergency incidents
- Ontology-based knowledge representation
- Logical inference using SWRL rules

---

## Architecture

The proposed pipeline consists of the following components:

1. **NLP Processing**
   - BERT model for Named Entity Recognition (NER)
   - XLM-RoBERTa for zero-shot emergency classification

2. **Data Processing**
   - Cleaning and normalization of emergency reports
   - Extraction of semantic features

3. **Knowledge Representation**
   - OWL ontology developed in Protégé
   - RDF knowledge graph generation

4. **Inference Layer**
   - SWRL rules derived from decision trees
   - Semantic reasoning using Pellet reasoner

5. **Validation**
   - SPARQL and SQWRL queries
   - Comparison with real ECU 911 incident labels

---

## Results

The system achieved **96.7% accuracy** when inferring the priority level of emergency incidents.

---

## Technologies

Python  
Transformers (HuggingFace)  
BERT  
XLM-RoBERTa  
Protégé  
OWL  
SWRL  
SPARQL  
Prolog  

---

## Paper

Paltin, D., Mejía, J., Orellana, M., & Zambrano-Martinez, J. (2025).  
Semantic Modeling of ECU 911 Emergencies Using NLP and Ontologies.  
Revista Tecnológica ESPOL.

https://doi.org/10.37815/rte.v37nE1.1351

---

## Author

Danny Leonardo Paltin
