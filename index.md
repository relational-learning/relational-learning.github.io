---
title: Relational Learning Resources
keywords: machine learning, relational data, graphical models, artificial intelligence, relational inference
tags: [Overview]
sidebar: mydoc_sidebar
permalink: index.html
---


# Welcome to Relational Learning

Relational learning is machine learning for relational data. Relational data provide information about entities and the relationships among them. This site collects resources to support research and teaching about relational learning. It includes pointers to datasets, implemented systems, tutorials and readings. 


## Relational Datasets

This section provides links to relational datasets and data formats.
Relational data have been studied in several communities, using different terminology and different data formats. Common terms for a relational dataset include the following. 

+ <i> Relational Database. </i> The most common relational format in industry based on the SQL standard.
+ <i> Network. </i> For network analysis, relational data can be visualized as a heterogeneous network with different types of nodes and (hyper)edges. 
+ <i> Matrix/Tensor </i>. In statistics and machine learning, data based on a relationship among two entities are represented using a matrix. Relationships involving more than two entities can be represented using a tensor. 
+ <i> Finite model, ground literals, facts. </i> The common representation in computational logic, including logic programming.
+ <i> A-box, triples, knowledge graph. </i> In description logic, semantic web ontologies, and the Resource Description Framework (RDF), relational data are also represented as collections of facts in a formal language. A knowledge graph visualizes the facts in a network. 

Relational learning algorithms can be applied to any of these data representations.

## Relational Learning Tasks

The site is organized around important learning tasks, and emphasizes approaches for which implementations are available. Tasks covered include the following.

+ <i> Classification. </i> Predicting a relational fact given other relational facts. Prediction types include:
  + <i> Link-based Classification. </i> Predicting the attribute of an entity given its relationships.
  + <i> Link Prediction. </i> Predicting the existence of a relationship between two entities.
  + <i> Link Attribute Prediction. </i> Predicting an attribute of a relationship between two entities. <i> Recommendation systems </i> are an extensively studied example, where the task is to predict the rating of an item by a user.
+ <i> Generative Modeling, Model Discovery, Unsupervised Learning. </i> Building a joint model of the attributes and relationships in a dataset. A common type of model utilizes <i> matrix/tensor factorization, </i> which supports relational clustering and network community detection.
+ <i> Frequency Modeling. </i> Supporting queries about the frequency of events or patterns in a relational dataset. 
+ <i> Anomaly Detection, Exception Mining. </i> Identifying anomalous or exceptional entities or events. 
+ <i> Network Analysis. </i> A complex network perspective highlights global topological properties of a relational dataset as a whole, and special properties of individual entities (nodes) in the dataset, such as centrality.
+ <i> Relationship Extraction, Knowledge Graph Discovery. </i> Extracting structured relationships from unstructured data is an important application for relational learning. The prime example of unstructured data is natural language text, where relational learning supports information extraction and machine reading. Recently relationship detection in images has been introduced as a task for computer vision.

  
## Relational Inference

We provide an overview of systems for relational inference. Inference is closely related to learning for two reasons: 

+ Relational inference is used to score relational models on a dataset (e.g. derive predictions on test cases)
+ Relational inference is required to fully leverage the knowledge discovered during relational learning to answer user queries.

Fields such as AI, knowledge representation, and computational logic have developed methods for reasoning with structured domain representations that support relational inference.

## Readings

This section provides links to readings with a broad scope, including survey articles, books, and tutorials. 

### Info for Editors

See the [Wiki](https://github.com/relational-learning/relational-learning.github.io/wiki/Github-Pages-Info) for a short customized collection of tips. The sidebar is an exhaustive list of authoring resources for the theme.


