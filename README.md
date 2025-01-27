# Network Analysis of a Hospital Ward: Structure, Community, and Interactions

## Overview 
This project explores informal communication networks among patients and healthcare workers (paramedical staff, medical doctors, administrative staff) in a hospital ward in Lyon, France. It examines how communication patterns between healthcare workers affect team dynamics and information flow to maximize patient care and hospital efficiency. The data is sourced from the Network Data Repository (Rossi and Ahmed, 2015), available [here](https://networkrepository.com).

## Research Questions
- Q1: What is the overall structure of the contact network between patients and healthcare workers in the ward?
- Q2: Are there communities of individuals that interact more frequently with one another?
- Q3: How does a healthcare worker's role (e.g., nurse, doctor) affect their interaction patterns with patients?

## Hypotheses
- H1: A structured pattern exists based on healthcare worker roles.
- H2: Individuals of the same role (e.g., nurses, doctors) will form distinct communities.
- H3: Medical doctors interact more frequently with each other than nurses do.

## Methods
- Community detection: identifies clusters of individuals who interact more frequently.
- Structural equivalence: measures similarities between different staff types.
- Reachability and small world phenomenon: analyzes how connected individuals within the network are. 

## Results 
- Network structure: different professional roles form distinct clusters and relationships.
- Community detection: six distinct communities were identified, with various degrees of overlap.
- Reachability: medical doctors have shorter average path lengths than nurses, supporting the hypothesis of hierarchical interaction patterns.
