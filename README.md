# Topological Data Analysis on Proteins

This repository contains a Jupyter Notebook project focused on the application of **Topological Data Analysis (TDA)** to protein structures, with particular attention to the theoretical foundations and algorithmic implementation of topological methods.

## Overview

The aim of this project is to study protein structures using tools from **Topological Data Analysis**, combining mathematical theory and computational implementation.

Proteins are represented as point clouds derived from atomic coordinates, and their topological properties are analyzed through simplicial complexes and the **Mapper algorithm**.  
The project also includes custom implementations of key algebraic and combinatorial structures used in TDA.

## Notebook Content

The core of the project is contained in the notebook:

- `Topological_Data_Analysis_on_Proteins.ipynb`

The notebook is structured as follows:

### 1. Installation (Google Colab)

Instructions and dependencies required to run the notebook in a Google Colab environment.

### 2. Libraries

Import and usage of the main scientific Python libraries used throughout the analysis.

### 3. Auxiliary Functions

Helper functions used for data manipulation, distance computations, and intermediate steps in the TDA pipeline.

### 4. Sparse Matrices over **𝑍₂**

A custom class for handling **sparse matrices over the field 𝑍₂**, which are essential for boundary operators in simplicial homology computations.

### 5. Simplicial Complexes

Implementation of a class representing **simplices** and simplicial complexes.

A brief theoretical recall is included:
> A simplicial complex is a collection of simplices closed under the operation of taking faces.

This section provides the mathematical backbone for the topological constructions used later in the notebook.

### 6. The Mapper Algorithm

Implementation and explanation of the **Mapper algorithm**, one of the main tools in Topological Data Analysis.

Mapper is used to:
- Project high-dimensional data to a lower-dimensional filter function
- Construct a simplicial representation of the data
- Reveal topological structures and clusters in protein data

## Dataset

Protein data used in this project are stored in the `Data/` directory (if present).  
The data typically consist of atomic coordinates extracted from protein structures and transformed into point clouds.

## Goals of the Project

- Provide a **theoretical and practical introduction** to TDA applied to proteins
- Implement core TDA structures from scratch for educational purposes
- Apply the Mapper algorithm to protein-related data
- Explore how topology can describe structural properties of proteins
