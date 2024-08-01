---
sidebar_position: 1
---

# Introduction
s-elBat provides an iterative process that performs EL on tables. Given a 
KG containing a set of entities 𝐸 and a collection of named-entity 
mentions 𝑀, the goal of EL is to map each entity mention 𝑚 ∈ 𝑀 to its 
corresponding entity 𝑒 ∈ 𝐸 in the KG (CEA task). 
Moreover, given the subject column S, the approach provides the 
annotation, between S-column and other columns in the table, with a 
predicate in the KG (CPA task). 
Eventually, the approach provides the annotation for each column with a 
concept in the KG (CTA task).

## System Architecture
The s-elBat system comprises several key components, each playing a vital role in the EL process.

### General Overview
![s-elBat Architecture](/img/architecture.png)

This diagram illustrates the general architecture of s-elBat, showcasing its various modules and their interactions.

### Unsupervised Approach
![Unsupervised Process](/img/unsupervised-process.png)

The unsupervised approach of s-elBat involves feature extraction, context-based prediction, and export functionalities.

### Supervised Approach
![Supervised Pipeline](/img/supervised-process.png)

In the supervised approach, s-elBat incorporates advanced features including context-based and similarity predictions, along with feature extraction revision.